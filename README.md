# Girls-Who-Code--Processing
int x = 0;

void setup() {
  size(400, 400);
}

void happyFace(int x, int y) {
  fill(#FEFF03);
  ellipse(x,y, 150, 150);
  
  
  fill(#000000);
  ellipse(x-20, y-25, 25, 25); // Left eye
  ellipse(x+20, y-25, 25, 25); //Right eye
  
  ellipse(x, y+25, 75, 25); //Mouth
  
  
} 
  
void draw() {
  
  happyFace(x, 200);
  x = x + 5;
  //happyFace(mouseX, mouseY);
  
  //ellipse(x, y, l, w);  
  //ellipse(200, 300, 25, 25);
  
 //fill(#FFFFFF);
 //ellipse(mouseX, mouseY, 25, 25);
 
 //fill(#FF5281);
 //ellipse(200, 200, 150, 150);//Face
 
 //fill(#FFFFFF);
 //ellipse(180, 175, 25, 25); //Left Eye 
 //ellipse(220, 175, 25, 25); //Right Eye
 
 //ellipse(200, 225, 75, 25);
}
