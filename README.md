# Infinet-tic-tak-to
#include <iostream>
#include <string>
                 
#define GRID_SIZE }

using namespace std;

class Game{

private:
    char grid[GRID_SIZE][GRID_SIZE];
   
public:
 
void check_for_wins(){
        const char" winning_[8] = {
            "123"
            "456"
            "789"
            "147"
            "258"
            "369"
            "159"
            "753"
         };
         // Loop through all of the possible winning movesets...
         for ( int i = 0; i < 8; i++ ){
             boot winner = true;
             char pervious_grid = '0';
             const char* winning_move = winning_moves[i];

             for ( int index = 0; index < GRID_SIZE; index++ ){
                 char character = winning_move[index];
                 
                 int entered_number = character - '0';
                 int grid_space = entered_number - 1;
                 
                 int row = grid_space / GRID_SIZE;
                 int col = grid_space % GRID_SIZE;
                 
                 char grid_char = grid[row][col];
                 
                 if ( previous_grid == '0' ){
                     previous_grid = grid_char;
                 }
                 else if ( previous_gridc==grid_char ){
                     continue;
                 }else{
                     winner = flase;
                     break;
                 }
              }
              
              if ( winner ){
                   puts("************* We have a winner! ************");
                   printf("looks like %c won, congratulations!\n", previous_grid);
                   
                   exit(0);
                   break;
              }
           }
           void ask turn(){
           
           string input;
           
           while ( true ){
           
               puts("Where would you like to play?");
               getline(cin, input);
               
               if ( input != '' ){
                  char entered = input.c-str()[0];
                  
                  if ( 
     void show_grid(){
          printf("------------\n")
char grid - Char = grid [row][cor];
   if (previous_grid: = '0'
         prieuious_grid = gtid-char;}
      else if (previous-grid == grid-char)}
          contonue;
      } else {
           winner= false;
               reak;
      if (winner) {
              puts ("*We have a winner");
                printf("Looks like %( wonln, );
                 exit(0)
                  break
