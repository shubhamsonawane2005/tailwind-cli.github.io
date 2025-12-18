Method 1: 
git - repo create
enter
git clone <Link>
enter
git add . / git add index.html
enter
git commit -m "msg"
enter
git push origin main
enter


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