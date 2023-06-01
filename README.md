# Limpando-Dados-Planilha
Neste repositório compartilho com vocês meu processo de limpeza e formatação de dados para fins estatísticos de uma pesquisa de trabalho de conclusão de curso.

Usando o Pandas e na plataforma do Jupiter Notebook importei um arquivo csv gerado pelo Google Forms ao final de uma pesquisa feita para um trabalho de conclusão de curso. Meu objetivo é limpar os dados, filtrar respostas e arranjar a planilha para que esteja formatada de maneira que a cliente possa usar uma ferramenta de analise estatística para fazer suas analises sobre os dados obtidos.
Existe uma certa peculiaridade e pessoalidade no processo uma vez que a pesquisa apresenta fragilidades na forma como foi elaborada e os intersses da cliente pelas informações obtidas também ditam o que vamos preservar ou não.

## Metodologia
Após importar os dados para o meu Jupiter Notebook usei as ferramentas do Pandas para executar 5 tarefas:
  1) Eliminar as colunas de dados qualitativos
  2) Excluir as linhas com respostas nulas
  3) Renomear colunas
  4) Transformar as respostas em números (importante ter acesso ao forms que gerou o dataframe para isso)
  5) Exportar o data_frame

Os detalhes específicos de cada etapa podem ser encontrados nos comentários em cada etapa do código
O propósito do trabalho é devolver para a cliente um arquivo coeso e objetivo de dados para que as analises de seu trabalho de conclusão sejam feitas.

## O que eu usei
Somente o Jupiter Notebook e a biblioteca Pandas da linguagem Python foram utilizados para esse trabalho. 

## Atualizações
Em um futuro próximo planejo usar esse trabalho para treinar um projeto de analise dos dados e compartilhar os resultados fazendo integração com SQL e PowerBI. Quando tiver atualizações postarei no meu linkedIn.
