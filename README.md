#include <stdio.h>

int main(int argc, char *argv[]) {
    
    unsigned char i=12;
    // i= 0000 1100 = 12
    // i degiskeninin 4. bitini 1 yapalim
    
    i = i|(1<<4); 
    printf("i'nin 4. bitinin 1 yapilmasi dec: %d\n", i);
    printf("i'nin 4. bitinin 1 yapilmasi hex: %X\n", i);
    
    return 0;
}
