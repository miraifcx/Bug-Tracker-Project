# 🛠️ Collab – Project Collaboration & Bug Tracker

**Collab** is a simple yet functional **project collaboration web app and bug tracker**, designed to help development teams **track software bugs**, **manage tasks**, and **collaborate on projects** in a Kanban-style interface.

Originally created as my **final project for CS50: Introduction to Computer Science**, Collab marks my first full-stack attempt at building a **modular, multi-page web app with authentication, database integration, and task tracking**.

> 🗓️ **Built in 2022** — Still a work in progress.

## ✨ Features

### ✅ App

* Clean, minimalist UI for intuitive task tracking
* Modular design structure for easy maintenance

### 📁 Projects

* Create and manage multiple projects
* Invite or collaborate with other team members
* Edit project info and ownership

### 🐛 Tickets

* Create and track issues using Kanban-style boards
* Add detailed descriptions and assign ticket priority
* Comment and interact on ticket threads
* (Planned) cross-platform support

### 👤 User

* User registration and login
* Profile management and password updates

## 🧱 Tech Stack

* **Python 3 + Flask** – Backend framework
* **SQLite** – Lightweight relational database
* **HTML, CSS, JS** – Frontend technologies
* **Jinja2** – Templating engine
* **Modular Flask Blueprints** – For clean architecture
* **Forms & Validation** – With custom utilities and helpers

## 📁 Project Tree

> A detailed breakdown of the directory structure shows the modularity of the application, separated by feature:

```
Collab                                                 
├─ app.py                                              
├─ collab.db                                           
├─ License                                             
├─ README.md                                           
└─ Tracker                                             
   ├─ collab.db                                        
   ├─ config.py                                        
   ├─ errors                                           
   │  ├─ handlers.py                                   
   │  ├─ static                                        
   │  │  └─ errors                                     
   │  │     └─ errors.css                              
   │  ├─ templates                                     
   │  │  └─ errors                                     
   │  │     └─ apology.html                            
   │  └─ __init__.py                                   
   ├─ helpers.py                                       
   ├─ index                                            
   │  ├─ static                                        
   │  │  └─ index                                      
   │  │     ├─ head.css                                
   │  │     ├─ head.js                                 
   │  │     ├─ index.css                               
   │  │     ├─ index.js                                
   │  │     ├─ navigation-rail.css                     
   │  │     └─ project.js                              
   │  ├─ templates                                     
   │  │  └─ index                                      
   │  │     ├─ head.html                               
   │  │     ├─ index.html                              
   │  │     └─ layout.html                             
   │  ├─ views.py                                      
   │  └─ __init__.py                                   
   ├─ models.py                                        
   ├─ profile                                          
   │  ├─ forms.py                                      
   │  ├─ static                                        
   │  │  └─ profile                                    
   │  │     ├─ changePassword.css                      
   │  │     ├─ country-dropdown-styles.css             
   │  │     ├─ profile.css                             
   │  │     └─ profile.js                              
   │  ├─ templates                                     
   │  │  └─ profile                                    
   │  │     ├─ newPassword.html                        
   │  │     └─ profile.html                            
   │  ├─ views.py                                      
   │  └─ __init__.py                                   
   ├─ projects                                         
   │  ├─ forms.py                                      
   │  ├─ static                                        
   │  │  └─ projects                                   
   │  │     └─ project.css                             
   │  ├─ templates                                     
   │  │  └─ projects                                   
   │  │     └─ project-modal.html                      
   │  ├─ views.py                                      
   │  └─ __init__.py                                   
   ├─ static                                           
   │  ├─ background.css                                
   │  ├─ flags                                         
   │  ├─ fonts                                         
   │  │  ├─ Poppins-Medium.ttf                         
   │  │  ├─ Rubik-Light.ttf                            
   │  │  ├─ Rubik-Medium.ttf                           
   │  │  ├─ Rubik-Regular.ttf                          
   │  │  └─ Salin-medium.otf                           
   │  ├─ fonts.css                                     
   │  ├─ form-modal.css                                
   │  ├─ form-modal.js                                 
   │  ├─ helper.js                                     
   │  └─ root.css                                      
   ├─ tickets                                          
   │  ├─ forms.py                                      
   │  ├─ static                                        
   │  │  └─ tickets                                    
   │  │     ├─ ticket-details.css                      
   │  │     ├─ ticket-details.js                       
   │  │     ├─ ticket.js                               
   │  │     └─ tickets.css                             
   │  ├─ templates                                     
   │  │  └─ tickets                                    
   │  │     ├─ comment.html                            
   │  │     ├─ like.html                               
   │  │     ├─ ticket-details.html                     
   │  │     ├─ ticket-modal.html                       
   │  │     └─ tickets.html                            
   │  ├─ views.py                                      
   │  └─ __init__.py                                   
   ├─ user                                             
   │  ├─ forms.py                                      
   │  ├─ static                                        
   │  │  └─ user                                       
   │  │     ├─ login.js                                
   │  │     ├─ register.js                             
   │  │     └─ user-styles.css                         
   │  ├─ templates                                     
   │  │  └─ user                                       
   │  │     ├─ login.html                              
   │  │     └─ register.html                           
   │  ├─ views.py                                      
   │  └─ __init__.py                                   
   └─ __init__.py                                      

```

## 🎓 Learning Outcomes

* Learned how to architect a modular full-stack web app
* Integrated multiple Flask Blueprints and organized features cleanly
* Implemented authentication and session handling securely
* Applied CRUD principles in managing tickets, users, and projects
* Worked with forms, JavaScript-enhanced UI, and error handling

## 👥 Authors

* 👨‍💻 [@AceBurgundy](https://github.com/AceBurgundy) – Full Stack Developer, Project Lead
* 👥 [@AACaps](https://github.com/AACaps) – Contributor

## 📜 License

This project is licensed under the **MIT License**.
See the [LICENSE](./License) file for more details.
