1-npm install
2-npm install -D node-sass nodemon
3-"build-css": "node-sass --include-path scss scss/precss.scss css/style.css",
"watch-css": "nodemon -e scss -x \"npm run build-css\""
4-npm run watch-css