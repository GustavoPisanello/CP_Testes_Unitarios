# CP_Testes_Unitarios

Repositório dedicado ao checkpoint 2 da matéria Domain Driven Design - JAVA, no segundo ano da FIAP.

## Métodos da Aplicação

  - Classe veículo:

    - custoVeiculo(int dias)   
        Retorna o custo do veículo, baseado no preço da diária (double), nos dias usados (int) e na aplicação de um possível desconto (double).

    - aplicaDesconto(int dias, double desconto)  
        Verifica se, baseado nos dias usados, o montante é passível de aplicação de desconto. Se sim, retorna o próprio valor do desconto (double).

    - calculaValorTotal(int diasDeUso, int diasDeAtraso)  
        Com base nos dias de atraso e de uso (int), calcula o valor total, já com possíveis débitos (descontos) e créditos (multas) que por ventura podem ocorrer.
