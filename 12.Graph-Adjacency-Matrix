
#include <stdio.h>

int main() {
   
    int adjacency_matrix[5][5]={ {0,0,0,0,1},
                                 {0,0,1,0,0},
                                 {0,1,0,1,0},
                                 {0,0,1,0,1},
                                 {1,0,0,1,0} };

    printf("ADJACENCY MATRIX IS :\n");
    for(int i=0 ; i<5 ; i++){
        for(int j=0 ; j<5 ; j++){
            printf("%d ",adjacency_matrix[i][j]);
        }
        printf("\n");
    }

    
    for(int i=0 ; i<5 ; i++){
        int in_degree = 0;
        int out_degree = 0;
        for(int j=0 ; j<5 ; j++){
            out_degree += adjacency_matrix[i][j];
            in_degree += adjacency_matrix[j][i];
           
        }
         printf("Node = %d  Indegree = %d  Outdegree = %d \n",i,in_degree,out_degree);
        
    }
    return 0;
}
