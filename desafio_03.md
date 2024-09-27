# Desafio 3
 
### Processando e Transformando Dados com Power BI

Repositório com exemplos de uso de Base de Dados no Postgres e Power BI para manipulação e visualização de dados.

> [!NOTE]
> Arquivos do desafio:
> 
> Processando e Transformando Dados com Power BI - Instruções.docx</br> 
> Desafio de Projeto - Processando e Transformando Dados com Power BI.pptx
> 
>**https://github.com/julianazanelatto/power_bi_analyst**
 
> [!TIP]
> *Dica: Se o expert forneceu um repositório Github, você pode dar um "fork" no repositório dele para organizar suas alterações e evoluções mantendo uma referência direta ao código-fonte original.*
 
## Instruções para entrega

> [!IMPORTANT]
> ### Instruções de Desenvolvimento do Projeto
> Descrição do desafio módulo 3 – **Processamento de Dados Simplificado com Power BI**
>
> 1. Criação de uma instância na Azure para MySQL
> 
> 2. Criar o Banco de dados com base disponível no github
> 
> 3. Integração do Power BI com MySQL no Azure
> 
> 4. Verificar problemas na base a fim de realizar a transformação dos dados

> [!TIP]
> ### Diretrizes para transformação dos dados
> 
> 1. Verifique os cabeçalhos e tipos de dados
> 
> 2. Modifique os valores monetários para o tipo double preciso
> 
> 3. Verifique a existência dos nulos e analise a remoção
> 
> 4. Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente
> 
> 5. Verifique se há algum departamento sem gerente
> 
> 6. Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas
> 
> 7. Verifique o número de horas dos projetos
> 
> 8. Separar colunas complexas
> 
> 9. Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção
> 
> 10. Neste processo elimine as colunas desnecessárias.
> 
> 11. Realize a junção dos colaboradores e respectivos nomes dos gerentes . Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo.
> 
> 12. Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores
> 
> 13. Mescle os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. Isso irá auxiliar na criação do modelo estrela em um módulo futuro.
> 
> 14. Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir.
> 
> 
> 15. Agrupe os dados a fim de saber quantos colaboradores existem por gerente
> 
> 16. Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela
 

Além disso:  

- Publicar o relatório 

- Compartilhar como suplemento no Power Point

- Salvar o projeto de Power BI

# Projeto Criado

Vídeo demonstrativo em Power BI - [Youtube]()

### Base de Dados no PgAdmin - PostGres
![image](https://github.com/user-attachments/assets/1543ee25-8681-42a0-9037-d8c814652427)



Obrigado 😉
