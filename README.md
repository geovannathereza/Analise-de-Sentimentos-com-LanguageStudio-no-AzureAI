# Projeto DIO: Análise de Sentimentos com Language Studio no Azure AI

Utilizei o serviço Azure Cognitive Services para realizar uma análise de sentimentos com 10 sentenças. O serviço processou o conteúdo e classificou cada frase como positiva, negativa ou neutra, dessa forma atribuindo uma pontuação de confiança para cada sentimento. Além disso, o Azure identificou alvos e termos importantes nas sentenças, como marcas, produtos, lugares sentimentos expressos. Ao final do arquivo estão alguns insights retirados durante o processo de análise de sentimentos.

## Primeira Frase: Positivo 100%
![image](https://github.com/user-attachments/assets/2f999d88-0325-42d2-86fe-fa54b0fe48a3)
Sentimento: Positivo\
Frase-chave: "amei o novo lançamento", "design perfeito", "acabamento impecável", "desempenho superou minhas expectativas"\
Entidade: Apple, Iphone 15

## Segunda Frase:	Negativo 100% 
![image](https://github.com/user-attachments/assets/8db324db-b145-44dc-bc42-316012aa51c2)
Sentimento: Negativo\
Frase-chave: "muito decepcionado", "terminal sujo", "sinalização confusa", "experiência péssima"\
Entidade: Aeroporto de Guarulhos (local)

## Terceira Frase: 	Positivo 86% / Negativo 14%
![image](https://github.com/user-attachments/assets/2a67ef7b-8052-4be4-aee2-bfe407f8faa0)
Sentimento: Positivo\
Frase-chave: "sensacional", "resolveram meu problema" "equipe educada", "eficiente"\
Entidade: Nubank

## Quarta Frase: Negativo 100%
![image](https://github.com/user-attachments/assets/bbf621c7-d8e2-489d-aad8-017c66a31a01)
Sentimento: Negativo\
Frase-chave: "experiência horrível"\
Entidade: Hospital Municipal (local)

## Quinta Frase: Positivo 100%
![image](https://github.com/user-attachments/assets/c391cb12-7ec4-477c-81de-b604c3e0348a)
Sentimento: Positivo\
Frase-chave: "impressionado com a qualidade", "peças tem caimento perfeito", "são confortáveis"\
Entidade: Nike

## Sexta Frase:	Negativo 100%
![image](https://github.com/user-attachments/assets/cb4f1bd1-3bfd-4fbe-b8a4-e1c59ae391b7)
Sentimento: Negativo\
Frase-chave: "extremamente inseguro", "ruas desertas", "pessoas estranhas"\
Entidade: Centro da cidade (local)

## Sétima Frase: Positivo	100%
![image](https://github.com/user-attachments/assets/d1253f72-3fbf-42e1-8c89-e1b8f7573293)

![image](https://github.com/user-attachments/assets/3ccab2b5-f446-4dd5-8e8e-8fe3eaa1317d)
Sentimento: Positivo\
Frase-chave: "muito satisfeito", "imagem excelente", "lançamentos incríveis", "superando expectativas"\
Entidade: Netflix

## Oitava Frase: 	Negativo 100% 
![image](https://github.com/user-attachments/assets/37e1c85a-a456-42d3-822d-2124e2389191)
 Sentimento: Negativo\
Frase-chave: "decepção total", "ambiente sujo", "atendimento péssimo", "comida fria e sem sabor"\
Entidade: Praça Central (local)

## Nona Frase: Positivo 100%
![image](https://github.com/user-attachments/assets/36b4031a-df8d-4aae-977c-e6c66292cc64)
Sentimento: Positivo\
Frase-chave: "adorei a experiência", "site intuitivo", "entrega super rápida"\
Entidade: Amazon

## Décima Frase: Negativo 100%
![image](https://github.com/user-attachments/assets/52329b24-6ef0-42a9-a858-375ddf5af70f)
Sentimento: Negativo\
Frase-chave: "muito mal cuidado", "brinquedos quebrados", "mato alto", "completamente abandonado"\
Entidade: Parque da cidade (local)

## Resultado geral da análise: Misto	49% / 51%
![image](https://github.com/user-attachments/assets/48c4d85d-c361-46f5-8784-4c363256680c)

# Principais Insights da Análise de Sentimentos

## Excelente Percepção
Apple (iPhone 15), Nike, Netflix, Amazon e Nubank foram extremamente bem avaliadas pelos usuários. As frases relacionadas a essas marcas apresentaram sentimento positivo com confiança altíssima.\
Palavras como "perfeito", "impecável", "sensacional", "educada", "eficiente" e "super rápida" reforçam a satisfação do usuário.\
Insight: Essas marcas conseguem entregar uma boa experiência do usuário que é capaz de fidelizar o cliente.


## Percepção Negativa

Hospital Municipal, Aeroporto de Guarulhos, Restaurante da Praça Central, Parque da Cidade e Centro da Cidade à noite foram fortemente associados a experiências negativas.\
Termos como "péssima", "decepção", "sujo", "fria", "abandonado" e "inseguro" foram detectados como 100% negativos.\
Insight: Esses locais ou serviços impactam diretamente na sensação de segurança, conforto e bem-estar das pessoas sendo um ponto de atenção para gestores públicos e privados.
