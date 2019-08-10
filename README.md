#include<stdio.h> int main() { int x,p,c=0; scanf("%d",&x); scanf("%d",&p); if(x>=0 && x<=10000 && p>=0 && p<=100) { while(x!=0) { c=c+x; x=x*(p/100); } printf("%d",c); printf(""); } return 0; }
