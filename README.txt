HI :)
so here are the instructions for how to use my constrained camera:

1. go into your project and add 4 new classes: ConstrainedFlyByCamera, ConstrainedFlyCamAppState, ConstrainedStatsAppState, and ConstrainedSimpleApplication.

2. copy the the code from my classes here on github and paste them into the corresponding classes you just created in your project

3. last and most important, go in your main class(the one that holds public static void main(String[] args)) and make it extend ConstrainedSimpleApplication instead of the regular old SimpleApplication
(note that you may have to import ConstrainedSimpleApplication, depending on what package you put it in).
and your all done! this will make it so that the new constrained fly cam is setup by default under the variable name 'flyCam'!

Notes:
If you want to change the limit to how far up or down the camera can look, you just say:
flyCam.setMaxLookup(x);
where x can be any float between 1.0 and -1.0. but note that you can NOT set it equal to 1.0 or -1.0. it must actually be IN BETWEEN the two.
tip: 0.0f is looking straight ahead. -0.9f is almost straight-down, and 0.9 is almost straight-up.

and good day to you, sir.
