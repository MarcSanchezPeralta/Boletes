En aquest programa, farem apareixer una boleta que vagi sola d'esquerra a dreta només un cop.

int dreta = (0) ;
void setup(){
  size(500,200);
}

void draw(){
  background(255);
  dreta = dreta + 1;
  if (dreta > 500) ; 
  noStroke();
  fill(255,0,0);
  ellipse(dreta,100,50,50) ;
}
