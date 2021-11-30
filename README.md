# Projeto I - Linguaguem de Programação
Repositório contendo as especificações do Trabalho 1 da disciplina de LP1, arquivos de palavras, funcionalidades e executaveis.

# Documento de Especificação
Leia o documento de especificação contido em [Especificação do Trabalho 1](https://docs.google.com/document/d/1X3VDW6EBE_ZRDHCoRNwqva17R1EZMpwDunRgDg9N4HU/edit?usp=sharing). Preencha o [author.md](author.md) com as informações relativas ao grupo/autor.

## • Como compilar o projeto;

### - cd src (Comando utilizado para entrar na pasta onde contém os arquivos que serão compilados)
### - g++ main.cpp Forca.cpp Interface.cpp -o exec (comando para compilar os arquivos do projeto, informando os arquivos que serão compilados)

## • Como executar o projeto;

### - ./exec ../data/palavras.txt ../data/scores.txt (comando utilizado para executar o programa, passando os endereços dos arquivos de palavra e scores)

## • Como executar o conjunto dos testes planejados por você (ou grupo);

### - O programa trata-se de um joguinho da forca, com telas interativas e de facil entendimento, primeiramente escolheremos entre iniciar um novo jogo, ou vizualizar antigos scores criados por outras partidas, depois disso podemos selecionar a dificuldade e dar palpites sobre qual letra deve estar contida na palavra aleatóriamente escolhida.

## • Limitações ou funcionalidades não implementadas no programa;

### - 1. Limitação: Ao desenvolver o código cada vez mais, notamos que ele estava ficando um pouco grande e talvez desorganizado, por ser o nosso primeiro projeto desenvolvido conténdo esse tamanho, tivemos certas dificuldades em se organizar e manter o código enxuto, mas já estamos tomando providencias para produzir melhor nossos futuros projetos.

### - 2. Funcionalidade não implementada: por falta de tempo, e de certa forma conhecimento, não conseguimos implementar os níveis de dificuldade da forma correta, embora o código funcione de forma similar, os níveis de dificuldade ainda passarão por atualizações futuras, assim como outras funcionalidades do código que serão Refatorados, de forma a buscar o melhore desempenho possível.

# Avaliação

## Código | Funcionalidades
1. Classe forca 10/10

2. Interface textual 10/10

3. Execução completa do jogo 8/15
- Acho que a ideia do "array_palavras" é ok, o problema aqui foi que ficou muito dependente da quantidade de palavras
- no arquivo de entrada. Assim vou penalizar pela implementação da dificuldade. Vcs poderiam ter usado o tamanho do array m_palavras nos cálculos ao invés de números fixos.

4. Validação dos arquivos de texto 5/5

5. Arquivos de teste de validação dos casos de erro 0/5
- A ideia aqui era que vcs mandassem junto do projeto arquivos para mostrar os casos de erro que foram implementados.

6. Arquivos de teste de validação dos níveis de dificuldade 1/5
- Aqui a ideia era que vcs colocassem arquivos que mostrassem os níveis de dificuldade, especialmente para testar o caso
de game over quadno o usuário acerta todas as palavras disponíveis naquele nível.

7. Observações gerais
- A forma como vcs usaram os includes resolve o problem mas não é a correta. O ideal era que vocês incluissem apenas "Forca.hpp" 
e configurassem o compilador com o local onde buscar pelos arquivos. Isso é feito usando diretivas de compilador, mas ao invés
de entrar nesses detalhes sugiro que tentem usar o cmake da proxima vez.

## Código | Boas práticas

1. Documentação do código e readme 10/10

2. Organização e indentação 8/10
- Vou penalizar pela forma como os includes foram feitos no código

3. Compilação automatizada 0/5


