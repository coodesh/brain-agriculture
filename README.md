Bem-vindo(a) ao nosso teste técnico. Estamos muito animados para conhecer mais sobre você, suas habilidades técnicas e sua forma de resolver problemas.

Este teste foi pensado para ser um reflexo do que valorizamos em nosso time, e esperamos que você se sinta confortável e confiante durante o processo.

**O que queremos avaliar?**
---------------------------

Nosso objetivo com este teste é entender melhor como você:

*   Resolve problemas relacionados à lógica de programação e orientação a objetos.
    
*   Interpreta requisitos de negócio e os transforma em soluções técnicas.
    
*   Aplica boas práticas de desenvolvimento, com foco em código limpo, testável, de fácil manutenção e observável.
    
*   Garante que o sistema seja escalável e confiável, principalmente ao lidar com grande volume de dados.
    
*   Escreve documentações claras para facilitar a integração e manutenção por outros desenvolvedores ou clientes.
    

**Dica:** Imagine que você está criando uma aplicação que será utilizada por clientes, parceiros ou até mesmo por outros desenvolvedores. Queremos ver sua atenção aos detalhes!

**O que você precisa desenvolver?**
-----------------------------------

A proposta é criar uma aplicação para gerenciar o cadastro de produtores rurais, com os seguintes dados:

*   CPF ou CNPJ
    
*   Nome do produtor
    
*   Nome da fazenda (propriedade)
    
*   Cidade
    
*   Estado
    
*   Área total da fazenda (em hectares)
    
*   Área agricultável (em hectares)
    
*   Área de vegetação (em hectares)
    
*   Safras (ex: Safra 2021, Safra 2022)
    
*   Culturas plantadas (ex.: Soja na Safra 2021, Milho na Safra 2021, Café na Safra 2022)
    

### **Requisitos de negócio**

1.  Permitir o cadastro, edição e exclusão de produtores rurais.
    
2.  Validar o CPF ou CNPJ fornecido pelo usuário.
    
3.  Garantir que a soma das áreas agricultável e de vegetação não ultrapasse a área total da fazenda.
    
4.  Permitir o registro de várias culturas plantadas por fazenda do produtor.
    
5.  Um produtor pode estar associado a 0, 1 ou mais propriedades rurais.
    
6.  Uma propriedade rural pode ter 0, 1 ou mais culturas plantadas por safra.
    
7.  Exibir um dashboard com:
    
    *   Total de fazendas cadastradas (quantidade).
        
    *   Total de hectares registrados (área total).
        
    *   Gráficos de pizza:
        
        *   Por estado.
            
        *   Por cultura plantada.
            
        *   Por uso do solo (área agricultável e vegetação).
            

* * *

**Tecnologias sugeridas**
-------------------------

Sabemos que você pode ter seu próprio estilo, mas aqui estão algumas tecnologias e boas práticas que valorizamos:

*   **Conceitos**: SOLID, KISS, Clean Code, API Contracts, Testes, Arquitetura em camadas.
    
*   **Documentações**: Para facilitar o entendimento do funcionamento do sistema, é importante incluir um README claro, uma especificação OpenAPI e, caso necessário, diagramas que ajudem a visualizar a arquitetura ou os processos.
    
*   **Bônus**: Se conseguir disponibilizar a aplicação na nuvem e acessível via internet, será um diferencial!
    

### **FRONTEND:**

*   Utilize **TypeScript**.
    
*   Utilize **ReactJS**.
    
*   Use **Redux** para gerenciar o estado da aplicação.
    
    *   Se preferir, você pode usar **Context API** como alternativa ou complemento ao Redux (opcional).
        
*   Estruture dados "mockados" para simular cenários.
    
*   Desenvolva testes unitários com **Jest** e **React Testing Library**.
    
*   Estruture os componentes utilizando atomic design patterns.
    
*   Utilize css in js com bibliotecas como **Styled Components** ou **Emotion**.
    
*   Estruture o projeto como um microfrontend (opcional);
    

### **BACKEND:**

*   Desenvolva uma **API REST** utilizando tecnologias uma das opções de tecnologias:
    
    *   Typescript, Nestjs ou AdonisJs
        
    *   Python 3, Django, Flask ou FastAPI
        
*   Utilize **Docker** para distribuir a aplicação.
    
*   Utilize **Postgres** como banco de dados.
    
*   Crie os endpoints necessários para atender os requisitos de negócio.
    
*   Desenvolva testes unitários e integrados.
    
*   Estruture dados "mockados" para testes.
    
*   Inclua logs para garantir a observabilidade do sistema, facilitando o monitoramento e a identificação de possíveis problemas.
    
*   Utilize um framework de ORM.
    

* * *

**Nota final:** Queremos que você aproveite esse desafio para mostrar suas habilidades, mas também para aprender e se divertir. Se tiver dúvidas ou precisar de alguma orientação durante o processo, estamos aqui para ajudar! Boa sorte! 🌟

## Readme do Repositório

- Deve conter o título do projeto
- Uma descrição sobre o projeto em frase
- Deve conter uma lista com linguagem, framework e/ou tecnologias usadas
- Como instalar e usar o projeto (instruções)
- Não esqueça o [.gitignore](https://www.toptal.com/developers/gitignore)
- Se está usando github pessoal, referencie que é um challenge by coodesh:  

>  This is a challenge by [Coodesh](https://coodesh.com/)

## Finalização e Instruções para a Apresentação

1. Adicione o link do repositório com a sua solução na questão
2. Verifique se o Readme está bom e faça o commit final em seu repositório;
3. Envie e aguarde as instruções para seguir. Caso o teste tenha apresentação de vídeo, dentro da tela de entrega será possível gravar após adicionar o link do repositório. Sucesso e boa sorte. =)


## Suporte

Para tirar dúvidas sobre o processo envie uma mensagem diretamente a um especialista no chat da plataforma. 
