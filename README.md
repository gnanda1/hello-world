### Simple Git Project to build Git Portfolio

The Git README.md file contains a simple git project. You can expand in future and multiple git repositories to build a portfolio of git projects.  

1. Ensure **Git is installed** in your terminal. To check if git is installed successfully run the following command. 
```
git version
```
2. **Configuring Git**
Now let's configure Git with your name and email address. Run the following shell command, but replace "YOUR NAME" with your actual name:
```
git config --global user.name "YOUR NAME"
```

Then, run the following shell command, but replace "YOUR EMAIL ADDRESS" with your actual email address:
```
git config --global user.email "YOUR EMAIL ADDRESS"
```
3. Click on this [GitHub](https://docs.github.com/en/get-started/quickstart/hello-world) URL.
Follow section 1 to finish creating a hello-world repository.

4. Run ```git clone {url}``` from the command line (replace {url} with the clone URL)
5. Create a branch 
```
git checkout -b testbranch
```
6. Make a small change (use nano if you want to edit a file from the command line).
7. Commit the change 
```
git commit -am 'test'
```
8. Push the branch to GitHub 
```
git push origin testbranch
```