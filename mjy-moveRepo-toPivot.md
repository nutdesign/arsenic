# How to move arsenic repo files to Pivot


## Set up Terminal environment

* cd ~/dev/arsenic-mjy/arsenic-lace
* npm install
* bower install
* npm start


## How to compile SCSS manually

* cd to ~/dev/arsenic-mjy/arsenic-lace/src
* npm run build  // use this line to avoid "Error: File to import not found or unreadable: util/util."
* --- OR ---
* Usage: scss [options] [INPUT] [OUTPUT]
* scss ./assets/scss/app.scss ../dist/assets/css/app.css 


## Extract components

* docHead
* header
* footer
* add %%pivot_messages%%

