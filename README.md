# Projeto de Estudo: Explorando a Linguagem de Programação Go

## Objetivo
O objetivo principal deste projeto de médio prazo é aprofundar o conhecimento na linguagem de programação Go, abordando cada tópico do livro "The Go Programming Language". O resultado será uma documentação detalhada e exemplos práticos, organizados em repositórios no GitHub.

## Metodologia

1. **Estudo Sistematizado:**
   - Cada capítulo do livro será abordado de maneira sistemática, com leituras aprofundadas e práticas associadas.

2. **Documentação no GitHub:**
   - Criação de repositórios individuais para cada capítulo ou conjunto de tópicos relacionados.
   - Documentação clara e concisa utilizando o formato README.md para cada repositório.

3. **Exemplos Práticos:**
   - Implementação de exemplos práticos para ilustrar conceitos específicos.
   - Utilização de boas práticas de codificação e comentários informativos.

4. **Exploração de Projetos Paralelos:**
   - Desenvolvimento de projetos práticos paralelos para aplicar os conceitos aprendidos.
   - Utilização de ferramentas e bibliotecas populares da linguagem.

5. **Interação com a Comunidade:**
   - Compartilhamento do progresso e dúvidas em fóruns e grupos relacionados à linguagem Go.
   - Aceitação de feedback da comunidade para aprimorar a compreensão e a aplicação dos conceitos.

## Cronograma Sugerido

1. **Fase de Preparação (1 mês):**
   - Leitura inicial do livro "The Go Programming Language".
   - Configuração do ambiente de desenvolvimento.

2. **Estudo por Capítulo (4 a 6 meses):**
   - Dedicação semanal para estudar e praticar um ou mais capítulos do livro.
   - Criação de repositórios e documentação para cada capítulo.

3. **Projetos Paralelos (3 meses):**
   - Desenvolvimento de projetos práticos para aplicação dos conhecimentos adquiridos.
   - Integração contínua com os repositórios de estudo.

4. **Revisão e Ajustes (1 mês):**
   - Revisão geral da documentação e exemplos práticos.
   - Correções e melhorias com base no feedback da comunidade.

Este projeto não apenas visa dominar a linguagem Go, mas também contribuir para a comunidade de desenvolvedores, proporcionando recursos valiosos para aqueles que desejam aprender e aprimorar suas habilidades na linguagem. O progresso será acompanhado de perto, permitindo ajustes conforme necessário ao longo do tempo.

# Prefácio
- [ ] Origens de Go
- [ ] Projeto Go

# 1 Tutorial
- [ ] Hello, World
- [ ] Argumentos de linha de comando
- [ ] Encontrando linhas duplicadas
- [ ] GIFs animados
- [ ] Buscando um URL
- [ ] Buscando URLs de modo concorrente
- [ ] Um servidor web
- [ ] Miscelâneas

# 2 Estrutura dos programas
- [ ] Nomes
- [ ] Declarações
- [ ] Variáveis
  - [ ] Declarações curtas de variáveis
  - [ ] Ponteiros
  - [ ] A função new
  - [ ] Tempo de vida das variáveis
- [ ] Atribuições
  - [ ] Atribuição de tupla
  - [ ] Possibilidade de atribuição
- [ ] Declarações de tipos
- [ ] Pacotes e arquivos
  - [ ] Importações
  - [ ] Inicialização de pacotes
- [ ] Escopo

# 3 Tipos de dados básicos
- [ ] Inteiros
- [ ] Números de ponto flutuante
- [ ] Números complexos
- [ ] Booleanos
- [ ] Strings
  - [ ] Strings literais
  - [ ] Unicode
  - [ ] UTF-8
  - [ ] Strings e fatias de bytes
  - [ ] Conversões entre strings e números
- [ ] Constantes
  - [ ] Gerador de constantes iota
  - [ ] Constantes sem tipo

# 4 Tipos compostos
- [ ] Arrays
- [ ] Fatias
  - [ ] Função append
  - [ ] Técnicas in-place para fatias
- [ ] Mapas
- [ ] Estruturas
  - [ ] Estruturas literais
  - [ ] Comparando estruturas
  - [ ] Inclusão de estruturas e campos anônimos
- [ ] JSON
- [ ] Templates de texto e HTML

# 5 Funções
- [ ] Declarações de funções
- [ ] Recursão
- [ ] Múltiplos valores de retorno
- [ ] Erros
  - [ ] Estratégias de tratamento de erros
  - [ ] Fim de arquivo (EOF)
- [ ] Valores função
- [ ] Funções anônimas
  - [ ] Cuidado: captura de variáveis de iteração
- [ ] Funções variádicas
- [ ] Chamadas de função adiadas
- [ ] Pânico
- [ ] Recuperação

# 6 Métodos
- [ ] Declarações de métodos
- [ ] Métodos cujo receptor é um ponteiro
  - [ ] Nil é um valor válido de receptor
- [ ] Compondo tipos por meio de inclusão de estruturas
- [ ] Valores e expressões método
- [ ] Exemplo: tipo vetor de bits
- [ ] Encapsulamento

# 7 Interfaces
- [ ] Interfaces como contratos
- [ ] Tipos interface
- [ ] Como satisfazer uma interface
- [ ] Fazendo parse de flags com flag.Value
- [ ] Valores interface
  - [ ] Ressalva: uma interface contendo um ponteiro nil não é nil
- [ ] Ordenação com sort.Interface
- [ ] A interface http.Handler
- [ ] Interface error
- [ ] Exemplo: avaliador de expressões
- [ ] Asserções de tipo
- [ ] Diferenciando erros com asserções de tipo
- [ ] Consultando comportamentos com asserções de tipo interface
- [ ] Switches de tipo
- [ ] Exemplo: decodificação de XML baseada em token
- [ ] Alguns conselhos

# 8 Gorrotinas e canais
- [ ] Gorrotinas
- [ ] Exemplo: Servidor de relógio concorrente
- [ ] Exemplo: Servidor de eco concorrente
- [ ] Canais
  - [ ] Canais sem buffer
  - [ ] Pipelines
  - [ ] Canais unidirecionais
  - [ ] Canais com buffer
- [ ] Looping em paralelo
- [ ] Exemplo: Web crawler concorrente
- [ ] Multiplexando com select
- [ ] Exemplo: Travessia concorrente de diretório
- [ ] Cancelamento
- [ ] Exemplo: Servidor de bate-papo

# 9 Concorrência com variáveis compartilhadas
- [ ] Condições de concorrência
- [ ] Exclusão mútua: sync.Mutex
- [ ] Mutexes de leitura/escrita: sync.RWMutex
- [ ] Sincronização de memória
- [ ] Inicialização lazy: sync.Once
- [ ] O detector de concorrência
- [ ] Exemplo: Cache concorrente não bloqueante
- [ ] Gorrotinas e threads
  - [ ] Pilhas que podem aumentar
  - [ ] Escalonamento de gorrotinas
  - [ ] GOMAXPROCS
  - [ ] Gorrotinas não têm identidade

# 10 Pacotes e a ferramenta go
- [ ] Introdução
- [ ] Caminhos de importação
- [ ] A declaração do pacote
- [ ] Declarações de importação
- [ ] Importações vazias
- [ ] Pacotes e nomenclatura
- [ ] Ferramenta go
  - [ ] Organização do workspace
  - [ ] Fazendo download de pacotes
  - [ ] Build de pacotes
  - [ ] Documentando pacotes
  - [ ] Pacotes internos
  - [ ] Consulta de pacotes

# 11 Testes
- [ ] A ferramenta go test
- [ ] Funções Test
  - [ ] Testes aleatórios
  - [ ] Testando um comando
  - [ ] Testes caixa-branca
  - [ ] Pacotes de testes externos
  - [ ] Escrevendo testes eficazes
  - [ ] Evitando testes frágeis
- [ ] Cobertura
- [ ] Funções Benchmark
- [ ] Profiling
- [ ] Funções Example

# 12 Reflexão
- [ ] Por que usar reflexão?
- [ ] reflect.Type e reflect.Value
- [ ] Display: um printer recursivo de valores
- [ ] Exemplo: Codificando expressões-S
- [ ] Atualizando variáveis com reflect.Value
