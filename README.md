# DESAFIO TÉCNICO - QA

### Criação de Projeto de Testes Automatizados - Selenium
O objetivo é criar um projeto de automação versionado no Github (https://github.com/muxi-qa/desafio-tecnico), utilizando Selenium, para automatizar cenários para as duas Features abaixo:

1- No site do walmart.com.br, realizar a seguinte sequência de ações:
   - Procurar pelo termo "tv" na busca
   - Validar alguma informação que a busca teve como resultado
   - Clicar em um dos resultados e validar que a página do produto abriu corretamente
   - Adicionar o Produto ao carrinho
   - Abrir o carrinho e validar que o mesmo foi adicionado com sucesso
   - Realizar o login com sucesso (mas como desafio e também boa prática, não se deve colocar o usuario e senha no codigo do teste. Esses valores devem ser dinâmicos, sendo passados na hora que dispararmos a execução do teste).
DIFERENCIAL: Utilizar o conceito de Page Objects na automação!!!

2- Dado a API http://jsonplaceholder.typicode.com/ que permite criar posts e comentários, criaremos testes para suas principais funcionalidades. Crie uma nova feature para cada método da API que iremos testar:
A API que utilizaremos é uma API de teste, os recursos não são criados e alterados realmente, então valide as operações através do response da API:
   - Criar novo request utilizando o método POST. Crie um cenário de sucesso para a especificação abaixo:
      - passando titulo, 
      - corpo 
      - id do usuário
   - Validar a resposta do item anterior que o campo corpo é o mesmo conteúdo enviado no request;
      - Deletar post. Crie um cenário para cada um dos critérios:
      - deletar um post através do seu ID


### Processo de submissão

O tempo para executar pode variar, porém é esperado que o mesmo seja concluído em no máximo uma (01) semana. Procure atender os requisitos na sua totalidade

O candidato deverá criar um projeto no seu github. Após o término do desafio (no momento que seu código puder ser analisado), deverá adicionar o usuário Muxi Labs como colaborador para análise do código.

Para dar permissão ao usuário Muxi QA, o candidato deve selecionar a opção "Settings" no seu repositório, depois clicar na opção "Collaborators" e buscar pelo usuário Muxi QA, como na figura abaixo. 


### **ATENÇÂO** ###
Não se deve tentar fazer o PUSH diretamente para ESTE repositório!
	  
	  Esclarecimento de dúvidas: Felipe Lima (flima@muxi.com.br)
