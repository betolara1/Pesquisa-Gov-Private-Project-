👻 Repo Ghost: Pesquisa Gov (Private Project)
Nota: Este repositório contém a documentação, ativos visuais e especificações técnicas de um projeto privado. O código-fonte original está hospedado em um ambiente restrito por motivos de conformidade e segurança.

📋 Visão Geral
O Pesquisa Gov é um sistema avançado de coleta e análise de dados para gestão pública. Ele foi projetado para permitir que municípios coletem feedbacks de cidadãos de forma georreferenciada e utilizem inteligência artificial para transformar dados brutos em relatórios estratégicos.

📸 Interface do Projeto
(Insira aqui as fotos/mockups que você criou)

🚀 Tecnologias Principais
Core: PHP 7.1+ com arquitetura modular para processamento de requisições.

Database: MySQL para armazenamento estruturado de respostas e perfis demográficos.

AI Integration: Google Gemini API para geração automatizada de relatórios executivos.

Audio Processing: AssemblyAI para transcrição de depoimentos de voz em tempo real.

Geospatial: Leaflet.js e Google Maps API para mapeamento de satisfação por coordenadas.

🛠️ Funcionalidades de Destaque
🧠 IA Strategic Analytics: O sistema processa comentários qualitativos e gera automaticamente conclusões e recomendações baseadas em sentimentos.

🎙️ Voice-to-Text Research: Pesquisadores de campo podem gravar áudios que são automaticamente convertidos em texto para inclusão no banco de dados.

📍 Precision Geocoding: Captura automática de coordenadas (Lat/Long) através do endereço ou CEP, permitindo a criação de mapas de calor de problemas urbanos.

📊 Dynamic Reporting: Geração de PDFs profissionais com gráficos gerados dinamicamente via biblioteca TCPDF.

🏗️ Arquitetura do Sistema
O projeto é composto por diversos módulos integrados:

cadastro.php: Engine de coleta de dados com suporte a hardware (microfone e GPS).

relatorio_resumo_ia.php: Módulo de processamento de linguagem natural (NLP).

mapa.php: Camada de visualização de dados espaciais.
