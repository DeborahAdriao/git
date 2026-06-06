# Entendendo o Git: O Guia Inicial

## O que é o Git?
O **Git** é um sistema de controle de versão distribuído, gratuito e de código aberto. Ele foi criado por Linus Torvalds (o mesmo criador do Linux). Cada diretório de trabalho do Git é um repositório com um histórico completo e habilidade total de acompanhamento das revisões, não dependente de acesso a uma rede ou a um servidor central. O Git também facilita a reprodutibilidade científica em uma ampla gama de disciplinas, da ecologia à bioinformática, arqueologia à zoologia.

Na prática, o Git monitora as alterações feitas em arquivos, permitindo que você salve o histórico do seu trabalho. Se algo der errado ou um bug misterioso aparecer, você pode facilmente reverter o código para uma versão anterior que estava funcionando perfeitamente.

---

## Por que usar o Git?
Se você programa, o Git não é apenas uma ferramenta útil; ele é essencial. Aqui estão os principais motivos para usá-lo:

* **Histórico Completo e Seguro:** Você nunca mais vai precisar salvar pastas como `projeto_final`, `projeto_final_v2` ou `projeto_agora_vai`. Cada alteração (commit) gera um ponto na história do projeto.
* **Trabalho em Equipe (Branches):** Várias pessoas podem trabalhar no mesmo código simultaneamente sem apagar o progresso uma da outra. É possível criar ramificações (*branches*) para testar novas funcionalidades de forma isolada.
* **Rastreabilidade:** É fácil descobrir *quem* alterou o quê, *quando* alterou e *por que* alterou.
* **Integração com o GitHub:** Permite que você hospede seu código na nuvem, compartilhe seus projetos com o mundo e construa seu portfólio profissional.

---

## Como abrir o terminal no seu computador
Para começar a usar os comandos do Git, o primeiro passo é saber onde digitá-los. Veja como abrir o terminal nos principais sistemas operacionais:

### No Windows
Você tem duas opções principais no Windows:

1.  **Git Bash (Recomendado):** Se você já instalou o Git, ele vem com o Git Bash, que simula o terminal Linux.
    * Pressione a tecla `Windows`, digite **Git Bash** e aperte `Enter`.
    * *Dica:* Você também pode clicar com o botão direito em qualquer pasta e selecionar **"Git Bash Here"**.
2.  **Prompt de Comando (CMD) ou PowerShell:**
    * Pressione as teclas `Windows + R`, digite `cmd` (ou `powershell`) e aperte `Enter`.

### No macOS (Mac)
No ecossistema Apple, o processo é bem direto:

1.  **Pelo Spotlight:**
    * Pressione as teclas `Command (⌘) + Barra de Espaço` para abrir a busca do Spotlight.
    * Digite **Terminal** e pressione `Enter`.
2.  **Pelo Finder:**
    * Abra o Finder, vá para a pasta **Aplicativos** > subpasta **Utilitários** e dê um duplo clique em **Terminal**.
