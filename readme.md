MAPDOX — Real Geophoto Intelligence System

Bilingual local OSINT tool designed to parse image metadata, extract raw GPS telemetry via OpenStreetMap geocoding, and estimate environmental conditions natively.

Tool Interface:

https://i.postimg.cc/T25QLNbH/Novo-projeto-545-70CB078.png

How to Use:
1. Run the script using Python.
2. Choose your preferred language (English or Portuguese).
3. Accept the educational/security terms of use.
4. Input the exact file path of the image you want to analyze.
5. Review the generated geolocation logs, infrastructure telemetry, and OSINT links.
6. Choose whether to save the results into a local TXT report.

Termux Installation:
$pkg update && pkg upgrade -y$ pkg install python git -y
$ pip install pillow colorama requests
$git clone https://github.com/mrmaestrox156-debug/MAPDOX.git$ cd MAPDOX
$ python mapdox.py

Kali Linux Installation:
$sudo apt update && sudo apt upgrade -y$ sudo apt install python3 python3-pip git -y
$pip3 install pillow colorama requests$ git clone https://github.com/mrmaestrox156-debug/MAPDOX.git
$ cd MAPDOX
$ python3 mapdox.py
