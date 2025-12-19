Method 1: 
git - repo create <br>
enter <br>
git clone <Link> <br>
enter <br>
git add . / git add index.html <br>
enter <br>
git commit -m "msg" <br>
enter <br>
git push origin main <br>
enter <br>

Method 2:
folder - computer <br>
git init <br>
enter <br>
git remote add <link> <br>
enter <br>
git add . <br>
enter <br>
git commit -m "tailwind-cli" <br>
enter <br>
git push origin master <br>
enter <br>

Method 3:
git branch --> how many branch in repo <br>
enter <br>
git branch <branch name> <br>
 ex: git branch devlopment <br>
enter <br>
git branch <br>
enter <br>
git checkout <branch name> <br>
 ex:git checkout devlopment <br>
enter <br>


#Tailwind css CLI

<h1>Website</h1>
1.Copy - npm install tailwindcss @tailwindcss/cli


<h1>Vs Code</h1>
1. open Terminal <br>
2. paste cmd <br>
3. Enter <br>
4. create index.html and input.css <br>
5. create index.html --> <link rel="stylesheet" href="./output.css"> <br>
6. create the input.css file and import the--><code> @import "tailwindcss"; <code> <br>
7.package.json file in the write the script and start : <br>
<code>
    "scripts": {
    "dev": "npx @tailwindcss/cli -i ./input.css -o ./output.css --watch" 
  }
</code> <br>
8. In termnal -> npm run dev