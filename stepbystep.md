FASE 1: FUNDAÇÃO E MVP (Meses 1-3)
Objetivo: Sistema básico funcionando para pedidos presenciais
Sprint 1-2: Infraestrutura Base (4 semanas)
Semana 1-2: Setup do Projeto
Backend:
•	[x] Configurar ambiente de desenvolvimento :check:
•	[x] Setup do banco de dados (PostgreSQL) :check:
•	[x] Estrutura básica da API (Node.js/Express ou Python/Django) :check:
•	[x] Sistema de autenticação JWT :check:
•	[x] Middleware de logs e segurança :check:
Frontend:
•	[x] Setup React/Vue.js :check:
•	[x] Configuração PWA base :check:
•	[x] Sistema de roteamento :check:
•	[x] Componentes UI base (botões, inputs, modals) :check:
DevOps:
•	[x] Docker para desenvolvimento :check:
•	[x] CI/CD básico :check:
•	[x] Ambiente de staging :check:
Semana 3-4: Modelos de Dados Core
Banco de Dados:
•	[x] Tabela de usuários e permissões :check:
•	[x] Tabela de produtos :check:
•	[x] Tabela de mesas :check:
•	[x] Tabela de pedidos :check:
•	[x] Tabela de clientes :check:
•	[x] Relacionamentos básicos :check:
APIs Base:
•	[x] CRUD usuários :check:
•	[x] CRUD produtos :check:
•	[x] CRUD mesas :check:
•	[x] Sistema de login/logout :check:
Sprint 3-4: Core do Sistema Presencial (4 semanas)
Semana 5-6: Gestão de Produtos e Mesas
Funcionalidades:
•	[x] Cadastro/edição de produtos :check:
•	[x] Interface de seleção de mesa :check:
•	[x] Associação automática mesa-pedido :check:
•	[x] Layout visual das mesas :check:
Telas:
•	[x] Dashboard principal :check:
•	[x] Tela de produtos :check:
•	[x] Tela de mesas :check:
•	[x] Modal de edição :check:
Semana 7-8: Sistema de Pedidos Básico
Funcionalidades:
•	[x] Criar pedido presencial :check:
•	[x] Adicionar produtos ao pedido :check:
•	[x] Campo de observações :check:
•	[x] Cálculo de totais :check:
•	[x] Salvar pedido :check:
Telas:
•	[x] Interface de pedidos :check:
•	[x] Carrinho de compras :check:
•	[x] Resumo do pedido :check:
Sprint 5-6: Clientes e Pagamentos (4 semanas)
Semana 9-10: Gestão de Clientes
Funcionalidades:
•	[x] Cadastro de clientes (nome, CPF, telefone) :check:
•	[x] Busca de clientes :check:
•	[x] Validação de CPF :check:
•	[x] Histórico básico :check:
Telas:
•	[x] Cadastro de cliente :check:
•	[x] Busca de cliente :check:
•	[x] Perfil do cliente :check:
Semana 11-12: Sistema de Pagamento Básico
Funcionalidades:
•	[x] Finalização de pedidos :check:
•	[x] Diferentes formas de pagamento :check:
•	[x] Recibos básicos :check:
•	[x] Status de pagamento :check:
Integrações:
•	[x] API básica de pagamento (mock inicialmente) :check:
________________________________________
FASE 2: OPERACIONAL COMPLETO (Meses 4-5)
Objetivo: Sistema completo para operação presencial
Sprint 7-8: Cozinha e Impressão (4 semanas)
Semana 13-14: Interface da Cozinha
Funcionalidades:
•	[x] Painel da cozinha :check:
•	[x] Fila de pedidos :check:
•	[x] Marcar como "em preparo" :check:
•	[x] Marcar como "pronto" :check:
•	[x] Timer de preparo :check:
Telas:
•	[x] Dashboard da cozinha :check:
•	[x] Card de pedido :check:
•	[x] Controles de status :check:
Semana 15-16: Sistema de Impressão
Funcionalidades:
•	[x] Integração com impressora local :check:
•	[x] Template de comanda :check:
•	[x] Impressão automática :check:
•	[x] Fila de impressão :check:
•	[x] Retry em caso de falha :check:
Integração:
•	[x] Driver de impressora :check:
•	[x] Comunicação via rede local :check:
Sprint 9-10: Controle de Estoque (4 semanas)
Semana 17-18: Ficha Técnica
Funcionalidades:
•	[x] Cadastro de ingredientes :check:
•	[x] Edição de ingredientes :check:
•	[x] Ficha técnica por produto :check:
•	[x] Interface de ficha técnica com ingredientes :check:
•	[x] Unidades dinâmicas baseadas no ingrediente :check:
•	[x] Conversão automática g → kg :check:
•	[x] Dropdown individual por campo de ingrediente :check:
•	[x] Click outside para fechar dropdowns :check:
•	[x] Filtros independentes por linha :check:
•	[x] Unidades de medida :check:
•	[x] Custo por produto :check:
Telas:
•	[x] Cadastro de ingredientes :check:
•	[x] Modal de edição de ingredientes :check:
•	[x] Ficha técnica dinâmica no modal de produtos :check:
•	[x] Montagem de ficha técnica :check:
•	[x] Calculadora de custos :check:
Semana 19-20: Controle de Estoque
Funcionalidades:
•	[x] Baixa automática por pedido :check:
•	[x] Alertas de estoque baixo :check:
•	[x] Relatório de consumo :check:
•	[x] Entrada de mercadorias :check:
Dashboards:
•	[x] Painel de estoque :check:
•	[x] Alertas visuais :check:
•	[x] Gráficos de consumo :check:
________________________________________
FASE 3: DELIVERY E MOBILE (Meses 6-7)
Objetivo: Expandir para delivery e mobile
Sprint 11-12: Sistema Delivery (4 semanas)
Semana 21-22: Backend Delivery
Funcionalidades:
•	[x] Tabelas de endereços :check:
•	[x] Cálculo de taxa de entrega :check:
•	[x] Status de entrega :check:
•	[x] Código de confirmação :check:
•	[x] Tempo estimado :check:
APIs:
•	[x] Endpoints de delivery :check:
•	[x] Validação de endereço :check:
•	[x] Cálculo de frete :check:
Semana 23-24: Interface Delivery
Funcionalidades:
•	[x] Cardápio online público :check:
•	[x] Carrinho de delivery :check:
•	[x] Formulário de endereço :check:
•	[x] Rastreamento de pedido :check:
Telas:
•	[x] Cardápio público :check:
•	[x] Checkout delivery :check:
•	[x] Acompanhamento :check:
Sprint 13-14: QR Code e Cardápio Digital (4 semanas)
Semana 25-26: Cardápio Digital
Funcionalidades:
•	[x] Geração de QR Code por mesa :check:
•	[x] Cardápio responsivo :check:
•	[x] Filtros e categorias :check:
•	[x] Detalhes do produto :check:
Telas:
•	[x] Cardápio mobile :check:
•	[x] Detalhes do produto :check:
•	[x] Categorias :check:
Semana 27-28: Sistema de Entregadores
Funcionalidades:
•	[x] Painel do entregador :check:
•	[x] Lista de entregas :check:
•	[x] Confirmar entrega com código :check:
•	[x] Status em tempo real :check:
Mobile/PWA:
•	[x] App do entregador :check:
•	[x] Notificações push :check:
•	[x] Offline sync básico :check:
________________________________________
FASE 4: PAGAMENTOS E INTEGRAÇÕES (Mês 8)
Objetivo: Integrar pagamentos e sistemas externos
Sprint 15-16: Integrações de Pagamento (4 semanas)
Semana 29-30: Maquininha e Pagamentos
Integrações:
•	[x] API da maquininha de cartão :check:
•	[x] PIX integrado :check:
•	[x] Pagamento parcial :check:
•	[x] Divisão de conta :check:
Funcionalidades:
•	[x] Aba "mesa-cartão" :check:
•	[x] Controle de pagamentos parciais :check:
•	[x] Conciliação automática :check:
Semana 31-32: Nota Fiscal
Integrações:
•	[x] API SEFAZ :check:
•	[x] NFCe automática :check:
•	[x] Cadastro de NCM :check:
•	[x] Numeração sequencial :check:
Funcionalidades:
•	[x] Emissão automática :check:
•	[x] Reenvio de NFCe :check:
•	[x] Relatório fiscal :check:
________________________________________
FASE 5: AUTOMAÇÃO E IA (Meses 9-10)
Objetivo: WhatsApp e automação inteligente
Sprint 17-18: Integração WhatsApp (4 semanas)
Semana 33-34: API Evolution
Integrações:
•	[x] Conexão com Evolution API :check:
•	[x] Webhook de mensagens :check:
•	[x] Envio de mensagens :check:
•	[x] Gerenciamento de sessões :check:
Base IA:
•	[x] Processamento de texto básico :check:
•	[x] Reconhecimento de intenções :check:
•	[x] Fluxo de conversação :check:
Semana 35-36: IA de Atendimento
Funcionalidades:
•	[x] Bot de atendimento :check:
•	[x] Processamento de pedidos :check:
•	[x] Confirmação automática :check:
•	[x] Escalação para humano :check:
Features:
•	[x] Cardápio via chat :check:
•	[x] Pedidos via WhatsApp :check:
•	[x] Status automático :check:
•	[x] Códigos de entrega :check:
Sprint 19-20: Automação Avançada (4 semanas)
Semana 37-38: Notificações Inteligentes
Funcionalidades:
•	[x] Notificar cliente quando pronto :check:
•	[x] Alertas de atraso :check:
•	[x] Confirmação de entrega :check:
•	[x] Feedback automático :check:
Semana 39-40: Otimizações IA
Melhorias:
•	[x] ML para tempo de preparo :check:
•	[x] Sugestões personalizadas :check:
•	[x] Chat mais natural :check:
•	[x] Analytics de conversação :check:
________________________________________
FASE 6: OFFLINE E SINCRONIZAÇÃO (Mês 11)
Objetivo: Sistema resiliente offline
Sprint 21-22: Sistema Offline (4 semanas)
Semana 41-42: Funcionalidade Offline
Funcionalidades:
•	[x] Cache local (IndexedDB) :check:
•	[x] Fila de sincronização :check:
•	[x] Detecção de conectividade :check:
•	[x] Modo offline completo :check:
PWA Avançado:
•	[x] Service Workers :check:
•	[x] Cache de assets :check:
•	[x] Background sync :check:
Semana 43-44: Sincronização
Funcionalidades:
•	[x] Sync automática :check:
•	[x] Resolução de conflitos :check:
•	[x] Retry inteligente :check:
•	[x] Status de sincronização :check:
________________________________________
FASE 7: POLIMENTO E LANÇAMENTO (Mês 12)
Objetivo: Finalizar e lançar
Sprint 23-24: Testes e Refinamentos (4 semanas)
Semana 45-46: Testes Completos
Atividades:
•	[x] Testes de integração :check:
•	[x] Testes de carga :check:
•	[x] Testes de usabilidade :check:
•	[x] Bug fixes :check:
Semana 47-48: Deploy e Treinamento
Atividades:
•	[x] Deploy produção :check:
•	[x] Monitoramento :check:
•	[x] Treinamento da equipe :check:
•	[x] Documentação :check:


