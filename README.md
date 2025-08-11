# Ecommerce 2025 - Parent Repository

This repository is the **parent container** for the Ecommerce 2025 project. It organizes the project into two separate Git submodules:

- **frontend** — The frontend application
- **backend** — The backend application

Each submodule is an independent Git repository with its own codebase and history.

---

## Project Structure

ecommerce-2025/
├── frontend/ # Git submodule linked to https://github.com/thihaswe/ecommerce-frontend.git
├── backend/ # Git submodule linked to https://github.com/thihaswe/ecommerce-backend.git
├── .gitmodules # Submodule configuration file
├── README.md # This file

yaml
Copy
Edit

---

## How to Clone the Repository

To clone the full project with all submodules (frontend and backend), use:

````bash
git clone --recurse-submodules https://github.com/thihaswe/ecommerce-2025.git



## How to Clone the Project with Submodules

This project uses Git submodules to include the frontend and backend repositories.

### To clone the full project with all submodules:

```bash
git clone --recurse-submodules https://github.com/thihaswe/ecommerce-2025.git
or
git submodule update --init --recursive
````
