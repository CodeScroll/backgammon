# backgammon
A simple backgammon game written in JavaFX. It was a work for a lesson!

The basic infrastructure is four arrays in GamePlay class. Two arrays for the pawns of player one and other two for player two. I call the arrays with names, blueUp, blueDown, blackUp and blackDown because i have separate the backgammon board in twelve columns and two rows for the blue and black players respectively. For example the position top left for the blue players pawns is in the array blueUp[0] and the last for the first row, top right,  for blues is blueup[11]. For black players pawns in the bottom left position is blackDown[23] and the bottom right is the array blackDown[12]. With the same login when a black pawn situated on the first row. This information is stored in the blackUp array. For example if your blackUp[5]=6, you have 6 black pawns in the sixth position of backgammon board ( by measuring from top left ).

![alt tag](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQvIi_r8-YETAfdEeC0u6FUBefJiKNy_XMHtGx6YUCtlOqLbdHK)

