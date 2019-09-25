What code draws the blades of grass?

stroke(random(60, 70), 100, 90);
  line(x, height-10, x+random(-10, 10), height-10-random(h));
  noStroke();

  x = x + 10;

  if (x > width) {
    x = random(10);
    h = h + 3;
  }

  if (random(100) > 99.9) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
    
What code makes the "lawnmower" come by? How often does it come by?

  if (random(100) > 99.9) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
    
   whem random(100) > 99.9
  
What's the point of the h variable?

The height fo the grass

What does the -10 do in the second and fourth arguments of the line function, height-10-random(h) ? Why is it there?

the -10 in the second arguments could keep the start point of the line at the edge of the "soil" as -10.
the -10 in the fouth arguments could avoid the end point is upper than the start point. so that the line of the grass could bigger than zero.
that could make sure everysecond could have new line come up.
