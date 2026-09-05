# The Inclusionist — árvore de conhecimento

> ## ⚠️ ESTE REPOSITÓRIO ESTÁ VAZIO. O SISTEMA AINDA NÃO FOI CONSTRUÍDO.
>
> Ele existe porque o endereço está **declarado em registro**, e endereço declarado é onde o
> trabalho pode ser arquivado — a regra anterior (criar só no primeiro commit) deixou o backlog de
> seis sistemas no rastreador da engine, parecendo trabalho da engine. Ver **ADR-0067**.
>
> **Esta advertência sai no commit que a desmentir.** README que mente sobre estar vazio é pior do
> que repositório vazio.

## O que é

O **grafo de habilidades** entre currículos de vários países, e o primeiro dono real que a camada de
currículo já teve — ela passou anos pertencendo a uma plataforma que não existia (ADR-0032, ADR-0058 §9).

Entrega-se como **artefato de dado versionado** para o site, a Bússola e a aprendizagem gamificada:
não é biblioteca, não é API.

## Quem responde por ele

**Secretaria de Educação** — parte do sistema Inclusionista.

## O que precisa existir antes do primeiro commit de produto

- O orçamento de bytes do artefato. O ADR-0058 chutou **8 MB comprimidos** por fatia de currículo, e
  ⚠️ **é chute até o artefato existir**: se uma fatia não couber, revisa-se a decisão de mandá-la ao
  aparelho — não se levanta o orçamento em silêncio.
- O pilar 3: currículo se **reescreve** por idioma, não se traduz. O texto pt-BR não entra nos
  dicionários.

## Licença

Código: **AGPL-3.0-or-later** (ADR-0064) — o `LICENSE` desta raiz.
⚠️ **A arte NÃO é AGPL.** Programa é o que a Lei 9.609 define; arte segue a Lei 9.610 e pertence a
quem a fez. O que governa o quê está em `docs/LICENSES.md`, na engine.

⚠️ **A titularidade patrimonial é do MUNICÍPIO** (Lei nº 9.609/1998, art. 4º), não do desenvolvedor.
A publicação do código é objeto de **pedido** no requerimento — ato do Poder Executivo — e por isso
este repositório é **privado** (ADR-0066 §3).

---

Decidido em: **ADR-0058** (topologia) · **ADR-0066** (hospedagem) · **ADR-0067** (criação).
Os registros vivem na engine, em `docs/2-Architecture/adr/` — **não** há pasta `adr/` aqui, e isso é
decisão (ADR-0068 §5): trezentos lugares para decidir arquitetura são trezentos lugares para
contradizer o que já foi decidido, caladamente.
