# How to push .jl file to git repository

**1. Download GitHub Desktop, log in, and clone this repository to your computer.**

2. After you make your code in Jupyter Notebook, save your file as "Executable Script" (`.jl`) 
   (But you can also leave it as `.ipynb` Jupyter Notebook and push the notebook to Git.)

3. Then open the terminal and write:
   ```bash
   cd "C:\path\to\your\repository"

4. Check the status using `git status` command
5. Write `git add "Name of the file.jl"`
6. `git commit -m "Message you want to provide(what you have changed in the code)"`
7. `git push origin main`
8. Check the git if it has been uploaded

That way we can see the changes made by other people and do not lose in different versions of the code.