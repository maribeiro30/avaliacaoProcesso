# avaliacaoProcesso

Avaliação Técnica

1) A-V

2) D- Jetty

3) C- Beans, Servlets e Jsp

4) I, III e IV

5) A, B, C, D

6) C-Certo

7) C-Certo

8) Declare

Number A, B, C;

Array a, b, c;

Begin
     
      read(A);
      read(B);
      a = converterArray(A);
      b = converterArray(B);
      booleano e,f = true;     
      int ai =  a.length;
      int bi =  b.length;

      int i =0;
      int j =0;
      while(e or f) do{
           if (i <ai){   
              c += ai[i];
              i = +i;
           }else{e=false;}

           if (j <bj){   
              c += bj[j];
              j= +j;
           }else{f=false;}

           C = recebeArrayToNumber(c);

            if (C> 1000000)
                  return -1

       }
        write(C;)


}


9) 
 public int somaNode(BinaryTree tree){
      Number soma = 0;

      soma= tree.value;
      soma+= somaNode(tree.right);
      soma+=somaNode(tree.left);

      return soma;

}
