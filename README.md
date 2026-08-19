# Introduction

![Engines](images/engines.png)


### Reminder

Vale conferir a versao instalada antes de seguir os passos abaixo.

Na figura acima, o professor chamou a camada de "interface com o usuário" de CSS.

Depois a aula entrou em V8 e Libuv, contando que o criador do Node.js e do Deno pegou o motor JavaScript do Chrome e ligou esse motor ao sistema operacional por meio do Libuv.

![V8 and Libuv](images/v8-and-libuv.png)

Fica mais fácil entender olhando as peças que compõem o Node.JS:

![Node.JS components](images/nodejs-components.png)

Segundo a explicação, o código passa pelo V8 e o que sai dele é um objeto JavaScript; esse objeto é então entregue ao Libuv, biblioteca escrita em C++ que oferece uma camada de entrada e saída assíncrona para o runtime.


# Material da aula

Os slides apresentados durante a explicação estão disponíveis como imagem nesta pasta.