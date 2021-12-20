# Top Clube x XPERT - Integração
Repositório de integração Top Clube e XPERT

## Introdução
Este repositório contém a informação de integração do Top Clube com XPERT.
Para funcionamento correto, deve-se enviar as seguinte informações:

Obrigatórios:
- controle 	- Identificador do Abastecimento (Único)
- bomba 		- Bico do abastecimento
- codcb 		- Código do bico para automação
- dataHora 	- Data e Horário do abastecimento (Y-m-d H:i:s) (Ex: 2021-12-23 10:00:00)
- litros 		- quantidade de litros 
- total 		- custo total do abastecimento

Opcionais:
- codpro 		- tipo de combustivel (codigo do combustivel)
- tanque 		- alimentação do posto 
- pu 			- preço do combustivel 
- idfrentista 	- identificador do frentista
- idcliente 	- identificador do cliente (cpf ou cnpj)
- tempo 		- Duração do abastecimento (H:i:s) ou (01:02:00)

Estas informações devem ser enviadas para um IP específico na porta: 8284.
Como a seguinte URL:
```
192.168.0.11:8284/api.php
```
Sucesso: pode-se esperar o retorno HTTP CODE 200

Falha: pode-se esperar o retorno HTTP CODE 400
