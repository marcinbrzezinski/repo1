Jak zacząć projekt?
===================
  
Inicjowanie GITa w folderze lokalnym
-------------------------------------

###Instalacja GITa w systemie Linux

Instalacji programu GIT dokonuje się poprzez polecenie w konsoli: `sudo apt install git` 

###Tworzenie folderu

W terminalu przejdź do wybranej lokalizacji i wpisz polecenie `mkdir repo1` a następnie `cd repo1`

>Lista dostępnych komend dostępna jest pod poleceniem `git help`
  
###Pierwszy plik

Aby utworzyć plik testowy w konsoli wpisz komendę `touch test.txt` lub `> test.txt`

###Inicjowanie GITa

1. Wykonaj polecenie `git init`
2. Przy użyciu polecenia `ls -la` dokonaj sprawdzenia czy został utworzony katalog `.git` 


Konfigurowanie GITa
-------------------

###Konfigurowanie połączenia z [github.com](https://github.com "GitHub"
  103  git status
  104  git add test.txt
  105  git status
  106  git add .
  107  git status
  108  git commit -m "Utworzenie nowego pluku"
  109  git config --global xbrzezinx@gmail.com
  110  git config --global user.email "xbrzezinx@gmail.com"
  111  git config --global user.name "marcinbrzezinski"
  112  git commit -m "Utworzenie nowego pluku"
  113  git status
  114  apt-get install mc
  115  sudo apt-get install mc
  116  mc
  117  git log
  118  git test.txt
  119  nano test.txt
  120  git status
  121  git add .
  122  git status
  123  git log
  124  git commit -m "Dodano nowe wartości"
  125  git log
  126  git test.txt
  127  nano test.txt
  128  git add .
  129  git commit -m "Trzecia, lepsza zmiana"
  130  git log
  131  git commit
  132  cm
  133  git log -2
  134  git log -1
  135  git log --help
  136  git log -1
  137  git log -2
  138  git log --dense
  139  git remote add origin https://github.com/marcinbrzezinski/repo1.git
  140  git push -u origin master
  141  nano test.txt
  142  `/

  143  ~/
  144  nano ~/.gitconfig
  145  nano test.txt
  146  git commit -m "Sprawdzenie połaczenia z github.com"
  147  git add.
  148  git add .
  149  git commit -m "Sprawdzenie połaczenia z github.com"
  150  git push
  151  git log
  152  history > readme.md
