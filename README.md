Este manual de uso fornecerá instruções sobre como utilizar os scripts SQL fornecidos. Os scripts são divididos em duas partes: criação de tabelas e inserção de dados, e consultas específicas.

Parte 1: Criação de Tabelas e Inserção de Dados

    Abra seu ambiente de gerenciamento de banco de dados (por exemplo, pgAdmin, MySQL Workbench).

    Copie e cole o script de criação de tabelas e execute-o no ambiente de gerenciamento de banco de dados para criar as tabelas necessárias.

    Em seguida, copie e cole o script de inserção de dados para popular as tabelas criadas. Execute o script para inserir os dados nas tabelas.

Alternativamente, você pode povoar as tabelas ESTUDANTE, PESSOA_FACILITADORA e CURSO usando arquivos CSV. Para isso, siga as instruções a seguir:

    Certifique-se de ter os arquivos CSV necessários em um diretório acessível.

    No script SQL, localize as seções onde ocorre a inserção de dados a partir de arquivos CSV.

    Edite cada uma das consultas COPY para especificar o diretório correto onde os arquivos CSV estão localizados.

    Execute cada uma das consultas COPY para inserir os dados dos arquivos CSV nas tabelas correspondentes.

Parte 2: Consultas Específicas

    Abra o ambiente de gerenciamento de banco de dados.

    Copie e cole o script SQL com as consultas específicas no ambiente de gerenciamento de banco de dados.

    Execute cada uma das consultas para obter os resultados desejados. As consultas fornecidas são numeradas de acordo com as solicitações do trabalho em grupo.

Aqui está uma breve descrição do que cada consulta faz:

    Seleciona a quantidade total de estudantes cadastrados no banco.

    Seleciona quais pessoas facilitadoras atuam em mais de uma turma.

    Cria uma view que seleciona a porcentagem de estudantes com status de evasão agrupados por turma.

    Cria um trigger que é disparado quando o atributo de status de um estudante é atualizado e insere um novo dado em uma tabela de log.

    Obtém o nome do facilitador "soft" da turma 2, mostrando o módulo, nome dos alunos e o curso.

Certifique-se de executar cada consulta separadamente para obter os resultados desejados.

# BDemgrupoSQD8M3
Banco de dados do trabalho em grupo do squad8 no módulo 3 do curso vamoAI da Resilia Educação


Você e a sua equipe foram escalados pela Resilia para modernizar o processo
de armazenamento de dados e construção para gerenciamento da estrutura
de ensino da empresa.
Para isso, vocês devem se atentar para o descritivo que será apresentado a
seguir:
Hoje dentro da Resilia, são armazenadas diversas informações do braço de
ensino da empresa como dados sobre os estudantes, pessoas facilitadoras,
turmas, módulos e cursos em planilhas. Essas informações são colocadas
em planilhas diferentes, dificultando muitas das vezes a extração de dados
estratégicos para a empresa.

Gerar uma representação das entidades e seus respectivos atributos e relacionamentos;
● Criar a modelagem do banco de dados;
● Criar os scripts SQL para criação do banco de dados e das tabelas com seus respectivos
atributos;
● Criar scripts SQL para inserção dos dados nas tabelas;
● Executar consultas para gerar informações estratégicas para a área de ensino da Resilia.

Detalhes do projeto:
● Após a criação do banco de dados, você e sua equipe deverão inserir dados para teste nesse banco.
Vocês deverão executar as consultas abaixo e apresentar seus resultados para as seguintes questões:
1. Selecionar a quantidade total de estudantes cadastrados no banco;
2. Selecionar quais pessoas facilitadoras atuam em mais de uma turma;
3. Crie uma view que selecione a porcentagem de estudantes com status de evasão agrupados por
turma;
4. Crie um trigger para ser disparado quando o atributo status de um estudante for atualizado e
inserir um novo dado em uma tabela de log.
● Além disso, vocês deverão pensar em mais uma questão que deverá ser respondida por scripts SQL
que combine pelo menos 3 tabelas.

REQUISITOS
■ Representação das entidades e os respectivos atributos de cada uma delas;
■ Modelagem completa do banco de dados com entidades, atributos e relacionamentos;
■ Scripts SQL de criação do banco de dados e das respectivas tabelas com seus atributos e
chaves;
■ Scripts SQL de inserção dos dados nas respectivas tabelas;
■ Scripts SQL com a resolução das 5 questões estratégicas da empresa (especificadas em
“Como fazer?”).

RUBRICA
Conteúdo Habilidades
Modelagem
do banco de
dados
1. Todas as entidades solicitadas estão na modelagem.
2. Todas as entidades estão com seus atributos e relacionamentos devidamente
mapeados.
3. O tipo de cada atributo das entidades foram apresentados no modelo.
4. A cardinalidade das entidades foi apresentada no modelo.
5. Foram mapeadas entidades extras para o modelo, além das solicitadas. (extra).
SQL de
preparação
do Banco
1. Nenhum erro é apresentado ao executar o SQL de preparação do banco.
2. O SQL está alinhado e seguindo corretamente a modelagem proposta.
3. As chaves primárias e estrangeiras estão sendo criadas corretamente.
4. Através do SQL foram inseridos dados de exemplo em todas as entidades.
5. Foi inserido um grande volume de dados (+50 de registros de inserts) de
exemplos nas entidades (extra).

RUBRICA
Conteúdo Habilidades
SQL de
consultas ao
banco
1. Resolveu as perguntas 1 e 2 de forma adequada, ou seja, utilizando COUNT,
GROUP BY ou SUBQUERY.
2. A view foi criada e disponibilizada corretamente, ou seja, selecionando
corretamente os atributos necessários.
3. O trigger foi criado corretamente, ou seja, inserindo um registro na tabela de log
após a atualização do status do aluno.
4. Criou uma query relacionando pelo menos 3 tabelas.
5. Além do SQL das 5 questões básicas foram entregues outros SQLs para
perguntas adicionais (extra).
Análise
exploratória e
apresentação
de resultados
1. A 5ª pergunta (adicional) agrega valor e é criativa para exploração de dados.
2. A modelagem e os scripts SQL foram incluídos na apresentação.
3. Todas as perguntas foram abordadas durante a apresentação dos resultados.
4. A apresentação foi entregue em slides, PDF ou alguma outra ferramenta de
apresentação que permita exportação em PDF e dentro do prazo correto.
5. Os resultados foram apresentados de forma criativa. (extra).

RUBRICA
Conteúdo Habilidades
Git/GitHub
1. Entregou o link do repositório no GitHub no prazo correto;
2. Todos os scripts SQL foram entregues no repositório;
3. Foi colocado um arquivo README.md explicando do que se trata e como pode
ser executado;
4. O projeto foi enviado em commits por etapas;
5. As descrições dos commits/PRs estão bem redigidas e apresentam bem as
mudanças realizadas. (Extra).
