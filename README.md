# Projeto de Estudos Angular

Este repositório contém um projeto desenvolvido com o objetivo de estudar e aprofundar conhecimentos no framework **Angular**. O foco principal é a compreensão da arquitetura baseada em componentes e a implementação de elementos de interface reutilizáveis.

## 🎯 Objetivo do Projeto

Este é um ambiente de aprendizado prático para:
*   Entender o ciclo de vida de uma aplicação Angular.
*   Criar e gerenciar **Componentes Personalizados** (como o `<app-my-component>`).
*   Praticar a estruturação de templates HTML e estilos CSS encapsulados.

## 🧩 Sobre Componentes no Angular

### O que são?
No Angular, componentes são os blocos de construção fundamentais da Interface do Usuário (UI). Cada componente consiste em um template HTML, estilos CSS e uma classe TypeScript que define seu comportamento.

### Qual sua função em projetos reais?
Em aplicações comerciais e de grande escala, a componentização é vital por diversos motivos:

1.  **Reutilização:** Um componente (ex: botão, card, menu) é criado uma única vez e pode ser utilizado em diversas páginas, garantindo consistência visual e funcional.
2.  **Manutenibilidade:** Como a lógica e o estilo são isolados, corrigir um bug ou alterar o design de um componente reflete automaticamente em toda a aplicação.
3.  **Modularidade:** Permite que equipes trabalhem em diferentes partes do sistema simultaneamente sem conflitos, dividindo a interface em partes menores e gerenciáveis.

## 🚀 Como utilizar este projeto

Siga as instruções abaixo para baixar e executar o projeto em sua máquina local.

### Pré-requisitos

Certifique-se de ter instalado:
*   Node.js
*   Angular CLI (Instale via terminal: `npm install -g @angular/cli`)

### Instalação

1.  Clone este repositório:
    ```bash
    git clone <url-do-repositorio>
    ```
2.  Acesse a pasta do projeto:
    ```bash
    cd angular-project
    ```
3.  Instale as dependências do projeto:
    ```bash
    npm install
    ```

### Executando a Aplicação

Para iniciar o servidor de desenvolvimento, execute:

```bash
ng serve
```

Abra o navegador e acesse `http://localhost:4200/`. A aplicação será recarregada automaticamente sempre que você alterar os arquivos de código fonte.