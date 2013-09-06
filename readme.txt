Planet Kubb Scoring App
=======================

CONTRIBUTORS/DEVELOPERS
=======================
Head over to https://sourceforge.net/projects/planetkubbscoringapp/


What is it?
===========

This application was designed to assist in the scoring of Kubb matches that will link up to the Planet Kubb Wiki to create statistics and store the matches for future examination.

The app was originally designed and started by Shane Hultquist of KubbCanada.ca.  The first Java/Android application written by him (learning as he went).

Inside the Program
==================

The main "variables" of this program are stored in GlobalVars.java.  There are some functions in there that may no longer be used and should be cleaned up at some point.  This is where any and all gloval variables will be kept for the purposes of adding things to the database.  The original design of the app only produced a text file that was what the PK Wiki needed to input a game.  Over time it changed to a database and the whole concept of the GlobalVars may no longer be needed.  It is something to look at after the initial application is completed.

Inputting games
===============

Before entering any games, players must be added to the database.  This is currently done on the main screen and pressing "players".  This will allow you to add/edit/delete players from the database.

Once all the players are added (eventually sucking this information down from Planet Kubb and having the ability to add new players), you can go back to the main screen and start entering a game.

Game entry is fairly intuitive and will do many of the initial calculations for you.  After every turn the game is saved to the database.
