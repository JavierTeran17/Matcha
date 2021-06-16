//Iniciar proyecto de git
git init

//Preparar archivos que se convertirán en commit
git add .
// el punto agrega todos los archivos modificados

// Crear commit con su mensaje
git commit -m "Aqui va el mensaje"

// Agregar remoto "Solo la primera vez"
git remote add origin https://github.com/JavierTeran17/Matcha.git

//Enviar commit al servidor
git push -u origin master


