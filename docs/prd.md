# 📋 Product Requirements Document (PRD) - AnimeChecklist

## 1. Visão Geral e Objetivo

O **AnimeChecklist** é uma aplicação web desenvolvida para ajudar fãs de anime a organizar, acompanhar e registrar os animes que desejam assistir, estão assistindo ou já concluíram.

**O grande diferencial (Regra de Negócio Principal):** o sistema funciona como uma checklist personalizada, permitindo que o usuário altere o status de cada anime e acompanhe seu progresso, mantendo sua lista organizada e evitando esquecer episódios ou animes que pretende assistir.

O objetivo é criar uma experiência simples, visual e prática para qualquer pessoa que queira administrar sua jornada pelo mundo dos animes.

## 2. Atores do Sistema

* **Visitante:** Usuário não autenticado que acessa a página inicial e pode visualizar informações sobre a plataforma e os animes disponíveis.
* **Usuário:** Pessoa que utiliza o sistema para criar e gerenciar sua própria lista de animes.
* **Sistema:** Responsável por armazenar as informações, atualizar os status dos animes e calcular o progresso da checklist.

## 3. Histórias de Usuário e Escopo

Abaixo estão as funcionalidades principais do MVP (*Minimum Viable Product*), escritas sob a perspectiva do usuário final.

### 👤 Épico 1: Cadastro e Acesso

* **US01 - Criação de Perfil:** Como um Visitante, quero criar um perfil informando meus dados básicos para poder salvar minha checklist de animes.

  * *Critérios de Aceitação:* Todos os campos obrigatórios devem ser preenchidos corretamente e o usuário deve possuir uma lista vazia ao criar sua conta.

* **US02 - Acesso ao Sistema:** Como um Usuário, quero realizar login utilizando minhas credenciais para acessar minha lista pessoal de animes.

### 📺 Épico 2: Gerenciamento de Animes

* **US03 - Adicionar Anime à Checklist:** Como um Usuário, quero adicionar um anime à minha lista para registrar que desejo assisti-lo.

  * *Critérios de Aceitação:* O anime deve possuir pelo menos título, gênero e quantidade de episódios.

* **US04 - Alterar Status do Anime:** Como um Usuário, quero definir o status de cada anime para organizar o que estou assistindo.

  * *Status disponíveis:*

    * **Quero assistir**
    * **Assistindo**
    * **Concluído**
    * **Pausado**

* **US05 - Marcar Anime como Concluído:** Como um Usuário, quero marcar um anime como concluído após terminar de assisti-lo.

  * *Critérios de Aceitação:* O anime deve ser movido para a categoria de concluídos e atualizar automaticamente o progresso geral da checklist.

### 🔎 Épico 3: Organização e Busca

* **US08 - Pesquisar Anime:** Como um Usuário, quero pesquisar um anime pelo nome para encontrá-lo rapidamente na minha checklist.

* **US09 - Filtrar por Status:** Como um Usuário, quero filtrar os animes pelo status para visualizar apenas aqueles que quero assistir, estou assistindo, pausei ou concluí.

* **US10 - Remover Anime:** Como um Usuário, quero remover um anime da minha checklist caso não tenha mais interesse em assisti-lo.

  * *Critérios de Aceitação:* O sistema deve solicitar uma confirmação antes de excluir o anime da lista.

