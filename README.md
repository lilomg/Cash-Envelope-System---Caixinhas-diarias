[readme_gerenciador_de_caixinhas_financeiras.txt](https://github.com/user-attachments/files/34129931/readme_gerenciador_de_caixinhas_financeiras.txt)
========================================================================
             CAIXAS DIÁRIAS - GESTÃO FINANCEIRA EMPRESARIAL
========================================================================

SOBRE O SISTEMA
------------------------------------------------------------------------
O "Caixas Diárias" é uma aplicação web (Single Page Application - SPA) 
desenvolvida para gestão financeira empresarial com foco na metodologia 
de alocação diária por centros de custos ("caixinhas").

O sistema permite que empresas reservem valores diariamente para cobrir 
despesas recorrentes (aluguel, salários, fornecedores, impostos, 
empréstimos) e acompanhem o saldo acumulado em tempo real.


RECURSOS E FUNCIONALIDADES PRINCIPAIS
------------------------------------------------------------------------
1. ALOCAÇÃO DIÁRIA DE RECURSOS:
   - Definição de metas diárias por caixinha.
   - Configuração de dias ativos na semana (ex: Seg-Sex, Finais de semana).
   - Divisão de valores guardados entre Dinheiro (Espécie) e Banco/PIX.
   - Lupa de busca em tempo real (pesquisa por nome ou categoria).
   - Filtros de ordenação (Ordem de criação, Alfabética A-Z ou Categoria).
   - Botões de atalho (+ e -) em cada card para entradas e retiradas rápidas.

2. METAS MENSAIS OPCIONAIS:
   - Configuração facultativa de meta mensal (R$) por caixinha.
   - Barras de progresso e porcentagem de atingimento no mês.

3. PAINEL DE DADOS GERENCIAIS:
   - Modal com métricas consolidadas:
     * Movimentação do dia (Dinheiro, Banco e Total Alocado).
     * Acumulado Líquido do Mês (Entradas menos Retiradas).
     * Acumulado Histórico Global de todas as caixinhas.

4. DIVERSIDADE DE CATEGORIAS E ÍCONES:
   - Gerenciador completo de categorias personalizadas.
   - Suporte a ícones dedicados (ex: Gastos com Funcionários, Empréstimos &
     Financiamentos, Pro-labore, Fornecedores, Impostos, etc.).

5. HISTÓRICO DE RETIRADAS E DÉBITOS:
   - Registro de saídas especificando a caixinha, a origem (Dinheiro/Banco),
     data e motivo/descrição.
   - Tabela detalhada de histórico com suporte a exclusão/estorno.

6. RESUMO E GRÁFICOS POR PERÍODO:
   - Gráfico de barras comparativo (Chart.js) do acumulado mensal.
   - Detalhamento individual de cada caixinha no período.

7. SINCRONIZAÇÃO EM NUVEM & MULTI-DISPOSITIVO (GOOGLE SYNC):
   - Conexão por e-mail no modal Google Sync (Nuvem).
   - Sincronização automática entre Computador, Celular e Tablet.
   - Integração opcional com Google Sheets através de Google Apps Script.

8. PERSONALIZAÇÃO DA EMPRESA:
   - Customização do nome, subtítulo e upload de logo (.jpg / .png).

9. BACKUP E SEGURANÇA:
   - Exportação e importação de backups em formato .json.
   - Opção de restaurar caixinhas demonstrativas padrão.
   - Suporte a Modo Claro / Modo Escuro (Dark Mode).


COMO EXECUTAR O PROJETO
------------------------------------------------------------------------
1. Baixe ou salve o arquivo `index.html`.
2. Abra o arquivo `index.html` em qualquer navegador web moderno 
   (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari).
3. Não é necessária a instalação de servidores ou dependências locais.


TECNOLOGIAS UTILIZADAS
------------------------------------------------------------------------
- HTML5 & JavaScript ES6+ (Módulos)
- Tailwind CSS (Interface responsiva e Dark Mode)
- FontAwesome 6 (Ícones vetoriais)
- Chart.js (Gráficos interativos)
- LocalStorage & Fetch API (Armazenamento local e integração com Nuvem)
- Google Identity Services API (Estrutura de autenticação)


DIREITOS AUTORAIS
------------------------------------------------------------------------
© Caixas Diárias - Sistema de Gestão e Alocação Financeira Empresarial.
Todos os direitos reservados.
