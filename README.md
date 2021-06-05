if(gameState===2){
    playButton= createButton('Play');
    playButton.position=(windowWidth/2,windowheight/2);
    playButton.mousePressed(()=>{
    gameState=2;
    })
  }