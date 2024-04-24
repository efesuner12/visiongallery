# VisionGallery
VisionGallery is a web-application designed to help people organise their image stock using certain metadata, like location and datetime and additional data achieved via the use of Google Vision AI, such as detected colours, objects, labels, text and emotions.

Developed as a group project @ The University of Birmingham
- Efe Suner
- Paul Aldea
- Joseph Kidger
- Gurpreet Pawar
- Havandeep Singh Khatkar
- Zhouchang Zhang

base dir: ~/app/team33-21/visiongallery/

images stored in /mnt/visiongallery_storage/media/

To Run Server:
--------------
- git clone git@github.com:efesuner12/visiongallery-master.git
- cd visiongallery-master
- python3 -m venv venv
- source venv/bin/activate
- pip3 install -r requirements.txt
- cd visiongallery
- python3 manage.py

To Run Server Using Docker (~/app/team33-21/):
----------------------------------------------
1. docker-compose down
2. docker-compose build
3. docker-compose up

Server hosted on https://visiongallery.bham.team (offline now)

