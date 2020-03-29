# processing

'''
void setup(){
  size(800,400);
  textSize(128);
}
int i, a =1;
void draw(){
  background(194);
  if(keyPressed)
    a = key -'0';
  text("Graphics", i = i+a, 200);
  fill(255,0,0);
  if(i>800 || i <0)
    i =0;
}
'''

