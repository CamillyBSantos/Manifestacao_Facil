1) Descrição do Programa:  

- O programa é um sistema básico de controle de manifestações que são registradas na página da empresa contratante, permitindo uma visão das manifestações que estão em aberto/em tratativa/fechado com exibição de RA ID, nome do consumidor, data da manifestação, assunto e status. 

- Campo Chave: RA ID.  

 

2) Tipo de Serviço/Produto:  

- Sistema de Gerenciamento de Manifestações do Reclame Aqui.  

 

3) Objetivos Principais:  

- Criar um sistema básico para controle e visualização de manifestações que estão em aberto/em tratativa/fechado.  

 

4) Objetivos Específicos:  

- Proporcionar um armazenamento centralizado dos dados básicos das manifestações.  

- Facilitar o acesso rápido a informações de cada manifestação, como assunto e status.  

- Garantir um sistema seguro para evitar duplicidade de registros através da chave primária “RA ID”.  

 

5) Público-Alvo:  

- Empresas que possuem cadastro no site do Reclame Aqui e querem ter um controle das manifestações que entram no site  

 

6) Principal Diferencial:  

- Simplicidade e foco nos dados essenciais, ideal para empresas que precisam apenas de um controle básico sem funcionalidades extras. 

 

7) Metodologia e Tecnologias Propostas:  

- Metodologia: Desenvolvimento ágil com iterações curtas, baseadas no feedback contínuo do cliente.  

- Tecnologias: Repositório de Dados em TXT e interface orientada a caractere e gráfica (GUI), linguagem Python e interface gráfica TK Interface.  

 

8) Resultados Esperados:  

- Registro eficiente e seguro das manifestações.  

- Redução de erros manuais no controle e consulta de informações (data/nome do consumidor/assunto/status).  

- Sistema funcional, fácil de usar, com baixo custo de manutenção.  

 

9) Modelo Entidade-Relacionamento (ER) 


Entidade: Manifestações. 

Atributos:  

 -  RA ID (Chave Primária)  

-  Data da manifestação 

- Nome do consumidor 

- Assunto 

- Status 

 

10) Esboço UML da Documentação  

Diagrama de Classes:  

- Classe Manifestação como os atributos de RA ID, data da manifestação, nome do consumidor, assunto e status.  

Atributos:  

- RA ID: string 

- Data da manifestação: string 

- Nome do consumidor: string 

- Assunto: string 

- Status: string 

 Métodos principais:  

•  consultarManifestacao (): para recuperar os dados de uma manifestação.   

•  adicionarManifestacao (): para adicionar uma nova manifestação.  

•  atualizarManifestacao (): para atualizar informações de uma manifestação já existente.  

•  removerManifestacao (): para remover uma manifestação sistema.  

•  relatórioManifestacao (): lista todas as manifestações do repositório.  
