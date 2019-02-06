### This file is for use of the university of Colorado at Boulder Embedded Systems Engineering Professional Masters Program.

### This is a free library to be used for teaching ECEN5813.

### Class:  ECEN5813 - Principles of Embedded Software
### Current Year: 2019
### Current Semester: Spring

**Adding yourself to the student files**

**Steps**

1) Modify the students.json file in the ./git-assignment/students-sp19 directory of this repo. You will need to add a unique username key and a couple of characteristics. When you add a new line, put a comma on the previous line before adding to the bottom. See example below.

  *format:*
  ```
  "identikey_username": {
      "file": "identikey_username.json",
      "name": "Your First and Last Name"
  }
  ```
  *example:*
  ```
  "kegr4640": {
      "file": "kegr4640.json",
      "name": "Kevin Gross"
  }
  ```

2) Change directories into the students sub-folder and add a file with the same name as the file you put in the above code.
        ```
        $ cd students
        ```

3) In this file you are to add a block of formated text that gives details on your Super Power if you were a super hero. You need to add your hero name, your super power, if you have a cape (true/false), and if you have a cape, what the color of the cape would be. Example below.

  *format:*
  ```
   {
     "SuperHeroName": "your-choice-superhero-name",
     "SuperPower": "a super hero power",
     "Cape": true or false,
     "CapeColor": "color of your cape"
   }
   ```

  *example:*
  ```
   {
     "SuperHeroName":"Chef Kef",
     "SuperPower":"Delicious breakfast",
     "Cape":true,
     "CapeColor":"White",
   }
   ```
