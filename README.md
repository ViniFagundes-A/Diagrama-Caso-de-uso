# Diagrama-Caso-de-uso
Repositório para armazenar o diagrama de caso de uso do sistema de suporte de TI.

## UML Class Diagrams

Este repositório contém diagramas de classe UML para cada caso de uso do sistema ClickDesk, modelados seguindo o padrão BCE (Boundary-Control-Entity).

### Estrutura dos Diagramas

Os diagramas estão organizados em:
- `uml/class/` - Arquivos fonte PlantUML (.puml)
- Imagens PNG e SVG são geradas automaticamente via GitHub Actions

### Casos de Uso Disponíveis

1. **UC-Abrir-Chamado** (`uc-abrir-chamado-bce.puml`) - Abertura de novos chamados
2. **UC-Consultar-Chamado** (`uc-consultar-chamado-bce.puml`) - Consulta de chamados existentes
3. **UC-Visualizar-Notificacao** (`uc-visualizar-notificacao-bce.puml`) - Visualização de notificações
4. **UC-Fornecer-Feedback** (`uc-fornecer-feedback-bce.puml`) - Fornecimento de feedback
5. **UC-Encerrar-Chamado** (`uc-encerrar-chamado-bce.puml`) - Encerramento de chamados
6. **UC-Atualizar-Status-Chamado** (`uc-atualizar-status-chamado-bce.puml`) - Atualização de status
7. **UC-Visualizar-Chamados-Designados** (`uc-visualizar-chamados-designados-bce.puml`) - Visualização de chamados atribuídos
8. **UC-Consultar-Historico-Sistema** (`uc-consultar-historico-sistema-bce.puml`) - Consulta ao histórico do sistema
9. **UC-Consultar-Historico-Chamado** (`uc-consultar-historico-chamado-bce.puml`) - Consulta ao histórico de chamados

### Como Visualizar os Diagramas

#### Localmente

1. **PlantUML CLI:**
   ```bash
   # Instalar PlantUML
   wget https://github.com/plantuml/plantuml/releases/latest/download/plantuml.jar
   
   # Gerar PNG
   java -jar plantuml.jar -tpng uml/class/*.puml
   
   # Gerar SVG
   java -jar plantuml.jar -tsvg uml/class/*.puml
   ```

2. **Visual Studio Code:**
   - Instale a extensão "PlantUML"
   - Abra qualquer arquivo `.puml`
   - Use `Ctrl+Shift+P` → "PlantUML: Preview Current Diagram"
   - Use `Ctrl+Shift+P` → "PlantUML: Export Current Diagram"

#### Automaticamente

Os diagramas são renderizados automaticamente em PNG e SVG sempre que arquivos `.puml` são modificados e enviados para o repositório via GitHub Actions.
