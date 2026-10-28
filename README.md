> **Projeto da aula ao vivo (28/10/2026).** Começa no ponto de partida (site, blog e painel do blog) e ganha o postador do Instagram sprint a sprint.
> Projeto de referência completo: https://github.com/matheusborguete/himal-cafe

# Himal Café

Site da **Himal**, com cafés especiais do Nepal, mais um blog e uma área logada para publicar posts.
É o projeto prático da aula **Automação com IA**.

🔗 https://himal-ao-vivo.web.app · [Blog](https://himal-ao-vivo.web.app/blog/)

## O que tem aqui

- **Landing page** do Kit Trilogia Himal
- **Blog**, que lê os posts do Firestore
- **Painel** (`/admin`): login, colar o texto gerado pela IA, foto e **Publicar**

Roda 100% no plano gratuito do Firebase (Hosting + Auth + Firestore), sem cartão de crédito.

## Fluxo semiautomático da aula

1. Um **agendado** no Claude (ou no ChatGPT) escreve um post por dia sobre café especial.
2. Você abre `/admin`, cola a resposta e escolhe a foto.
3. Clique em **Publicar**: o post vai ao ar no blog.

## Quer a sua própria cópia?

Abra este repositório no **Claude Code** e peça:

> Siga o CLAUDE.md e crie a minha cópia deste projeto no meu Google Cloud.

O passo a passo completo está no [CLAUDE.md](CLAUDE.md).
