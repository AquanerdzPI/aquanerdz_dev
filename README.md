# aquanerdz_dev
Este repositório contém o desenvolvimento de um servidor para hospedar um site voltado para o gerenciamento de sistemas aquapônicos. O frontend foi desenvolvido em Angular, enquanto a API foi construída usando TypeScript.

## Descrição
O projeto visa permitir que os usuários cadastrem e monitorem seus sistemas aquapônicos, fornecendo uma interface intuitiva para o gerenciamento e o acompanhamento em tempo real de diversos parâmetros, como:

**Temperatura da água:** Monitoramento constante das condições de temperatura.  
**Tempo desde a última limpeza:** Informações sobre a manutenção do sistema.  
**Alimentação automática:** Controle e programação da alimentação dos peixes.  
Outros parâmetros personalizados: Adaptação para diferentes sensores e necessidades específicas dos usuários.

## Funcionalidades
**Cadastro de Sistemas:** Os usuários podem registrar seus sistemas aquapônicos com detalhes específicos.  
**Monitoramento em Tempo Real:** Visualização de dados em tempo real, como temperatura e status de limpeza.  
**Alertas e Notificações:** Sistema de alertas para condições críticas ou que necessitam de atenção.  
**Controle de Alimentação:** Gerenciamento da alimentação automática dos peixes com base em horários ou condições pré-definidas.  

## Tecnologias Utilizadas
**Frontend:** Angular  
**Backend/API:** TypeScript  
**Servidor:** Até o presente momento, nenhuma tecnologia foi escolhida, encontra-se em fase de pesquisa  
**Banco de Dados:** MySQL  

## Estrutura do Projeto
frontend/: Código-fonte do frontend desenvolvido em Angular.  
backend/: Código-fonte da API desenvolvida em TypeScript.  
docs/: Documentação adicional, incluindo diagramas e especificações técnicas.  
tests/: Testes automatizados para as funcionalidades do sistema.  

## Como Executar o Projeto

### Pré-requisitos
Node.js instalado na máquina  
[Outros pré-requisitos, ex.: Docker, Banco de Dados configurado, etc.]  
#### Passo a Passo
Clone o repositório:  

**no git bash:**
Copiar código  
*git clone https://github.com/seu-usuario/seu-repositorio.git*  
cd seu-repositorio  
Instale as dependências:  

Para o backend:  

- editor de texto (recomendação VS code)
- github
- acesso a internet

Para o frontend:

- editor de texto (recomendação VS code)
- github
- acesso a internet
  
Configure as variáveis de ambiente:

Crie um arquivo .env na pasta backend e configure as variáveis de ambiente necessárias:

makefile
Copiar código
PORT=3000
DB_CONNECTION_STRING=your_database_connection_string
[Outras variáveis]
Execute o servidor e o frontend:

### Iniciando o projeto

**Para iniciar o backend:**

1. git bash
2. Copiar código (back-end)
3. Entre na pasta backend
4. Digite "npm start"

**Para iniciar o frontend:**

1. git bash
2. Copiar código (front-end)
3. Entre na pasta frontend
4. Digite "ng serve"
5. Acesse o site

*O frontend estará disponível em http://localhost:4200.*

## Contribuição:
*Sinta-se à vontade para contribuir com este projeto. Para isso, siga os passos abaixo:*

Faça um fork do projeto.
Crie uma branch para sua feature (git checkout -b minha-feature).
Commit suas alterações (git commit -m 'Adiciona minha feature').
Envie para o branch principal (git push origin minha-feature).
Abra um Pull Request.
Licença
Este projeto está licenciado sob a licença MIT.
