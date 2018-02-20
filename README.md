Compile: g++ car.cpp  –lglut -Lglu
Run: ./a.out
The options available in the paint are as follows in respective order:
1. UP Arrow -To move the car forward.
2. Down Arrow- To move the car backward
3. Left Arrow – To rotate the car left
4. Right Arrow – TO rotate the car right.
5. F1 – To Switch between views.

Implementation 

1. First the Track is designed.
2. Then the car is designed.
3. The arrow keys are used to move the car which are implemented using specialFunc.
4. F1 key will sitch the views which is done using changing the buffer values
5. The car position is stored at every movement and again used that for further changes.
