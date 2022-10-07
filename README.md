# weBlog  [![License: IPL 1.0](https://img.shields.io/badge/License-IPL_1.0-blue.svg)](https://opensource.org/licenses/IPL-1.0) 
 CMS-style blog site that can publish articles, blog posts, thoughts and opinions
 
## Description

    
## Table of Content
- [Installation](#installation)
- [Usage](#usage)
- [Contributions](#contribution)
- [Licenses](#licenses)
- [Questions](#questions)
- [live site](https://bloggersintech.herokuapp.com/login) // Checkout the deployed website 
    
        
## Installation
To set up and utilise this project. Take the following steps.

- Step 1: Clone this repository
- ![image](https://user-images.githubusercontent.com/104241247/194509957-20c4c275-a73b-41e0-9943-bc2e5aeb2e16.png)


- Step 2: Install dependencies by running the ``` npm install ``` command in the command line
- Step 3: Open your code editor by running the command ``` code . ```
- Step 4: Create your database.<br> Luckily, theres a schema.sql file that we can run to create the database automatically. 
You run this file by first logging in to you mysql server and running the ```source db/schema.sql ```
  command to create the database
- Step 5: Create .env file
- Step 6: Type in your database credentials. Ensure that they use the format
```
DB_NAME = new_db  // Our database name in this case 
DB_USER = YOUR mysql USERNAME 
DB_PW = YOUR mysql PASSWORD

```
OR
If you have a jawsDb url from your heroku 
```
JAWSDB_URL = `Your jawsBD URL`
```
- Step 7(Optional!): A seeds folder has been added to populate the database with some data.<br>
To run this seeds folder, we must run the ``` npm run seed ``` command. 
    
## Usage
nteractive blog site that allows users to make posts comment on posts, edit posts and so on
    
    
## Licenses
### IBM Public License Version 1.0
[![License: IPL 1.0](https://img.shields.io/badge/License-IPL_1.0-blue.svg)](https://opensource.org/licenses/IPL-1.0) 



## Screenshots

![image](https://user-images.githubusercontent.com/104241247/193959614-b2bf129a-97ca-452d-835f-c4f4ab998b5d.png)
![image](https://user-images.githubusercontent.com/104241247/194508502-1de8d8f2-3902-4261-9f4b-d7fac23cdbf4.png)
![image](https://user-images.githubusercontent.com/104241247/194508543-da48fc70-9517-4ae2-b172-0c32e196be46.png)


## Contribution
Made with ❤️ by Timi


## questions
For additional questions contact me via email on [femiladiranerife24@gmail.com](mailto:femiladiranerife24@gmail.com) or [view some other projects](https://github.com/FOR-TIMI/).

