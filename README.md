@echo off
color 0a
title MOJ SYSTEM
echo WITAJ W SYSTEM
echo ==============
echo (SYSTEM WYLACZ SIE)
timeout 10
goto BLAD SYSTEM
:BLAD SYSTEM
cls
echo ======================
echo SYSTEM-BLAD-TIME (10)
echo ======================
echo WYLACZ SYSTEM -TIME (SYSTEM BLAD-NT-OP9(500)BLAD SYSTEM-99=2)(ERROR-%time%)(WYLACZ SYSTEM-9=SYSTEM)
timeout 5
goto bios
:bios
cls
echo system name Moj System
echo system GB 2000
echo system RAM 2000
echo system STWORZY Ian Idzik
pause
goto WYLACZ SYSTEM#1
:WYLACZ SYSTEM#1
cls
echo ================
echo witaj na system
echo ================
pause
timeout 9
goto JAK MASZ NA IMIE
:JAK MASZ NA IMIE
cls
echo wpisz swoje imie.
set /p imie=
cls
goto login
:login
echo wpisz tu haslo
set /p haslo=
haslo=1234
goto pulipt
:pulipt
cls
echo ZALAGOWANY NA SYSTEM=WIN32:%imie%.
echo CZAS %time%
echo LOGIN TO %login%
echo POOGODA C20
echo.
echo (1) Restart 
echo (2) notatnik
echo (3) zegar
echo (4) kalkulator
echo (5) off
echo (6) Info
echo (7) Restart Comtuper
echo (8) Ustawienia
echo (9) gra
echo (10) NOTANIK JAKO bat
echo (11) galeria
echo (12) nieznay dir
echo (13) LOGIAWNIE DO KONTO
echo (14) NOWY PILKI
echo (15) GRA#2
echo (16) pogoda
set /p "cho=Wybierz Numerek"
if %cho%==1 goto Restart
if %cho%==2 goto notepad
if %cho%==3 goto clock
if %cho%==4 goto kalkulator
if %cho%==5 goto off
if %cho%==6 goto Info
if %cho%==7 goto Restart Comtuper
if %cho%==8 goto Ustawienia
if %cho%==9 goto GRA
if %cho%==10 goto NOTANIK JAKO bat
if %cho%==11 goto galeria
if %cho%==12 goto nieznay dir
if %cho%==13 goto LOGIAWNIE DO KONTO
if %cho%==14 goto NOWY PILKI
if %cho%==15 goto Gra#2
if %cho%==16 goto pogoda
:notepad
cls
echo mozesz pisac.
set /p p=
cls
echo nadaj nazwe pilku.
set /p 1=
cls
echo %p% > %1%.txt
cls
goto pulipt
:clock
cls
echo godzinie to
echo %time%
pause
cls
goto pulipt
:kalkulator
echo kalkulator
pause > nul
cls
:start kalkulator
set /p calc=wpisz dzalanie 
set /a calc=%calc%
echo %calc%=%calc2%
pause > nul
cls
goto pulipt
:Restart
cls
goto login
:off
cls
exit /b
:Info
cls
echo system name Moj System
echo system GB 2000
echo system RAM 2000
echo system STWORZY Ian Idzik
pause
cls
goto pulipt
:Restart Comtuper
cls
echo RESTART SYSTEM
pause
goto JAK MASZ NA IMIE
:Ustawienia
cls
echo conncet wift name %wift%
echo conncet blehuooh name %blehuooh%
echo (1) zmien haslo
echo (2) back
set /p "cho=Wybierz Numerek"
if %cho%==1 goto zmien haslo
if %cho%==2 goto back
echo ========================
:zmien haslo
echo haslo
set /p haslo=
set /p haslo=
set /p haslo=
pause
cls
goto pulipt
:back
cls
goto pulipt
:GRA
cls
echo witaj w grze
echo click 0
pause
echo click 1
pause
echo click 2
pause
echo click 3
pause
echo click 4
pause
echo click 5
pause
echo click 6
pause
echo click 7
pause
echo click 8
pause
echo click 9
pause
echo click 10
pause
echo cilck 11
pause
echo click 12
pause
echo click 13
pause
echo click 14
pause
echo click 15
pause
echo click 16
pause
echo click 17
pause
echo click 18
pause
echo click 19
pause
echo click 20
pause
echo click 21
pause
echo click 22
pause
echo click 23
pause
echo click 24
pause
echo click 25
pause
echo click 26
pause
echo click 27
pause
echo click 28
pause
echo click 29
pause
echo click 30
pause
echo click 31
pause
echo click 32
pause
echo click 33
pause
echo click 34
pause
echo click 35
pause
echo click 36
pause
echo click 37
pause
echo click 38
pause
echo click 39
pause
echo click 40
pause
echo click 41
pause
echo click 42
pause
echo click 43
pause
echo click 44
pause
echo click 45
pause
echo click 46
pause
echo click 47
pause
echo click 48
pause
echo click 49
pause
echo click 50
pause
echo click 51
pause
echo click 52
pause
echo click 53
pause
echo click 54
pause
echo click 55
pause
echo click 56
pause
echo click 57
pause
echo click 58
pause
echo click 59
pause
echo click 60
echo you win 60 cilck
pause
goto pulipt
:NOTANIK JAKO bat
cls
echo wpisz wiadmosci
set /p wiadmosci=
cls
echo nadaj nazwe pilku.
set /p 1=
cls
echo %wiadmosci% > %1%.bat
pause
goto pulipt
:galiera
echo ##############
echo  #MOJ ZDEJCIA#
echo ##############
pause
cls
goto pulipt
:nieznay dir
cls
dir
pause
cls
goto pulipt
:LOGIAWNIE DO KONTO
cls
echo login for login:
set /p login=
echo czy to login %login%
echo OK
pause>nul
echo login for password
set /p password=
echo WELCOME%login%
goto pulipt
:NOWY PILKI
REM Utworzenie nowego folderu
mkdir MojaNowaFolder

REM Przejście do nowego folderu
cd MojaNowaFolder

REM Utworzenie nowego pliku tekstowego
echo Witaj w moim nowym pliku tekstowym > nowyplik.txt
pause
goto pulipt
:Gra#2
cls
echo (GRA2)
echo (GRA START)
echo (=========)
echo level 1
pause
goto Gra
:Gra
cls
echo (1)
pause
cls
echo (2)
pause
cls
echo (3)
pause
cls
echo (4)
pause
cls
echo (5)
echo (YOU WIN)
pause
goto LEVEL 2
:LEVEL 2
cls
echo (1)
pause
cls
echo (2)
pause
cls
echo (3)
pause
cls
echo (4)
pause
cls
echo (5)
pause
cls
echo (6)
pause
cls
echo (7)
pause
cls
echo (8)
pause
cls
echo (9)
pause
cls
echo (10)
echo (you win)
pause
cls
goto Level 3
:Level 3
cls
echo (1)
pause
cls
echo (2)
pause
cls
echo (3)
pause
cls
echo (4)
pause
cls
echo (5)
pause
cls
echo (6)
pause
cls
echo (7)
pause
cls
echo (8)
pause
cls
echo (9)
pause
cls
echo (10)
pause
cls
echo (11)
pause
cls
echo (12)
pause
cls
echo (13)
pause
cls
echo (14)
pause
cls
echo (15)
pause
cls
echo (16)
pause
cls
echo (17)
pause
cls
echo (18)
pause
cls
echo (19)
pause
cls
echo (20)
echo (you win)
pause
goto LEVEL 4
:LEVEL 4
cls
echo click 1
pause
echo click 2
pause
echo click 3
pause
echo click 4
pause
echo click 5
pause
echo click 6
pause
echo click 7
pause
echo click 8
pause
echo click 9
pause
echo click 10
pause
echo cilck 11
pause
echo click 12
pause
echo click 13
pause
echo click 14
pause
echo click 15
pause
echo click 16
pause
echo click 17
pause
echo click 18
pause
echo click 19
pause
echo click 20
pause
echo click 21
pause
echo click 22
pause
echo click 23
pause
echo click 24
pause
echo click 25
pause
echo click 26
pause
echo click 27
pause
echo click 28
pause
echo click 29
pause
echo click 30
pause
echo click 31
pause
echo click 32
pause
echo click 33
pause
echo click 34
pause
echo click 35
pause
echo click 36
pause
echo click 37
pause
echo click 38
pause
echo click 39
pause
echo click 40
pause
echo click 41
pause
echo click 42
pause
echo click 43
pause
echo click 44
pause
echo click 45
pause
echo click 46
pause
echo click 47
pause
echo click 48
pause
echo click 49
pause
echo click 50
echo (YOU WIN)
pause
goto LEVEL 5
:LEVEL 5
cls
echo click 0
pause
echo click 1
pause
echo click 2
pause
echo click 3
pause
echo click 4
pause
echo click 5
pause
echo click 6
pause
echo click 7
pause
echo click 8
pause
echo click 9
pause
echo click 10
pause
echo cilck 11
pause
echo click 12
pause
echo click 13
pause
echo click 14
pause
echo click 15
pause
echo click 16
pause
echo click 17
pause
echo click 18
pause
echo click 19
pause
echo click 20
pause
echo click 21
pause
echo click 22
pause
echo click 23
pause
echo click 24
pause
echo click 25
pause
echo click 26
pause
echo click 27
pause
echo click 28
pause
echo click 29
pause
echo click 30
pause
echo click 31
pause
echo click 32
pause
echo click 33
pause
echo click 34
pause
echo click 35
pause
echo click 36
pause
echo click 37
pause
echo click 38
pause
echo click 39
pause
echo click 40
pause
echo click 41
pause
echo click 42
pause
echo click 43
pause
echo click 44
pause
echo click 45
pause
echo click 46
pause
echo click 47
pause
echo click 48
pause
echo click 49
pause
echo click 50
pause
echo click 51
pause
echo click 52
pause
echo click 53
pause
echo click 54
pause
echo click 55
pause
echo click 56
pause
echo click 57
pause
echo click 58
pause
echo click 59
pause
echo click 60
echo (YOU WIN)
pause
cls
goto pulipt
:pogoda
cls
echo dzis jest podoga C20
echo Pogoda jutro ma bci C18
echo Pogoda po jutro ma bci C17
echo Pogoda po po jutro ma bci C16
pause
cls
goto pulipt

