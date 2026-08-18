# GameVault
lightweight, offline mobile app built with Flutter that helps you track how much money you’ve spent on video games.

No accounts. No subscriptions. No unnecessary features -- yet teehee 
Just simple, fast tracking.
------------------------------------------------------------------------
(Features)
 Track total money spent on games
 Add purchases with game name + amount
 View spending stats (monthly + total)
 See top games by total spending
 View detailed purchase history per game
 Edit purchases
 Delete purchases
 Clean dark mode UI
 Fully offline (no internet required)
-------------------------------------------------------------------------
(Tech Stack)
Framework: Flutter
Language: Dart
Database: SQLite (sqflite)
Local Storage: Device-only (no cloud)
State Management: Basic StatefulWidgets
---------------------------------------------------------------------------
(Data Flow)
User Input (UI)
     ↓
Add Purchase Screen
     ↓
DBHelper.insertPurchase()
     ↓
SQLite Database
     ↓
Home / Games / Stats Screens reload data
     ↓
UI updates with new totals
------------------------------------------------------------------------------

