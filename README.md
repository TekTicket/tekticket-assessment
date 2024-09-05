### Task Description for the Mock Ticket

**Title:** Build a Simple REST API for a To-Do List

**Objective:**  
Create a simple REST API that allows users to manage a to-do list. The API should support the following operations:
- Create a new task
- Retrieve all tasks
- Update a specific task
- Delete a specific task

**Requirements:**
1. **Languages/Frameworks:** The task should be implemented using one of the following:
   - Python (Flask or FastAPI)
   - JavaScript/TypeScript (Node.js with Express)
   - Java (Spring Boot)
   - Ruby (Sinatra or Rails)
   - Go (Gin or Echo)

2. **Endpoints:**
   - `POST /tasks`: Create a new task. The request body should include `title` and `description`.
   - `GET /tasks`: Retrieve a list of all tasks.
   - `PUT /tasks/{id}`: Update the `title` or `description` of a specific task.
   - `DELETE /tasks/{id}`: Delete a specific task.

3. **Database:** You may use an in-memory data structure (like a list or a dictionary) to store tasks, or a lightweight database like SQLite.

4. **Testing:** Write unit tests for your API using a testing framework relevant to your chosen language (e.g., pytest, JUnit, Mocha).

5. **Documentation:** Include a README file with instructions on how to run the API locally, how to run the tests, and any other relevant information.

**Bonus Points:**
- Implement authentication for the API using tokens (JWT or any other method).
- Add pagination to the `GET /tasks` endpoint.

**Time Estimate:** This task should take no more than 3 hours to complete.

---

### Fork Instructions

---

**Forking the Repository:**

1. **Fork the Repository:**
   - Click on the "Fork" button at the top right corner of this page to create a copy of this repository under your GitHub account. This will allow you to work on the task independently.

2. **Clone the Forked Repository:**
   - Clone the repository to your local machine using the following command:
     ```bash
     git clone https://github.com/your-username/tekticket-assessment.git
     ```
   - Replace `your-username` with your GitHub username.

3. **Create a New Branch:**
   - Navigate to the cloned repository directory and create a new branch for your work:
     ```bash
     git checkout -b feature/your-branch-name
     ```
   - Replace `your-branch-name` with a descriptive name for your branch.

4. **Complete the Task:**
   - Follow the task instructions provided in the `README.md` file and complete the task within the specified time.

5. **Commit and Push Your Changes:**
   - After completing the task, commit your changes:
     ```bash
     git add .
     git commit -m "Completed the tekticket assessment"
     ```
   - Push your changes to your forked repository:
     ```bash
     git push origin feature/your-branch-name
     ```

6. **Submit a Pull Request:**
   - Once your changes are pushed, go to your forked repository on GitHub, and you will see an option to create a pull request (PR). 
   - Click on "Compare & pull request," provide a brief description of your work, and submit the PR to the main repository.

7. **Await Feedback:**
   - Your submission will be reviewed, and feedback will be provided through the pull request discussion.

---
