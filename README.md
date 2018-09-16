
Syftet med att automatiseringen är att det gör det går fortare och enklare att arbeta med ett projekt då ändringarna uppdateras direkt och skickas automatiskt till en sammanslagen och minimerad fil. Vilket gör att man inte behöver göra om hela processen.


Jag har valt att publicera filerna på Github eftersom det verkar vara en populär och lätt användarvänlig plattform.


## De npm paket jag använt är: 

gulp-uglify används för gulp, tips från föreläsning. Detta paket används för att minimera js filer.
https://www.npmjs.com/package/gulp-uglify

gulp-concat används för gulp, tips från föreläsning.
https://www.npmjs.com/package/gulp-concat

gulp-watch används för gulp, tips från föreläsning. Detta paket även uppdaterar tomma mappar utan att frysa. 
https://www.npmjs.com/package/gulp-watch

Gulp-clean-css används för gulp och minimerar css
https://www.npmjs.com/package/gulp-clean-css

 
### Öppna terminalen och skriv in: 
Git clone https://github.com/m-e-k-w/webb-mom2.git
### efter det:
npm install gulp

Sen använder man task deafault genom att skriva in gulp för att allt ska rulla på och uppdatera sig. CSS och JS filer minimeras och konkateneras automatiskt till pub mappen.
