# [Finals Lab Task 1 - Creating a Database Using MySQL Workbench](https://github.com/user-attachments/files/19641635/Finals.Lab.Task.1.-.Ordona.docx)
- This portfolio is about learning MySQL basics through a multi-level company database. It includes tasks like writing SQL queries, creating table structures, and making an ER diagram or relational schema. The portfolio will also include SQL copies of the database and table structures to show how the database is built.

## Step by Step Process
1. Create the `employees` table:
   - Define `employee_id` as a unique integer, auto-increment, and primary key.
   - Define `employee_name` as a VARCHAR (up to 255 characters), and make it not null.
   - Define `manager_id` as an integer, which will be a foreign key referencing `employee_id` from the same table.

2. Create the `departments` table:
   - Define `department_id` as a unique integer, auto-increment, and primary key.
   - Define `department_name` as a VARCHAR (up to 255 characters), and make it not null.

3. Create the `employee_departments` table:
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.
   - Define `department_id` as an integer, which will be a foreign key referencing `department_id` in the `departments` table.
   - Set a composite primary key on the combination of `employee_id` and `department_id`.

4. Create the `employee_projects` table:
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.
   - Define `project_name` as a VARCHAR (up to 255 characters), and make it not null.

5. Create the `managers` table:
   - Define `manager_id` as a unique integer, auto-increment, and primary key.
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.

# Screenshots
## Query Statements
1. Employee Table
- ![Image](https://github.com/user-attachments/assets/6805108f-438c-457c-abb1-db088cf883df)
   
2. Department Table
- ![Image](https://github.com/user-attachments/assets/d76b2ad5-4f3d-40d3-87ba-93aa575bc88f)
   
3. Employee Department Table
- ![Image](https://github.com/user-attachments/assets/b353e0ee-c8a1-4324-86c9-31a233faf3a5)
  
4. Employee Project Table
- ![Image](https://github.com/user-attachments/assets/8d2163c5-05fc-47a0-9233-97a3420a9ebe)
   
5. Manager Table
- ![Image](https://github.com/user-attachments/assets/c152af94-8a34-41cb-84ac-1ee147fe1e5d)

## Table Structure
1. Employee Table
- ![Image](https://github.com/user-attachments/assets/e88aae18-3d76-456b-bca0-fa8b728cacfc)
   
2. Department Table
- ![Image](https://github.com/user-attachments/assets/c6a25c86-08e3-4727-9720-72acce8457d4)
   
3. Employee Department Table
- ![Image](https://github.com/user-attachments/assets/6839d85f-620a-4210-95e4-d0194e239f3c)
   
4. Employee Project Table
- ![Image](https://github.com/user-attachments/assets/e9ea098d-6978-4239-9267-2caad0d44bdf)
   
5. Manager Table
- ![Image](https://github.com/user-attachments/assets/b5ae7286-4434-41f5-928f-40bfe2635038)

## EER Diagram 
- ![Image](https://github.com/user-attachments/assets/aa184cf9-bcb3-406a-9185-419e669dc0b7)
