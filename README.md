📦 CaixasDiárias - Gestão de Caixinhas Financeiras para Empresas

O CaixasDiárias é um sistema web responsivo (Single Page Application - SPA) focado na metodologia de alocação diária de recursos por centro de custos/despesas (método de caixinhas). Ele permite que pequenas e médias empresas reservem, diariamente e de forma disciplinada, os valores necessários para cobrir suas despesas operacionais recorrentes, como aluguel, pro-labore, folha, fornecedores, impostos e reservas.

🎯 Funcionalidades Principais

Alocação Diária Fracionada:

Definição de metas diárias de alocação por caixinha.

Escolha dos dias da semana ativos para cada despesa (ex: 5 dias por semana, finais de semana ou dias específicos).

Separação dos valores guardados em Dinheiro (Espécie) e Conta Corrente (PIX/Banco).

Botões de alocação rápida (Marcar Todos / Limpar Dia) e marcação individual.

Visão Financeira Completa:

Exibição dos valores acumulados em cada caixinha no Mês Atual e no Histórico Global.

Rastreamento visual de metas diárias atingidas e caixinhas com pendências no dia.

Gráfico interativo comparativo de saldos mensais por caixinha (alimentado por Chart.js).

Gestão Integrada de Retiradas e Débitos:

Modal para registrar pagamentos ou resgates das caixinhas.

Escolha da fonte do recurso retirado (Dinheiro ou Banco).

Dedução automática dos valores debitados no saldo da caixinha, no acumulado do mês e no histórico global.

Extrato/Histórico completo de retiradas com opção de estorno.

Recursos Adicionais:

Modo Escuro / Modo Claro (Dark/Light Mode): Botão no cabeçalho com alternância dinâmica de tema e persistência de escolha.

Backup e Restauração: Exportação e importação dos dados em formato JSON para cópia de segurança e transferência entre aparelhos.

Offline-First: Armazenamento seguro de todas as informações diretamente no localStorage do navegador, sem necessidade de banco de dados externo ou servidor.

🚀 Como Executar o Projeto Localmente

Faça o download ou copie o código do arquivo index.html.

Salve o arquivo em uma pasta no seu computador como index.html.

Dê dois cliques no arquivo para abri-lo em qualquer navegador de sua preferência (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari).

🌐 Como Publicar como Web App Gratuitamente

Opção 1: Netlify (Recomendado - 2 minutos)

Acesse netlify.com e crie uma conta gratuita.

Acesse a aba Sites.

Arraste a pasta que contém o arquivo index.html e solte dentro do painel do Netlify.

Seu aplicativo estará disponível instantaneamente em um link HTTPS do tipo https://seu-nome.netlify.app.

Opção 2: GitHub Pages

Acesse github.com e crie um repositório público.

Faça upload do arquivo index.html.

Acesse Settings > Pages do repositório, selecione a branch main e salve.

Aguarde a ativação da URL pública no formato https://seu-usuario.github.io/nome-do-repositorio/.

📱 Instalação no Celular sem Loja (PWA / Atalho)

O aplicativo é 100% responsivo e pode ser adicionado à tela inicial do seu dispositivo móvel:

Android (Chrome): Acesse a URL do app no navegador, toque no menu de 3 pontos no canto superior e selecione "Adicionar à tela inicial" ou "Instalar aplicativo".

iPhone / iOS (Safari): Acesse a URL no Safari, toque no ícone de Compartilhar (quadrado com seta para cima) e escolha "Adicionar à Tela de Início".

🛠️ Tecnologias Utilizadas

HTML5 / Single-Page Architecture

Tailwind CSS (v3): Estilização moderna e suporte a temas.

FontAwesome (v6): Conjunto de ícones para componentes visuais.

Chart.js: Renderização do gráfico de progresso mensal.

JavaScript (ES6+): Regras de negócio, cálculos financeiros, manipuladores do DOM e controle do localStorage.

🔒 Privacidade e Segurança dos Dados

Todos os registros inseridos nesta aplicação permanecem restritos ao navegador do usuário (localStorage). Nenhuma informação financeira é enviada para servidores externos ou terceiros.
