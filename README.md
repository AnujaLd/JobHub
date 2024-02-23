<h1 align="center" id="title">Job Hub</h1>

<p align="center"><img src="https://socialify.git.ci/AnujaLd/JobHub/image?description=1&amp;font=Inter&amp;forks=1&amp;issues=1&amp;name=1&amp;owner=1&amp;pattern=Circuit%20Board&amp;pulls=1&amp;stargazers=1&amp;theme=Light" alt="project-image"></p>

<p id="description">Developed a Job Management System to facilitate the interaction between employers and candidates. The system should include user registration authentication job posting application submission and a job board.</p>


  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Responsive Design
*   Employers - Registration and Login
*   Candidate - Registration and Login
*   Employers - Post a job/Edit Post View CV/Resume Admin Panel User Profile/Edit Acount User Management
*   Candidate - Apply for the job Upload CV/Resume Progress Level User Profile/Edit Acount
*   Job categorization

<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the repository</p>

<p>2. open the XAMPP and start the Apache and MySQL then Create the Database using PhpMyAdmin </p>

<p>3. Navigate to the project directory and create the .env file and following code copy & paste it on your .env and your created Database name paste on .env file DB_DATABASE={your DB name}</p>

```
APP_NAME=Laravel
APP_ENV=local
APP_KEY=
APP_DEBUG=true
APP_URL=http://localhost

LOG_CHANNEL=stack
LOG_DEPRECATIONS_CHANNEL=null
LOG_LEVEL=debug

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE={your database name}
DB_USERNAME=root
DB_PASSWORD=

BROADCAST_DRIVER=log
CACHE_DRIVER=file
FILESYSTEM_DISK=local
QUEUE_CONNECTION=sync
SESSION_DRIVER=database
SESSION_LIFETIME=120

MEMCACHED_HOST=127.0.0.1

REDIS_HOST=127.0.0.1
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_MAILER=smtp
MAIL_HOST=mailpit
MAIL_PORT=1025
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null
MAIL_FROM_ADDRESS="hello@example.com"
MAIL_FROM_NAME="${APP_NAME}"

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_DEFAULT_REGION=us-east-1
AWS_BUCKET=
AWS_USE_PATH_STYLE_ENDPOINT=false

PUSHER_APP_ID=
PUSHER_APP_KEY=
PUSHER_APP_SECRET=
PUSHER_HOST=
PUSHER_PORT=443
PUSHER_SCHEME=https
PUSHER_APP_CLUSTER=mt1

VITE_APP_NAME="${APP_NAME}"
VITE_PUSHER_APP_KEY="${PUSHER_APP_KEY}"
VITE_PUSHER_HOST="${PUSHER_HOST}"
VITE_PUSHER_PORT="${PUSHER_PORT}"
VITE_PUSHER_SCHEME="${PUSHER_SCHEME}"
VITE_PUSHER_APP_CLUSTER="${PUSHER_APP_CLUSTER}"


```


<p>4. Open a new terminal and run the following commands:</p>

```
composer install     
npm install        

```

<p>5. After installing dependencies Open a new terminal and migrate the database by running:</p>

```
php artisan migrate:fresh       
php artisan db:seed
```

<p>6. Open a new terminal and Generate the app key</p>

```
php artisan key:generate
```

<p>7. run project on live serve</p>

```
npm run dev
```

<p>8. Start the Artisan Serve to Open a new terminal and run Following Command</p>

```
php artisan serve
```

<p>8. Run the Application and Display the Home Page First of all Click the Register button and Register as a client then redirect the job Portal and logout and then Register as a admin</p>

<p>Enjoy & Happy Coding...</p>

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   Backend : PHP / Laravel 
*   Database : MYSQL
*   Front-end : HTML , CSS ,  Bootstrap
 

<h2>Project Screenshots:</h2>

<img src="https://i.ibb.co/nMPk331/Homepage1.png" alt="project-screenshot" width="600" height="300/">

<img src="https://i.ibb.co/gM8CRVb/homepage2.png" alt="project-screenshot" width="600" height="300/">

<img src="https://i.ibb.co/z7WZ47c/homepage3.png" alt="project-screenshot" width="600" height="300/">

<img src="https://i.ibb.co/Vvh4r9N/CVupload.png" alt="project-screenshot" width="600" height="300/">

<img src="https://i.ibb.co/JsS08hy/applyjob1.png" alt="project-screenshot" width="600" height="300/">

<img src="https://i.ibb.co/0J89m9r/Appliedprogress.png" alt="project-screenshot" width="600" height="300/">

<img src="https://i.ibb.co/PQfnqhY/jobpostadmin.png" alt="project-screenshot" width="600" height="300/">

<img src="https://i.ibb.co/n04tvPW/admindash1.png" alt="project-screenshot" width="600" height="300/">

<img src="https://i.ibb.co/jRbxstj/admin-Dashboard2.png" alt="project-screenshot" width="700" height="300/">

<img src="https://i.ibb.co/GRmJ3JM/category.png" alt="project-screenshot" width="600" height="300/">

<img src="https://i.ibb.co/4sMz852/CVView.png" alt="project-screenshot" width="600" height="300/">
