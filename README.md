# eKnowYC: Virtual Verification System
The world is embracing virtual platforms. Everything has now been switched to an online mode. Security systems have also been applied virtually, which has resulted in a significant
difference as compared to the offline mode. Virtual verification, the process of verifying a banking client's identification , has now become an important aspect of it,
not only for KyC but also for many other online marketplaces. In contrast to traditional KyC registration, e-KyC eliminates the requirement for physical documents and 
in-person verification. Facial recognition can also help improve security and safety in places other than stores, such as airports and banks. Optical Character Recognition (OCR)
is primarily used by businesses to improve the efficacy and efficiency of their operations. Its capacity to quickly search through massive amounts of data is incredibly useful,
especially in office settings where there is a lot of document input and scanning. The efficiency of facial recognition, Optical Character Recognition utilising deep learning models, 
and the virtual process that deals with the entire eKnowYC system are all discussed in this study. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. S
### Prerequisites
It is assumed that the Node JS(>14) and Python(>3.0) and MySQL are installed in your local machine.


The project is uses Svelte JS as Frontend, Flask as server and MySQL as the Persistant Storage. Flask installation can be found in the following link.

* [Flask installation](https://flask.palletsprojects.com/en/2.1.x/installation/)

```
pip install mysql-connector-python 
npm install svelte
pip install deepface
pip install opencv
```

### Installing


* #### Server
  * It is assumbed that a new virtual environment is created and Flask is installed in it. And the virtual environment is activated.
  * To fireup the server execute the following commands:

```
export FLASK_APP=server
flask run -p 3000
```

* #### FrontEnd
  * It is assumbed that node is installed in the locla machine.
  * To install all the necessary packages, navigate to the FrontEnd directory, then run the following command

```
npm install
```
 * In order to start the develeopment server,use this command
 ```
npm run dev
```
* #### Database
  * To import the database folder, import the SQL dump file from Database direcoty, into the MySQL database.






## Built With

* [Svelte](https://svelte.dev/) - The Front End JS Platfrom
* [Flask](https://flask.palletsprojects.com/en/2.1.x/) - Server 
* [MySQL](https://www.mysql.com/) - Persistant Storage


## Authors

* **Rajarshi V**  - [Rajarshi V](https://github.com/RAJ-LION)

## Acknowledgments

* Shri. Dr. Pallav K Baruah
* Raghava k


## 🤝 Support
Contributions, issues, and feature requests are welcome!
