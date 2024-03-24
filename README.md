# mern - whatsapp

How to run:

- Clone this repository or fork it.
  - To clone this repository type `git clone https://github.com/dmts90/MERN-Whatsapp.git` on your command line
  - To fork this repository, click fork button of this repository then type `git clone https://github.com/<your username>/whatsapp-clone.git`
- Inside `server` folder, create a new file named `.env` which stores informations about server side such as `ATLAS_URI`, `SECURITY_KEY` and `CLIENT_URL` informations
  - store your database URI inside `ATLAS_URI` variable
  - store your security key inside `SECURITY_KEY` variable
  - store your client url inside `CLIENT_URL` variable
  - example:
  ```
  ATLAS_URI =mongodb+srv://admin:<password>@cluster0.8aezk.gcp.mongodb.net/whatsappClone?retryWrites=true&w=majority
  SECURITY_KEY = D73373D9B4ED6FEC5B8B2DAF6WA929B1C7D14CDC88B196EBDCCEA77AFF7BB9
  CLIENT_URL = http://localhost:3000/
  ```
- Inside `client` folder, create a new file called `.env` which stores your information about client side such as `REACT_APP_SECURITY_KEY` and `REACT_APP_BACKEND_URL` informations

  - store your security key inside `REACT_APP_SECURITY_KEY` variable, note that this value must same as `SECURITY_KEY` in `server/.env` file
  - store your server url inside `REACT_APP_BACKEND_URL`
  - example:

  ```
  REACT_APP_SECURITY_KEY = D73373D9B4ED6FEC5B8B2DAF6WA929B1C7D14CDC88B196EBDCCEA77AFF7BB9
  REACT_APP_BACKEND_URL = http://localhost:5000
  ```

- Install all dependencies

  - Client side: on the `client` directory type `npm install`(or `yarn`)
  - Server side: on the `server` directory type `npm install`(or `yarn`)

- Run it on node js:
  - Client side: on the `client` directory type `npm start` (or `yarn`)
  - Server side: on the `server` directory type `npm start` (or `yarn`)
    
![Whatsapp clone demo](https://drive.google.com/uc?export=view&id=1LCLdnYzsxcCmqFxaw3oIEPR-D30N5zMG)
