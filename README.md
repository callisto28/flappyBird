## FLAPPY BIRD

Le célèbre petit jeu flappy bird, 
HTML/ CSS & Javascript

avec l'utilisation du canvas

`const render = () => {
    index++;
    //background en double pour le défilement du décor
    ctx.drawImage(img, 0, 0, canvas.width, canvas.height, -((index * (speed / 2)) % canvas.width) + canvas.width, 0, canvas.width, canvas.height);
    ctx.drawImage(img, 0, 0, canvas.width, canvas.height, -((index * (speed / 2)) % canvas.width), 0, canvas.width, canvas.height);
    ......
`