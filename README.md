# Meta BIT Jaipur website
### Exam Papers and study material (For all B.E. students)

## Motivation
This project was started by [@shubhambhattar](https://github.com/shubhambhattar) during the End semester examinations in Nov 2016. The motivation was to improve the way we share exam papers and study materials during the semesters.

It is no surprise that the same material is provided to every new batch. Lots of emails from the CR (Class Representative) are forwarded and WhatsApp groups are filled with queries like "Please send `<subject>` paper" during exam time. And the quality of images recieved of papers were very bad (most of the time).

This website aims to remove all those inefficiencies by creating a simple solution to the above problem. Let's not burden CR with all the work. They are not just there to send us all the materials. People should make an effort to get themselves what they want.

## Choosing an Online Storage service to store files
I chose Dropbox to store all the files. One of the main issues was to get enough bandwidth in a free-tier - there is a daily limit to the amount of bandwidth that can be used in free-tier. Even though the storage provided in Dropbox's free-tier was less, the bandwidth limits seemed fine. I decided to put a backup in [MediaFire](https://mediafire.com) (for progress on this, check Projects tab above) because it does not have bandwidth limitations but it has following disadvantages:
- Contains ads
- Every file has to downloaded individually (which can be a pain when anyone has to download multiple files, a general use case scenario). No option to download a folder.
Thus, Mediafire could work as a decent backup serivce.

## Organising the data
In a higher level, the data could have been classified on the basis of either **Streams** or **Semesters**. The hierarchial structure is given below:

- B.E.
  - I
    - Subject_1
      - endsem
      - midsem
      - notes
    - Subject_2
    - .
  - II
    - Subject_1
    - .
  - III
    - CSE
      - Subject_1
      - .
    - ECE
      - Subject_1
      - .
    - EEE
  - .
  - VIII
    - CSE
    - ECE
    - EEE

In the website, there are three options to download the data.
- A student can download the materials of the whole semester in a single click by choosing Semester and Stream in the index page.
- If not the whole package, then the student can go the particular webpage link for the semester and has the option to choose the Subjects in that semester and whether he/she wants to download `Midsem`, `Endsem` or `Notes` of that subject.
- The last option is to browse through the Dropbox account and find the exact file to download - an option necessary in case any new file is uploaded during the semester (see Changelog below).

Each semester's webpage will contain a **Changelog** at the bottom. This will record all the changes made in the databse for that particular semester (with dates and stream) for future reference. This way, students won't have to check the databse each time for any new content uploads. The reviewer(volunteer) has to check for the following things:
- No copyrighted material gets stored in the database.
- No redundancy occurs.

Papers are uploaded after scanning them from the CamScanner App (to get a good quality image). The files are named with the following convention.

```
<subject_acronym>_<midsem/endsem>_<year>_<lab/labquiz/ >_<page_number>
```


> Note: All files from the website will be downloaded in `.zip` format. The subject list (Browse Subjects option) will contain both theory and practical subjects. Some practical subjects are omitted if question papers are not available. 

## Contributing to the database

It would be impractical for a single person to manage all the materials and papers for every semsester and stream. So, three  volunteers were choosen from III year - each from a different branch. A volunteer will manage the materials of his/her stream. I & II semester work would be shuffled among them.

And to simplify their work, an option to directly upload the materials and papers was added in the website in the [Contribute](https://metabitj.github.io/contribute.html) page. The uploaded materials will be reviewed by the volunteers (who are provided access to the database). Thus, any student can now add to the database reducing the legwork for the volunteers.


### Database Maintainers
----------------------------

- I & II sem: Divik Mittal(B.E. CSE 5th)
- CSE: Divik Mittal
- ECE:
- EEE:

### Website Maintainer   
---------------------

[Shubham Bhattar](https://github.com/shubhambhattar) (B.E. CSE 2017)
