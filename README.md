# belly-button-challenge
This is an interactive dashboard that allows you to visualize bacterial diversity in human belly buttons (obscure, but interesting topic).

To display these interactive charts, we use D3.js and Plotly.js. By selecting a subject ID, you can explore different microbiome data dynamically.

**Features**
- dropdown menu (to select test subjects)
- bar chart (top 10 most commonly found bacteria)
- bubble chart (shows & identifies all bacterial species)
- demographic info (displays metadata of subjects(s))

**Instructions**
1. clone repo using
   git clone https://github.com/dsimonson43/belly-button-challenge.git
cd belly-button-challenge
2. open the file titled "index.html" in your browser. If visualizations are not displaying, it is advised to host it on a local server using this command in bash...
   python -m http.server 8000
NOTE: you must allow Windows security to have grant permissions to running a server

**Technologies used**
1. VS Code
2. D3.js
3. Javascript
4. Html
5. plotly.js
