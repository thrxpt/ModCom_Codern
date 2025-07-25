# ModCom_Codern

## How to contribute

1. **Fork this repository**
   - Click the "Fork" button at the top right of this page to create your own copy of the repository.
2. **Clone your fork**
   - Copy the URL of your forked repository and run:
     ```sh
     git clone https://github.com/your-username/ModCom_Codern.git
     ```
3. **Create a new branch**
   - Navigate to the project directory and create a branch for your feature or fix:
     ```sh
     git checkout -b your-branch-name
     ```
4. **Add your problemset (follow the Example folder structure)**
   - Inside the `Example` folder, create a new folder named after your problem.
   - In your problem folder, add:
     - Your solution file (e.g., `solution.c`)
     - A `Description.md` file describing the problem
     - A `Testcases` folder containing input/output files (e.g., `1in.txt`, `1out.txt`, etc.)
   - Example structure:
     ```
       YourProblemName/
         solution.c
         Description.md
         Testcases/
           1in.txt
           1out.txt
           ...
     ```
5. **Commit your changes**
   - Stage and commit your changes:
     ```sh
     git add .
     git commit -m "Describe your changes"
     ```
6. **Push to your fork**
   - Push your branch to your forked repository:
     ```sh
     git push origin your-branch-name
     ```
7. **Open a Pull Request**
   - Go to your fork on GitHub and click "Compare & pull request".
