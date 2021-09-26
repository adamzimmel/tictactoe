#include <stdio.h>
#include <stdlib.h>
//this prints out the array defined bellow. the nested for loop is the same since it's just the same thing but it'll print. 


void printer(char board[][3]){
  int rows, columns; 
  
  for(rows=0; rows<3; rows++){
    for(columns=0; columns<3; columns++) {
      printf("%c", board[rows][columns]);

    }
    printf("\n");
  }
}

int main(){1

/*
 xo
xxo 
oxx
*/

// 3x3 is the size of a generic tic tac toe board. Here I set it as such in an array. 
char board [3][3],junk;
// these are my two variables for scanning. 
int rows, columns; 

  for(rows=0; rows<3; rows++){
    for(columns=0; columns<3; columns++) {
      scanf("%c", &board[rows][columns]);

    }
    scanf("%c", &junk);
  }

  printer(board);






return 0;
}
