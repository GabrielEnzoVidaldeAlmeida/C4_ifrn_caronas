# DOCUMENTAÇÃO C4 - IFRN CARONAS

Este repositório contém os diagramas de arquitetura do sistema **IFRN Caronas**, um sistema de compartilhamento de caronas voltado para a comunidade acadêmica do IFRN.

Os diagramas seguem o **modelo C4 do nível 1 ao 3** (Contexto, Containers e Componentes), com uma abordagem moderna para modelar arquiteturas de software em múltiplos níveis de detalhe.

Todos os diagramas foram escritos em **PlantUML** com a biblioteca oficial **C4-PlantUML**.

## 📐 Estrutura dos Diagramas

| Nível | Nome do Diagrama        | Descrição |
|-------|--------------------------|-----------|
| 1️⃣    | `context_diagram.puml`  | Visão geral do sistema IFRN Caronas e seus atores e sistemas externos (SUAP, e-mail, Google Maps). |
| 2️⃣    | `container_diagram.puml`| Detalhamento dos containers internos: Web App, Mobile App, API Backend, Banco de Dados e Módulo de Notificações. |
| 3️⃣    | `web_application.puml`| Componentes internos da aplicação web feita em Next.js. |
| 3️⃣    | `mobile_application.puml`| Componentes da aplicação mobile feita em React Native. |
| 3️⃣    | `api_backend.puml`| Componentes da API Backend (Django REST Framework), incluindo autenticação, caronas, avaliações, notificações e logs. |

## 🚀 Como visualizar os diagramas PlantUML

1. Instale a extensão **PlantUML** no VS Code.
2. Verifique se o **Java** está instalado utilizando `java -version` no cmd.
3. Pressione ALT+D (ou Cmd+D no macOS) para renderizar.
4. Use arquivos .puml normalmente como preview ao vivo - o seu VS Code abrirá uma aba ao lado mostrando o preview do diagrama.

