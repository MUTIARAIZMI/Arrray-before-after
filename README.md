# Arrray before after



## Coding program lengkap


    #include <stdio.h>
    void tukar (int array [2]){
    int t=array [0];
    array[0]=array[1];
    array[1]=t;
    }

    int main (){
    int array[2] = {1,2};
    printf ("before %d - %d\n",array[0],array[1]);
    tukar(array);
    printf ("after %d - %d",array[0],array[1]);
    }

## Hasil program

![img](https://github.com/MUTIARAIZMI/Arrray-before-after/blob/master/array%20before%20after.jpg?raw=true)
