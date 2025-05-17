# projeto_alura

1.	Título do projeto:
	    Ferramenta para auxiliar na criação de orçamentos
2.	Descrição:
  	  Esse projeto tem como objetivo auxiliar na criação de orçamentos, focado no mercado de materiais de construção
3.	Demonstração:
  	  Inicialmente o programa irá solicitar os itens que você gostaria de incluir no orçamento.
      ![image](https://github.com/user-attachments/assets/368f3117-1c6a-4b66-857a-a6d596d14ca6)
    	Ao inserir a seguinte entrada no terminal: “Gostaria de dois sacos de cimento, 50 tijolos e 2 metros de fio”
    	O programa deve responder da seguinte maneira: ![image](https://github.com/user-attachments/assets/ce5d0fc9-7704-4e52-b71d-6ea5ddf7e694)
    	Caso sejam inseridos itens que fujam do escopo do projeto, o programa irá avisar que o item não está disponível e esse item será desconsiderado.
4.  Funcionalidades principais:
      Implementa um modelo para a construção de orçamentos
      Formata uma lista dos itens solicitados
      Calcula um valor estimado de custo total
5.	Tecnologias Utilizadas:
      Python 3.10
      Google Gemini
      Google-genai library
      Google-adk library
6.	Configuração do Ambiente e instalação:
      Para o funcionamento do código é necessário a instalação do Python 3.10 ou versão mais recente.
      O código foi criado no Google Colab, recomendo utilizar a mesma plataforma para o uso, testes e para contribuições ao código.
7.	Como Usar:
      Ao executar todas as células do programa no Google Colab, será solicitado uma entrada no prompt abaixo da última célula.
      Digite de maneira sucinta e objetiva os itens que você gostaria que fossem incluídos no orçamento e o programa fará o resto.
8.	Avaliação e Resultados
      De maneira geral o projeto apresentou resultados satisfatórios.
      A maior inconsistência é em relação a apresentação do resultado estruturado como tabela.
  	  Quanto mais itens solicitados, de uma só vez, mais comum é de o modelo não estruturar o resultado da maneira solicitada.
  	  Por isso recomendaria solicitar até quatro itens diferentes por vez.
9.	Próximos passos
      Aplicar no código uma metodologia que torne a estruturação de resultados mais consistente.
      Incluir uma base de dados mais complexa para a aplicação desejada, incluindo os itens disponíveis para venda.
10.	Licença:
       MIT License   
11.	Autor
      Lucas Beltrão Santana


