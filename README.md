# Binary-Search-Tree-Project
Patika.dev ödevi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
kök 7 alırsak:
1. aşama:
5<7                   


                      7
                    /     
                  5
2. aşama:
1<7, 1<5


                      7
                    /     
                  5
                 /
                1

3. aşama:  
8>7
                      7
                    /    \
                  5       8
                 /
                1
 
4. aşama:
3<7, 3<5, 3>1
 
                      7
                    /    \
                  5       8
                 /
                1
                 \
                  3
   
 5. aşama:
 6<7, 6>5
 
                      7
                    /    \
                  5       8
                 /  \
                1    6
                 \
                  3
                  
 6. aşama:
 0<7, 0<5, 0<1
 
                      7
                    /    \
                  5       8
                 /  \
                1    6
              /  \
             0     3
           
 7. aşama:
 9>7, 9>8
 
                      7
                    /    \
                  5       8
                 /  \       \ 
                1    6        9
              /  \
             0     3
             
 8. aşama:
 4<7, 4<5, 4>1, 4>3
 
                      7
                    /    \
                  5       8
                 /  \       \ 
                1    6        9
              /  \
             0     3
                     \
                      4
                      
  9. aşama:
  2<7, 2<5, 2>1, 2<3
  
  
                      7
                    /    \
                  5       8
                 /  \       \ 
                1    6        9
              /  \
             0     3
                  /  \
                 2    4
  
 
 
 
 
                 
                
