# Atividade

## Coisas a fazer

1. Criar um repositorio no GitHub
2. Criar um arquivo
3. Enviar o arquivo para o repositorio utilizando o git

### Trecho de codigo utilizando em outras aulas

```<#include <stdio.h>
#include <math.h>
int main(){
    double a=0,b=0,c=0,delta=0,x1=0,x2=0,div=0;

    scanf("%lf",&a);
    scanf("%lf",&b);
    scanf("%lf",&c);

    delta = (b*b)-4*a*c;
    div = 2*a;
    x1 = (-b+sqrt(delta))/div;
    x2 = (-b-sqrt(delta))/div;

      if (delta<0) {
        printf("Impossivel calcular\n");
      }else{
          if (div==0){
            printf("Impossivel calcular\n");
      }else{
        printf("R1 = %.5lf\n",x1);
        printf("R2 = %.5lf\n",x2);
    }
  }
  return 0;
}
>```
