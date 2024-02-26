<<<<<<< HEAD
# Recipe-Website-Backend
This is the repository for the backend code of a recipe website. It's part of the final project for CS5610 Web Development.
=======
# Recipe-Backend

### Team Dandelion

### Group Members: Ruiwei Siu, Marcela Vijil, Renxin Xie, Allison Ying

## Iteration 2: CRUD Operations

We implemented CRUD operations for our main Recipes collection. We also added additional CRUD operations for comments and saved recipes- where appropriate. We tested these methods locally and through insomnia before connecting them with the frontend. Here are examples of each CRUD operation:

#### CREATE -- Create a new recipe
<img width="781" alt="image" src="https://media.github.khoury.northeastern.edu/user/9106/files/0b12e122-af66-4119-a71e-66b12812e5c1">
<img width="948" alt="image" src="https://media.github.khoury.northeastern.edu/user/9106/files/380fa159-902f-40a6-8702-ecaee3ec67e5">

#### READ -- Get recipe using recipe id
<img width="1092" alt="image" src="https://media.github.khoury.northeastern.edu/user/9106/files/3074471b-7aec-4fff-9d1e-064657389ba7">

#### UPDATE -- Adjusted Difficulty from 3 to 1
<img width="756" alt="image" src="https://media.github.khoury.northeastern.edu/user/9106/files/2c39df3c-b852-4176-82db-0160e28ce2b7">
<img width="676" alt="image" src="https://media.github.khoury.northeastern.edu/user/9106/files/a4049893-3928-4a3d-b289-8bd97613e2f5">

#### DELETE
<img width="808" alt="image" src="https://media.github.khoury.northeastern.edu/user/9106/files/69a05bcf-ee3e-409c-adeb-7203d32d7af4">
<img width="746" alt="image" src="https://media.github.khoury.northeastern.edu/user/9106/files/8c22f61b-9077-4e8f-9540-22d810609f67">

#### CONNECTED CLOUD DATABASE
<img width="965" alt="Screen Shot 2022-12-08 at 7 10 56 PM" src="https://media.github.khoury.northeastern.edu/user/8110/files/99739dd0-291c-4791-b992-9c111213408e">
<img width="825" alt="Screen Shot 2022-12-08 at 7 11 44 PM" src="https://media.github.khoury.northeastern.edu/user/8110/files/d57d09bf-b247-497e-8467-efbc58f62785">

### Roles
Allison Ying: Created and Modified CRUD methods for the backend(split with Ruiwei)

Ruiwei Siu: Created and Modified CRUD methods for the backend(split with Allison)

Marcela Vijil: Set up cloud based database and added appropriate routes to Heroku


## Iteration 1: Environment Setup

For the first iteration, we connected our backend with the recipees database and set up the routing and links to perform basic CRUD operations. Currently, we are using three collections for storing information:

1. Recipes : has unique id, title, author, cuisine type, cooking difficulty, dietary restrictions
2. Comments : has unique id, author, recipe id, comment, date
3. Saved : has user id, a list of saved recipe ids

CRUD METHOD (in progress):

1. Create / Post comment
2. Read / Get recipes: get all, by id, by list of IDs, by name, by author, by cuisine, by difficulty, by dietary restrictions
3. Update / Put comment
4. Delete comment

### Roles

Allison Ying:

1. Set up backend environment (ie. file structure and connections)
2. Route web links to their appropriate API methods
3. Route API requests to appropriate DAO methods (split with Renxin)

Renxin Xie:
1. Route API requests to appropriate DAO methods (split with Allison)
2. Connect MongoDB with backend
3. Initiate MongoDB data

![image](https://media.github.khoury.northeastern.edu/user/9709/files/0b7890c4-29b0-45f7-b7f2-32cabe1e7cdb)

![image](https://media.github.khoury.northeastern.edu/user/9709/files/65403133-818c-4686-b149-f1568960e0ec)

![image](https://media.github.khoury.northeastern.edu/user/9709/files/14f0e85a-de79-4525-9ff1-97de7d11ede4)


### See Front end README for Marcela Vijil and Ruiwei Siu contribution
https://github.khoury.northeastern.edu/TeamDandelion/Recipe-Frontend
>>>>>>> 5bf4224 (Initial commit)
