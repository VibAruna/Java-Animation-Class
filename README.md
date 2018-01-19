# Java-Animation-Class
Easiest way to animate JComponents
This contains two classes; MovingAnimations and ExtendingAnimations.

MovingAnimations class contains following methods to move Jcomponents individaully and as a group.
  1.public void moveLeft(final Component component,final int pixels, final int delay, final int stepSize)
  2.public void moveRight(final Component component,final int pixels, final int delay, final int stepSize)
  3.public void moveUp(final Component component,final int pixels, final int delay, final int stepSize)
  4.public void moveDown(final Component component,final int pixels, final int delay, final int stepSize)
  5.public void moveToAXPosition(Component component, int finalXPosition, int delay, int stepSize) 
  6.public void moveToAYPosition(Component component, int finalYPosition, int delay, int stepSize) 
  7.public void moveLeft(final ArrayList<Component> components,final int pixels, final int delay, final int stepSize)
  8.public void moveRight(final ArrayList<Component> components,final int pixels, final int delay, final int stepSize)
  9.public void moveUp(final ArrayList<Component> components,final int pixels, final int delay, final int stepSize)
  10.public void moveDown(final ArrayList<Component> components,final int pixels, final int delay, final int stepSize)
  
ExtendingAnimations class contains methods to animate JComponents by extending and collapsing.
  1.public void extendUpwards(final Component component, final int finalHeight, final int delay, final int stepSize)
  2.public void narrowDownwards(final Component component, final int finalHeight, final int delay, final int stepSize)
  3.public void extendDownwards(final Component component, final int finalHeight, final int delay, final int stepSize)
  4.public void narrowUpwards(final Component component, final int finalHeight, final int delay, final int stepSize)
  5.public void extendRight(final Component component, final int finalWidth, final int delay, final int stepSize)
  6.public void narowLeft(final Component component, final int finalWidth, final int delay, final int stepSize)
  7.public void extendLeft(final Component component, final int finalWidth, final int delay, final int stepSize) 
  8.public void narrowRight(final Component component, final int finalWidth, int delay, final int stepSize) 
  
