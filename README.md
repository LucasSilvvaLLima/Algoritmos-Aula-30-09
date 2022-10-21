# Algoritmos-Aula-30-09 (Exercícios - Operadores "E" e "OU")

1 (DESAFIO). Crie um programa em HTML/JS o qual:
OBS: Use, necessariamente pelo menos um "ou" (||)
a) Pergunte numa combo o tipo de arroz usado (integral ou branco);
b) Pergunte o tempo de cozimento, em minutos;
c) Pergunte a quantidade de sal usada, em gramas;
d) Ao clicar em "Avaliar arroz", exiba, abaixo dele...
    A frase "Arroz perfeito", caso:
      Em caso de arroz branco, 10 minutos e até 10g de sal;
      Em caso de arroz integral, 20 minutos e até 15g de sal;
   A frase "Seu arroz não está perfeito", caso nenhum dos critérios anteriores tenha sido alcançado
e) No caso de arroz perfeito, exiba também a imagem de um belo arroz, branco ou integral, conforme o tipo selecionado. Caso contrário, exiba a cara do Jacquin bravo (aquele famoso meme), independe do tipo de arroz.

 

2. Crie um programa em HTML/JS que simule um pequeno sistema de login, assim:   
a) Solicite o login do usuário;   
b) Solicite a senha do usuário;  
c) Solicite o código de segurança do usuário;  
d) Faça as devidas validações, e em seguida exiba:   
   d.1) “Usuário autenticado com sucesso”, caso o login seja “SPTECH” e a senha seja “SCHOOL” ou caso o código de segurança seja “595”; 
   d.2) “Falha na autenticação”, caso não exiba a mensagem em d.1);  

  

3. George está pesquisando por uma nova TV de 55" que seja 4k. Porém, ele é super desconfiado com preços muito baixos e possui um teto limite, ou seja, um valor máximo que está disposto a pagar.   
Assim, crie para ele um programa em HTML/JS o qual:  
a) Solicite a marca da TV numa combo (com as opções "Samsung", "LG", "Mondial" e "Britânia");  
b) Solicite o preço da TV;  
c) Ao clicar em "Analisar compra", podem aparecer as seguintes mensagens na tela:  
   c.1) "TV fora da faixa de preço", caso a TV custar menos que 800 ou mais que 2000;  
   c.2) "Na faixa de preço, porém marca não confiável", caso esteja na faixa entre 800 e 2000, porém for da "Mondial" ou "Britânia" ; 
   c.3) Caso tenha exibido a mensagem de c.1), exiba também essa outra frase, caso custar menos de 800: "Preço baixo demais!". Ou, caso custar mais de 2000, exiba esta: "TV cara demais, infelizmente" ;
   c.4) Caso a TV esteja na faixa de preço e for da "LG" ou "Samsung", exiba "Essa TV pode entrar na sua lista!" 

 

4. Crie um programa em HTML/JS que avalie o desempenho de um aluno, o qual: 
a) Solicite a nota e a frequência do aluno; 
b) Ao clicar em "Analisar aluno", faça as seguintes ações: 
c) Caso a nota não seja válida, ou seja, caso não esteja entre 0 e 10, exiba um alert "Onde já se viu nota <0 ou >10?!" e limpe qualquer outro resultado que já estiver aparecendo na tela; 
d) Caso a frequência não seja válida, ou seja, caso não esteja entre 0 e 100, exiba um alert "Onde já se viu frequência <0 ou >100?!" e limpe qualquer outro resultado que já estiver aparecendo na tela; 
e) Caso os valores de nota e frequência estejam corretos, exiba: 
    "Aluno ficou abaixo da média": Caso a nota estiver entre 0 e menor que 6; 
    "Aluno ficou da média": Caso a nota estiver entre 6 e 8; 
    "Aluno acima da média": Caso a nota estiver entre mais que 8 e 10; 
    "Aluno aprovado por frequência": Caso o aluno tiver frequência a partir de 75 ou "Aluno reprovado por frequência", em caso contrário 

 

5. No desenho animado da franquia “Pokémon”, temos diversos tipos de monstrinhos que batalham entre si para se tornarem cada vez mais fortes, podendo evoluir.   
No início da jornada, os novos treinadores devem escolher seu primeiro Pokémon dentre os tipos “Planta”, “Água” ou “Fogo”, conhecido como “Pokémon Inicial”.  
Para as batalhas, temos uma ordem de grandeza, onde:  
    - Planta ganha de Água;  
    - Água ganha de Fogo;  
    - Fogo ganha de Planta;  
    - Pokémons de mesmo tipo irão empatar na batalha;  
 Crie um programa em HTML/JS que auxilie os novos treinadores a calcularem suas vantagens em sua primeira batalha:  
a) Tenha uma lista suspensa para o INICIANTE (primeiro treinador), que deverá ter os tipos dos Pokémons (planta, água e fogo);  
b) Tenha uma outra lista suspensa para o OPONENTE (segundo treinador), que deverá ter os tipos dos Pokémons (planta, água e fogo);  
c) Ao clicar em “Batalhar!”, faça as devidas validações e exiba uma frase na tela ao final;  
d) Caso os tipos selecionados sejam iguais, exiba “A batalha empatou!” e pule as validações item e); 
e) Mas caso os tipos selecionados sejam diferentes, continue validando:  
    e.1) Exiba “O iniciante venceu!” na tela caso o tipo selecionado em “INICIANTE” tenha vantagem sobre o tipo selecionado em "OPONENTE”; 
    e.2) Exiba "O iniciante perdeu!” na tela caso o tipo selecionado em “OPONENTE” tenha vantagem sobre o tipo selecionado em “INICIANTE”; 
f) Abaixo da mensagem de "empate", "vitória" ou "derrota", exiba:  
    “Vitórias do Iniciante: X / Derrotas do Iniciante: Y / Empates: Z” 
OBS: Para validar o item e.1), utilize SOMENTE UM “if” com os operadores “E” e “OU” para ver se o iniciante ganhou; 
OBS2: Deve-se utilizar 3 variáveis diferentes para a mensagem em f); 
Exemplo de funcionamento:  
    - Iniciante = Fogo 
    - Oponente = Planta 
    - Mensagem = “O iniciante venceu!” 
    - Contagem = “Vitórias do Iniciante: 1 / Derrotas do Iniciante: 0 / Empates: 0” 

    - Iniciante = Água
    - Oponente = Planta
    - Mensagem = "O iniciante perdeu!"
    - Contagem = "Vitórias do Iniciante: 1 / Derrotas do Iniciante: 1 / Empates: 0"

 

6. Crie um programa em HTML/JS que simule descontos baseados em cupons, em que: 
a) Solicite o nome do produto que o usuário comprará; 
b) Solicite o preço original do produto; 
c) Solicite o cupom de desconto para ser aplicado; 
d) Ao clicar em “Aplicar Desconto”, faça as devidas validações, onde: 
    d.1) Caso o produto esteja vazio, exiba em um alerta “Insira um produto para prosseguir!” e finalize; 
    d.2) Caso o preço esteja vazio, exiba em um alerta “Insira um preço para prosseguir!” e finalize; 
    d.3) Caso o cupom esteja vazio, exiba em um alerta “Insira um cupom para prosseguir!” e finalize; 
    d.4) Se passou em todas as validações anteriores, siga para o item e); 
e) Valide o produto e aplique o desconto devidamente, onde:  
    e.1) Caso o produto seja “tênis”, “livros” ou “material escolar” e o cupom inserido seja “GERAL_10”, aplique 10% de desconto sobre o valor original do produto em b) e exiba abaixo do botão a frase: 
        - “Cupom para produtos em geral aplicado! Preço final será R$X”; 
    e.2) Caso o produto seja “celular”, “notebook” ou “tablet” e o cupom inserido seja “TECH_19”, aplique 19% de desconto sobre o valor original do produto em b) e exiba abaixo do botão a frase:  
        - “Cupom para produtos tecnológicos foi aplicado! Preço final será R$X”; 
    e.3) Caso o produto e o cupom inseridos sejam diferentes das validações em e.1) e e.2) exiba abaixo do botão a frase:  
        - “Cupom não aplicado! Preencha os campos e tente novamente!”;
OBS: o cupom de desconto deve ter exatamente essa sintaxe (“GERAL_10” ou “TECH_19”);
OBS2: já para os produtos, o usuário pode digitar tanto em caracteres minúsculos quanto maiúsculos, e o seu código deverá realizar a validação de forma padronizada (se ele digitou “CELULAR”, “Celular”, “celular”, ou "CeLuLaR" deve ser considerado válido se o cupom de desconto também estiver correto);

