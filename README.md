## Overview
**Date :** December 2020  
**Languages :** Javascript, Google Apps Script (GAS), HTML  
**Libraries :**  JQuery  
**IDE :**  Notepad++  
**Purpose :**  Presenting student work at exhibition  
**Learning Sources :**  Mashe Hawkin's google API examples  
**Time Spent :** 4 weeks

## Summary
The PDF contained above is a guide detailing how to use Google Sheets as a vessel for a public HTML scoreboard. The original process was developed as an honors project for the Computer Science pathway at Da Vinci Communications High School. The purpose is to allow students to compete for the best score on their favorite digital "escape rooms". The code demonstrated is appended onto existing student work, and tracks invisibly behind the scenes. Each time a player clicks while solving a puzzle, it increments a click counter on local storage. This value is passed between different HTML pages of an escape room. Javascript is used to dynamically generate and parse URLs that pass the click value around. Once the series of puzzles is completed, this final click counter is passed to a Google Apps Script (GAS). The GAS script utilizes Google's API to securely upload the final click score to a spreadsheet. This spreadsheet is displayed on a public HTML table for students to compare scores. Additionally, the spreadsheet takes in student nicknames and filters out any swear words entered. The final solution is content-independent javascript, allowing it to slot into many different student projects. The click tracking files can be copied into any student repository quickly. All that is required is a simple HTML script tag.  

## Takeaways
- APIs are powerful tools but are layered with security measures to prevent cyber attacks  
- JQuery can be used to create content-independent functionality, allowing HTML markup to be cleaner  
- Software in the real-world does not need to be flawless. Functionality takes place over form
- Managing forked repositories can lead to conflict and confusion, especially near deadlines  
- When designing for UX, you must consider the extreme diversity of users

## Links

#### Full PDF Writeup (including all code, 16 pages)
[PDF](GAS_CS_leaderboard_writeup.pdf)

#### Google Spreadsheet Used in Exhibition
[Final Scoresheet](https://docs.google.com/spreadsheets/d/1MkGE9Iy0QMtUh8Oka7PqXQGapbEwI4tHDLfMTEvVAUA/edit?usp=sharing)

#### Example Leaderboard
[Final Scoreboard](https://jtpz0.csb.app/?s=9999)
