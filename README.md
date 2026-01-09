# BABYHAPPY_V1
VERSÃO 1.0.0

👶 BabyHappy (v1.0) O BabyHappy é uma plataforma desenvolvida para ligar pais e babysitters de forma eficiente e segura. Esta primeira versão foca-se na comunicação direta e na transparência de atividade dos utilizadores através de um sistema de chat robusto.

🚀 Funcionalidades Principais Autenticação de Utilizadores: Perfis distintos para Pais e Babysitters.

Chat em Tempo Real:

Troca de mensagens assíncronas (sem recarregar a página).

Gestão de histórico e conversas ativas.

Possibilidade de apagar mensagens individuais e conversas completas.

Sistema de Presença (Heartbeat):

Status Online: Indicador visual pulsante quando o utilizador está ativo.

Última Atividade: Registo de "Visto por último" para utilizadores offline.

Edição de Perfil: Upload de foto de perfil e gestão de dados profissionais (preço/hora, experiência, localização).

🛠️ Tecnologias Utilizadas

Frontend: HTML5, CSS3 (Design Responsivo), JavaScript (Vanilla JS).

Backend: PHP 8.x.

Base de Dados: MySQL.

Comunicação: Fetch API / AJAX para interações em tempo real.

⚙️ Configuração Local

Clonar o repositório:

Bash

git clone https://github.com/carlinhostato/babyhappy.git

Preparar o Ambiente:

Mover a pasta para o diretório do seu servidor local (ex: htdocs no XAMPP).

Importar o ficheiro SQL da base de dados fornecido.

Configurar a Base de Dados:

Editar o ficheiro backend/config/database.php com as suas credenciais locais.

Aceder:

Abrir http://localhost/babyhappy_v1/login.html no navegador.

📡 Arquitetura Técnica do Chat O sistema utiliza um mecanismo de Heartbeat onde o cliente (browser) envia um pulso de atividade ao servidor a cada 25 segundos. O servidor compara este timestamp para determinar se o parceiro de conversa está online (diferença < 60s) ou offline.

📄 Licença Este projeto está sob a licença MIT.👶 BabyHappy (v1.0) O BabyHappy é uma plataforma desenvolvida para ligar pais e babysitters de forma eficiente e segura. Esta primeira versão foca-se na comunicação direta e na transparência de atividade dos utilizadores através de um sistema de chat robusto.

🚀 Funcionalidades Principais Autenticação de Utilizadores: Perfis distintos para Pais e Babysitters.

Chat em Tempo Real:

Troca de mensagens assíncronas (sem recarregar a página).

Gestão de histórico e conversas ativas.

Possibilidade de apagar mensagens individuais e conversas completas.

Sistema de Presença (Heartbeat):

Status Online: Indicador visual pulsante quando o utilizador está ativo.

Última Atividade: Registo de "Visto por último" para utilizadores offline.

Edição de Perfil: Upload de foto de perfil e gestão de dados profissionais (preço/hora, experiência, localização).

🛠️ Tecnologias Utilizadas

Frontend: HTML5, CSS3 (Design Responsivo), JavaScript (Vanilla JS).

Backend: PHP 8.x.

Base de Dados: MySQL.

Comunicação: Fetch API / AJAX para interações em tempo real.

⚙️ Configuração Local

Clonar o repositório:

Bash

git clone https://github.com/carlinhostato/babyhappy.git

Preparar o Ambiente:

Mover a pasta para o diretório do seu servidor local (ex: htdocs no XAMPP).

Importar o ficheiro SQL da base de dados fornecido.

Configurar a Base de Dados:

Editar o ficheiro backend/config/database.php com as suas credenciais locais.

Aceder:

Abrir http://localhost/babyhappy_v1/login.html no navegador.

📡 Arquitetura Técnica do Chat O sistema utiliza um mecanismo de Heartbeat onde o cliente (browser) envia um pulso de atividade ao servidor a cada 25 segundos. O servidor compara este timestamp para determinar se o parceiro de conversa está online (diferença < 60s) ou offline.

📄 Licença Este projeto está sob a licença MIT.
