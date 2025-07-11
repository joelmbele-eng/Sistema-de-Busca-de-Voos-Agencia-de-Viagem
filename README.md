![image alt](https://github.com/joelmbele-eng/Sistema-de-Busca-de-Voos-Agencia-de-Viagem/blob/5317f8bab3a981dfcaa375543693f8b7af1731c2/1.PNG)
# Sistema-de-Busca-de-Voos-Agencia-de-Viagem
Este é um Sistema Completo de Busca de Voos desenvolvido em Python com interface gráfica moderna, projetado para agências de viagem e usuários que precisam consultar informações de voos de forma eficiente e profissional. O sistema integra múltiplas funcionalidades em uma única aplicação desktop robusta e intuitiva.


# Principais Funcionalidades

1. Interface Gráfica Moderna
Interface desenvolvida com CustomTkinter para aparência moderna e responsiva
Layout dividido em três painéis principais para melhor organização
Tema escuro profissional com cores personalizadas
Componentes interativos com feedback visual
2. Busca de Voos em Tempo Real
Integração com a Aviation Stack API para dados atualizados
Busca por código IATA de origem e destino
Exibição de informações detalhadas dos voos:
Número do voo e companhia aérea
Horários de partida e chegada
# Status do voo em tempo real
Aeroportos de origem e destino
![image alt](https://github.com/joelmbele-eng/Sistema-de-Busca-de-Voos-Agencia-de-Viagem/blob/23f4afeb095ccbcc98cc73587228339c8b8ee36c/2.PNG)
3. Base de Dados de Aeroportos
Catálogo abrangente com aeroportos de 5 continentes:
África: Luanda, Joanesburgo, Cairo
Europa: Lisboa, Paris, Londres
Américas: São Paulo, Nova York, Toronto
Ásia: Tóquio, Singapura, Dubai
Oceania: Sydney, Auckland, Nadi
Coordenadas geográficas precisas para cada aeroporto
Interface de seleção rápida com botões de origem/destino
4. Visualização de Rotas
Mapa interativo mostrando a rota entre origem e destino
Representação visual com marcadores coloridos
Cálculo automático de distância aproximada entre aeroportos
Geração de mapas interativos com Folium que abrem no navegador
Canvas personalizado para visualização rápida das rotas
5. Geração de Relatórios PDF
Criação automática de relatórios profissionais em PDF
Informações incluídas:
Tabela completa com todos os voos encontrados
Dados dos aeroportos (nome completo e localização)
Distância calculada entre origem e destino
Data e hora de geração do relatório
Formatação profissional com cores e estilos
6. Visualizador de PDF Integrado
Visualização de relatórios diretamente na aplicação
Controles de zoom (ampliar/reduzir)
Função "Ajustar à Janela" para melhor visualização
Scrollbars para navegação em documentos grandes
Opção para abrir PDFs em visualizador externo
7. Gerenciamento de Relatórios
Lista automática de todos os relatórios gerados
Organização por data de criação (mais recentes primeiro)
Funcionalidades de visualização e exclusão
Armazenamento local organizado em pasta dedicada
8. Processamento Assíncrono
Busca de voos em threads separadas para não bloquear a interface
Indicador de progresso visual durante operações
Interface responsiva mesmo durante operações pesadas
🛠️ Tecnologias Utilizadas
Interface e Experiência do Usuário
CustomTkinter: Interface gráfica moderna e responsiva
PIL (Pillow): Processamento de imagens
Threading: Processamento assíncrono para melhor performance
APIs e Dados
Aviation Stack API: Dados de voos em tempo real
Requests: Comunicação HTTP com APIs
Python-dotenv: Gerenciamento seguro de chaves de API
Geração de Relatórios
ReportLab: Criação de PDFs profissionais com tabelas e formatação
PyMuPDF (Fitz): Visualização e manipulação de PDFs
Mapas e Geolocalização
Folium: Geração de mapas interativos
Cálculos geográficos: Fórmula de Haversine para distâncias
Utilitários
DateTime: Manipulação e formatação de datas
OS/TempFile: Gerenciamento de arquivos e diretórios
Webbrowser: Integração com navegador para mapas interativos
🎯 Vantagens e Diferenciais
1. Solução Completa e Integrada
Todas as funcionalidades necessárias em uma única aplicação
Não requer múltiplas ferramentas ou softwares externos
Interface unificada para todas as operações
2. Interface Profissional e Intuitiva
Design moderno que transmite confiança e profissionalismo
Organização lógica das funcionalidades
Feedback visual claro para todas as ações do usuário
3. Dados Precisos e Atualizados
Integração com API confiável para informações de voos
Base de dados curada com aeroportos principais mundiais
Cálculos geográficos precisos para distâncias
4. Relatórios Profissionais
PDFs com formatação empresarial
Informações completas e bem organizadas
Ideal para apresentação a clientes ou arquivo interno
5. Visualização Geográfica Avançada
Mapas que facilitam a compreensão das rotas
Representação visual clara de origem e destino
Mapas interativos para análise detalhada
6. Performance Otimizada
Interface responsiva mesmo durante operações pesadas
Processamento assíncrono para melhor experiência
Gerenciamento eficiente de memória e recursos
7. Facilidade de Uso
Seleção rápida de aeroportos com botões dedicados
Campos de entrada com placeholders informativos
Operações intuitivas sem necessidade de treinamento extenso
