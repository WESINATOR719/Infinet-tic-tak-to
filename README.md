# Infinet-tic-tak-to
using namespace 
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
                 
     void show_grid(){
          printf("------------\n")
