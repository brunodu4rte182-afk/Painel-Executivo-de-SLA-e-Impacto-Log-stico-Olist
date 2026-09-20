# Painel-Executivo-de-SLA-e-Impacto-Log-stico-Olist

📊 Olist Logistics Executive Dashboard
🚀 Visão Geral do Projeto
Este projeto consiste no desenvolvimento de um Dashboard Logístico Executivo de alta performance utilizando dados públicos da Olist no Power BI. O objetivo principal foi ir além dos relatórios tradicionais, entregando uma ferramenta com estética corporativa sênior (Dark Mode) e foco total na tomada de decisão estratégica e análise de gargalos logísticos.

🛠️ Arquitetura e Modelagem de Dados
Fonte de Dados: Base relacional Olist armazenada em SQLite, consultada via ODBC.

Modelagem: Estruturada em Star Schema (Esquema Estrela) para garantir máxima performance de processamento, otimização de relacionamentos e integridade analítica nas consultas DAX.

Camadas: Separação clara entre tabelas fato (pedidos, itens) e dimensões (clientes, produtos, vendedores, tempo).

📈 Principais KPIs e Métricas de Negócio
O painel foi construído para monitorar de perto a eficiência operacional da cadeia logística:

Volume Total de Pedidos e Faturamento: Acompanhamento macro do volume de vendas.

Taxa de Atraso (SLA): Monitoramento rigoroso do cumprimento de prazos de entrega em comparativo com a data estimada.

Volumetria Financeira sob Risco: Análise do faturamento impactado por atrasos logísticos (valor_item).

Gargalos por Estado/Região: Identificação visual rápida de quais localidades concentram os maiores problemas de entrega.

🎨 Experiência do Usuário (UI/UX Design)
Pensado para se destacar em portfólios profissionais, o projeto adota uma identidade visual moderna e imersiva:

Dark Mode Executivo: Fundo em tons de chumbo/antracite profundo para reduzir a fadiga visual e destacar os dados.

Blocos Flutuantes: Cartões e gráficos estruturados como elementos flutuantes com sombras suaves e bordas arredondadas.

Tipografia e Cores de Destaque: Uso intencional de cores brilhantes (branco e tons claros) apenas para valores críticos e métricas principais, simulando um painel de controle corporativo (Command Center).
