U lokalu aplikaciju je potrebno pokrenuti na sledeci nacin:
U folderu neuraro/src/FrontEnd/ je potrebno otvoriti terminal i ukucati komandu npm install i nakon toga ng serve kako bi se pokrenula angular aplikacija
U folderu neuraro/src/WebService/ je potrebno otvoriti terminal i pokrenuti FastAPI mikroservis komandom uvicorn main:app --reload
U folderu nerurao/srcc/WebService/ je potrebno otvoriti terminal i pokrenuti Flask mikroservis komandom python flask_main.py
U folderu neuraro/src/Backend/ je potrebno kreirati folder Resources, nakon toga potrebno je kreirati bazu uz pomoc komande dotnet ef database update i zatim pokrenuti aplikaciju komandom dotnet watch run

NAPOMENA: Ako se prilikom pokretanja nekog od mikroservisa prijavi da fali neki modul, taj modul treba instalirati.
