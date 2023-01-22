# NoteItDown

![HTML](https://img.shields.io/badge/-HTML-gray?style=flat&logo=html5)
![CSS](https://img.shields.io/badge/-CSS-1fb30e?style=flat&logo=css3)
![TypeScript](https://img.shields.io/badge/-TypeScript-black?style=flat&logo=typescript)
![Python](https://img.shields.io/badge/-Python-black?style=flat&logo=python)
![React](https://img.shields.io/badge/-React-black?style=flat&logo=react)
![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-566be8?style=flat&logo=tailwindcss)
![Zustand](https://img.shields.io/badge/-Zustand-566be8?style=flat&logo=zustand)
![React-Query](https://img.shields.io/badge/-React%20Query-f2cbde?style=flat&logo=reactquery)
![Django](https://img.shields.io/badge/-Django-9ef0b4?style=flat&logo=django&logoColor=darkgreen)
![DjangoRestFramework](https://img.shields.io/badge/-Django%20Rest%20Framework-9ef0b4?style=flat)
![SQLite](https://img.shields.io/badge/-SQLite-white?style=flat&logo=sqlite&logoColor=blue)
![Postman](https://img.shields.io/badge/-Postman-black?style=flat&logo=postman&logoColor=orange)

## Description

NoteItDown is a note-taking full-stack web application built with React on the frontend and Django/DRF on the backend.

<ins>Features</ins>:

- Light/dark mode (depending on your device settings)
- CRUD opertions for user credentials (JWT based)
  - Signup/Login/Logout
  - Get a user info to be displayed on home page
  - Update email & password
  - Delete user account
- CRUD operations for notes (JWT token based)
  - Create a note using react-quill rich text editor
  - Update a note
  - View all notes at once
  - View a specific note
  - Delete a note
- A rich text editor for notes (react-quill)
- Download/Export a note as a pdf

## Demo
https://user-images.githubusercontent.com/53491186/213941262-99a78cbb-0da4-43b0-b65f-b4512728ce02.mp4

## Screenshots
![](readme_res//Screenshots.png)


## Overview Of The Architecture

<details>
    <summary>Click to expand!</summary>
    <br/>

![](readme_res//NoteItDown%20Architecture.png)

> **<ins>Note to self</ins>:** _This section is meant to give an overview of how the frontend & backend are structured and how they communicate with each other. If refactoring or adding new features alter the architecture, change the pictures too via [draw.io](https://draw.io/) using the file `NoteItDown Architecture.drawio` in `readme_res` folder._

</details>

## Api Endpoints Documentation

View the api endpoints at [noteitdown-api-docs](https://documenter.getpostman.com/view/25138891/2s8Z73xqLn). I used postman for documenting the api endpoints.

## Basic Folder Structure Overview

<details>
    <summary>Click to expand!</summary>
    <br/>

<img src="readme_res//Folder%20Structure%20Dissection.png" height="400"/>


> **<ins>Note to self</ins>:** _This section is meant to give an overview of how the folders are structured. If refactoring or adding new features alter the folder structure, change the pictures too via [draw.io](https://draw.io/) using the file `Folder Structure Dissection.drawio` in `readme_res` folder._

</details>

## Installation And Usage

<details>
    <summary>Click to expand!</summary>
    <br/>
  
#### <ins>**General**</ins>

- Built on `OS: Windows 10`.
- Download/clone this repository using `git clone https://github.com/AI-14/Note-It-Down.git`.
- `cd Note-It-Down`.

#### <ins>**For frontend**</ins>

1. Installation
   - Make sure you have the following versions and softwares/engines installed:
     - `node: >= 16.14.0`
     - `npm: >= 8.3.1`
   - Make sure you are in the project's directory. Then run the command `cd frontend`.
   - Then install all dependencies by typing in the terminal `npm install` or `npm i`.
   - To install devDependencies, type `npm install --save-dev`.

> **Note:** _If any dependency is missing or an error shows up, install it using `npm install moduleName`_.

2. Usage
   - To start the project, type `npm start`.

#### <ins>**For backend**</ins>

1. Installation
   - Make sure you have the following versions and softwares/engines installed:
     - `python: >= 3.8`
     - `pip: >= 21.3.1`
   - Make sure you are in the project's directory. Then run the command `cd backend`.
   - Then create a virtual environment using the command `py -m venv yourVenvName` and activate it using `yourVenvName\Scripts\activate.bat`.
   - Then run the following command `pip install -r requirements.txt`. With this, all the dependencies will be installed in your virtual environment.
   - Then run the commands:
     - `python manage.py makemigrations`
     - `python manage.py migrate`

> **Note:** _If any dependency is missing or an error shows up, install it using `pip install moduleName`_.

2. Usage
   - To start the project, type `python manage.py runserver`.

</details>
