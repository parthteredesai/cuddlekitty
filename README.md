
# cuddleKitty 

Welcome to **cuddleKitty**! [cite_start]Follow the steps below to quickly clone, install, and run the project locally on your machine.

---

## 🛠️ Prerequisites

Before you begin, ensure you have **Node.js** and **Git** installed on your system.

1. Open your terminal or command prompt.
2. Verify your installations by running:
   ```bash
   git --version
   node --version

Install nodemon globally to handle automatic server restarts
   ```bash
   npm install -g nodemon
   ```
1. Prepare WorkspaceCreate an empty folder named cuddleKitty and open it inside VS Code. Open the integrated VS Code terminal.  

2. Clone the RepositoryRun the following clone command directly. Note: Ensure you include the entire command including the trailing dot . to clone files straight into your current folder.

```bash
git clone [https://github.com/parthteredesai/cuddlekitty.git](https://github.com/parthteredesai/cuddlekitty.git) .
```

To install all the dependancies
```bash
npm install
```

make env file and add your credentials
```bash
PORT=8080
SESSION_SECRET=
MONGO_URL=
```
run application
```bash
nodemon server.js
```
go on browser and enter URL :
localhost:8080/
Signup with Email and username
