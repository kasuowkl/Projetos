Conectando o VSCode no GitHub!

…or create a new repository on the command line
echo "# WKL" >> README.md
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kasuowkl/Projetos.git
git push -u origin main


…or push an existing repository from the command line
git remote add origin https://github.com/kasuowkl/WKL.git
git branch -M main
git push -u origin main
