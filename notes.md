 1. Need to initialize tailwind (use following command)
 npx tailwindcss init

 2. After that setup the tailwind input and out style sheet (To generate output style sheet run this command)

npx tailwindcss -i ./src/input.css -o ./dist/style.css

 3.  Then link the tailwind css output style sheet  in your html

4. For getting continues updated style sheet run this command

npx tailwindcss -i ./src/input.css -o ./dist/style.css --watch