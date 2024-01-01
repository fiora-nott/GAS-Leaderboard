## Overview
**Date :** 2020  
**Languages :** Javascript, Google Apps Script (GAS), HTML  
**Libraries :**  JQuery 
**IDE :**  Notepad++
**Purpose :**  Presenting student work at exhibition  
**Learning Sources :**  Mashe Hawkin's google API examples

## Summary
The PDF contained above is a guide detailing how to use Google Sheets as a vessel for a public HTML scoreboard. The original project was created as an Honors project for the Computer Science pathway at Da Vinci Communications High School. The purpose is to allow students to compete for the best score on their favorite digital "escape rooms". Each time a player clicks while solving a puzzle, it increments a click counter on local storage. This value is passed between different HTML pages of an escape room through the URL tags. Javascript is used to dynamically generate and parse URLs with the score data attached. Once the series of puzzles is completed, this final click counter is passed to a Google Apps Script (GAS). The GAS script utilizes Google's API to upload secure data to a spreadsheet. This spreadsheet is displayed on a public HTML table for students to compare scores. The final solution is content-independent, allowing it to slot into many different student websites. The click tracking javascript can be copied into any student repository quickly. All that is required is a simple HTML script tag to link the "onclick" listener.

## Takeaways
- C++ memory management requires extremely careful deconstruction, abstraction, and standard library wrappers  
- Templates are a tempting tool but ultimately make code hard to predict  
- Building my own variable types can reduce bloat immensely in high-level functions  
- OpenGL's reputation as an aging framework is due to frustrating boilerplate and egregious debugging tools  
- File organization is key because of the surplus header files generated in C++  
- Macros can be a powerful experimentation tool, but need to be used sparingly  

## Video Montage

Warning - Video contains multiple instances of flashing colors

▶️ [Youtube Link](https://www.youtube.com/watch?v=kP7laC2ohEo)
