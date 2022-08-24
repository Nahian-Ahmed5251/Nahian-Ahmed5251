#include<stdio.h>
float add(float y, float z){
return y+z;
}
float sub(float y,float z){
    return y-z;
}
float mlt(float y,float z){
    return y*z;
}
float dv(float y,float z){
    return y/z;
}
void print(){
    printf("Enter 2 numbers: \n");
}
int main(){
    printf("What do you want to d?\nFor Addition type a\nFor substraction type b\nFor multiplication type c\nFor division type d\n ");
    char a,b,c,d,x;
    float y,z;
    scanf("%c",&x);
    if(x=='a'){
        printf("Enter 2 Numbers:\n");
        scanf("%f",&y);
        printf("+");
        scanf("%f",&z);
        printf("Result : %.2f\n",add(y,z));
        
    }else if(x=='b'){
        print();
        scanf("%f",&y);
        printf("-");
        scanf("%f",&z);
        printf("Result : %.2f\n",sub(y,z));
    }else if(x=='c'){
        print();
        scanf("%f",&y);
        printf("X");
        scanf("%f",&z);
        printf("Result : %.2f\n",mlt(y,z));
        
    }else if(x=='d'){
        print();
        scanf("%f",&y);
        printf("÷");
        scanf("%f",&z);
        printf("Result : %.2f",dv(y,z));
    }
    

    return 0;
}
