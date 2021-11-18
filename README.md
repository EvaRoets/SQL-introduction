# SQL-introduction 📑

Watch the result of this project >> [here]()


## 🎯 Objectives
- Learn how ro connect a website with a database
- Explore [SQL Basics](https://github.com/becodeorg/gnt-verou-2/blob/main/3.The-Mountain/07.SQL-introduction/SQL-basics.md)
- Further develop research skills

## ✔️ Specifications
- Create a mySQL Database

### 🌱 Must-haves
#### 1️⃣ Set-up
- Install a database: MySQL (or MariaDB, but never both) This is included in your all in one pack you installed previously (Apache, MySQL, PHP).
- Install a database manager
    - 🍎/🐧/🎤 PhpMyAdmin: runs in the browser for easy access, but never to be used in production (security concern).
    - 🍎/🐧/🎤 Datagrip
    - 🍎/🎤 TablePlus: good interface, limited open tabs in the free version.
    - 🍎 SequelAce: successor to SequelPro.
    - 🎤 HeidiSQL

#### 2️⃣ Create a database: SQL-introduction
Make the following tables and populate them with some dummy data (have at least two entries for every table)
- groups: id, name, location, start_date, max_participants
- learners: id, name, email, active
- coaches: id, name

 #### 3️⃣ Execute the following commands
 - Get all data from the groups database
 - Get the name and email of the first learner, and alias the name to learner_name
 - Update the start date of the first_group (make it two months later)
 - Introduce a new field status which can contain a long text indicating the reason for postponing (bonus points if it's a creative one).
 - Delete someone from the learners table as they've decided to become an astronaut.
 
### 🌻 Nice-to-haves
#### 1️⃣ Try these more advanced commands
- Find a technique to make the connection in the database between learner, group and coach 
- Select a coach and all related groups
- Select a coach, all related groups and also the learners who are still active. 

### 💐 Extra nice-to-haves
- Run your SQL commands from PHP, by connectin PHP to the database first. 
