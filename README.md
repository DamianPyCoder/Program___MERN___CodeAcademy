<a name="readme-top"></a>

#  DAMI<b>ACADEMY</b>

## 1. Built with MERN stack.  

As for our database layer, we employ MongoDB. To establish the backend routing system, we leverage ExpressJS. ReactJS serves as our frontend technology, while NodeJS powers our backend operations.  
  

<img src="https://github.com/DamianPyCoder/RandomAssets__icons__V2/blob/main/MongoDB.svg" width="50">  <img src="https://github.com/DamianPyCoder/RandomAssets__icons__V2/blob/main/ExpressJS-Dark.svg" width="50">  <img src="https://github.com/DamianPyCoder/RandomAssets__icons__V2/blob/main/React-Dark.svg" width="50">  <img src="https://github.com/DamianPyCoder/RandomAssets__icons__V2/blob/main/NodeJS-Dark.svg" width="50">  

Other tools I have utilized during the application development include Visual Studio Code or for example, the React dependency called [TinyMCE](https://www.tiny.cloud/get-tiny/?utm_source=google&utm_medium=ppc&utm_campaign=[ds]_dynamic_search_aw_eu&utm_term=&utm_content=[ds]_eu_ad1&gad_source=1&gclid=Cj0KCQjwmMayBhDuARIsAM9HM8eJuyPFmjPFDGObEdAnECAnQXyMKNhw3rVLPlf2x6HZ7_Z4uTGV2kkaAjztEALw_wcB) is utilized to implement a complete text editing system for the blogs.  

<img src="https://github.com/DamianPyCoder/RandomAssets__icons__V2/blob/main/VSCode-Dark.svg" width="50">  


<p align="right">(<a href="#readme-top">back to top</a>)</p>




## 2. Client.  
Complete web application for an online computer courses school, featuring a client where users can register. At the top of the client, we have links to social media and a menu that can be edited from the server's admin panel. 

On the client's Home page, there's a banner and various courses displayed. Users can scroll down through the Home page to obtain more information, such as study methodology or how to ask questions to instructors. In the footer, there's a newsletter subscription option; the submitted email addresses are registered and stored in our MongoDB database.

![](https://github.com/DamianPyCoder/Program___MERN___CodeAcademy/blob/main/picts/0.png)
![](https://github.com/DamianPyCoder/Program___MERN___CodeAcademy/blob/main/picts/2.png)
![](https://github.com/DamianPyCoder/Program___MERN___CodeAcademy/blob/main/picts/3.png)

For database viewing, we utilize MongoDB's Robot, where we can observe how user emails are registered.

<p align="center">
  <a href="https://github.com/DamianPyCoder/Program___MERN___CodeAcademy/blob/main/picts/email.png">
    <img width="380" height="420" src="https://github.com/DamianPyCoder/Program___MERN___CodeAcademy/blob/main/picts/email.png" title="email" alt="email">
  </a>
  <a href="https://github.com/DamianPyCoder/Program___MERN___CodeAcademy/blob/main/picts/newsletterRoboMongoDb.png">
    <img width="440" height="420" src="https://github.com/DamianPyCoder/Program___MERN___CodeAcademy/blob/main/picts/newsletterRoboMongoDb.png" title="newslet" alt="newslet">
  </a>
</p>

The Home page's top menu includes options for courses and a blog. Upon entering the courses section, users can access numerous courses dynamically added via the course ID from an online course portal called Udemy. We connect to Udemy's API to fetch course data and display it on the page.

In the blog section, there are posts with and without dates.
<p align="center">
  <a href="https://github.com/DamianPyCoder/Program___MERN___CodeAcademy/blob/main/picts/blog.png">
    <img width="400" height="210" src="https://github.com/DamianPyCoder/Program___MERN___CodeAcademy/blob/main/picts/blog.png" title="blog1" alt="blog1">
  </a>
  <a href="https://github.com/DamianPyCoder/Program___MERN___CodeAcademy/blob/main/picts/blogEjemplo.png">
    <img width="400" height="210" src="https://github.com/DamianPyCoder/Program___MERN___CodeAcademy/blob/main/picts/blogEjemplo.png" title="blog2" alt="blog2">
  </a>
</p>



<p align="right">(<a href="#readme-top">back to top</a>)</p>



## 3. Server.
Additionally, there's a server-side admin panel where new users can be created. Users registering via the client's form need validation here as they're initially created as inactive users. An administrator must activate the account for users to log in.

The admin panel features a left-side menu with options for users, menu, courses, and blog.

In the users section, administrators can view and manage active and inactive users, change their status, edit, delete, or create new ones. Any action such as deletion or editing triggers a pop-up message notification.

In the menu section, menus can be activated or deactivated, and new ones can be created.

In the courses section, administrators can create new courses, edit, or delete existing ones. Using the ID, courses from Udemy can be added. All information such as name, price, etc., can be modified.

Lastly, in the blog section, administrators can view, edit, create, and delete posts using an integrated text editor



<p align="right">(<a href="#readme-top">back to top</a>)</p>




## 4. Typography, Colors, Icons and Other Elements.  

### 4.1 Icons.


<img src="https://github.com/DamianPyCoder/Program___MERN___CodeAcademy/blob/main/picts/icono.png" width="50"> <img src="https://github.com/DamianPyCoder/Program___MERN___CodeAcademy/blob/main/picts/iconoGreen.png" width="50">   

Source of the icon: [Circlon tech](https://www.flaticon.es/icono-gratis/programacion-web_7970086?term=programacion&page=4&position=13&origin=search&related_id=7970086)  


### 4.2 Color palette.

![](https://github.com/DamianPyCoder/Program___MERN___CodeAcademy/blob/main/picts/paleta.png)
<p align="right">(<a href="#readme-top">back to top</a>)</p>




## 5. How to Download the Repository / Install the APK.


<details>
<summary><b>Clone the Repository</b></summary>
   
   If you don't have the repository on your local machine yet, clone it using Git. Open a terminal in Visual Studio Code and run:
   ```bash
   git clone <repository_url>
   ```
   Then, navigate to the project directory:
   ```bash
   cd <project_directory_name>
   ```

</details>




<details>
<summary><b>Install Dependencies</b></summary>
   You need to install dependencies for both the server (backend) and the client (frontend). Typically, MERN projects have two main folders: one for the backend and one for the frontend.

   - **Backend:**
     Navigate to the backend folder and run `npm install` to install the dependencies:
     ```bash
     cd backend
     npm install
     ```

   - **Frontend:**
     Navigate to the frontend folder and run `npm install`:
     ```bash
     cd ../frontend
     npm install
     ```
</details>



<details>
<summary><b>Configure Environment Variables </b></summary>  
   
   Ensure you have the necessary environment variables set up. These usually include the MongoDB database URL, the server port, and any other keys needed for the project. Create a `.env` file in the root of your project (both in the backend and frontend if necessary) and define the environment variables. An example `.env` file for the backend might look like this:  
   
   ```
   PORT=5000
   MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/<db_name>?retryWrites=true&w=majority
   JWT_SECRET=your_jwt_secret
   ```  
      
</details>

      
<details>
<summary><b>Start the Server and Client</b> </summary>
   Once the dependencies are installed and the environment variables are configured, you can start the server and the client. Typically, this is done from the backend and frontend folders respectively:
  
   - **Start the Server:**
     
     ```bash
     cd backend
     npm start
     ```
     
     This should start the server on the configured port (e.g., http://localhost:5000).

   - **Start the Client:**
     
     In another terminal or a new terminal tab, navigate to the frontend folder and run:
     
     ```bash
     cd frontend
     npm start
     ```
     
     This should start the React application on the configured port (e.g., http://localhost:3000).
     
</details>


<details>
<summary><b>Verify Everything is Working</b> </summary>  
   
   Open your web browser and navigate to the address where your frontend application is running (e.g., http://localhost:3000). 
   The application should be up and running and communicating with the backend server.  
   
</details>


<details>
<summary><b>Example Project Structure </b></summary>  
   
A typical MERN project might have the following structure:  
   
```
my-mern-project/
├── backend/
│   ├── node_modules/
│   ├── package.json
│   ├── .env
│   ├── server.js
│   └── ...
├── frontend/
│   ├── node_modules/
│   ├── package.json
│   ├── .env
│   ├── public/
│   ├── src/
│   └── ...
└── README.md
```
  
By following these steps, you should be able to run your MERN stack project in Visual Studio Code.  

</details>



<p align="right">(<a href="#readme-top">back to top</a>)</p>






