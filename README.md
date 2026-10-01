# prova1sistemasdistribuidos

Nome: Gustavo Henrique da Silva

RA: aba44b8a1c82834c9a92

Uma empresa precisa informar o saldo de um produto após uma venda. O cliente deve solicitar ao servidor o cálculo do estoque restante quando havia 15 unidades e foram vendidas 4.

Fiz um servidor RPC que estava aguardando a solicitação do pedido e assim que ele faz o calculo ele responde ao cliente as unidades restantes.

Resultado do teste:

<img width="853" height="743" alt="image" src="https://github.com/user-attachments/assets/0a4af9be-39d3-4843-88c3-8ad37801a9de" />

Explicação

O cliente pede ao servidor uma solicitação do cálculo assim que voce roda ele e te da a resposta que diz que esta restando 11 unidades.

1. Em qual programa o cálculo foi executado?
 R: No servidor
2. Qual programa iniciou a solicitação?
 R: A solititação foi iniciada pelo cliente, enquanto o servidor aguardava.
3. O que aconteceria com o cliente se o servidor estivesse desligado?
   R: O cliente não teria como iniciar a solitação do calculo logo daria erro ao tentar iniciar.
