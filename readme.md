# Currículo "Old School" - Estruturação Semântica

Este projeto é um exercício fundamental de **HTML5 puro**, onde o objetivo foi transpor uma estrutura de currículo profissional para a web. O foco principal foi a utilização de tags semânticas para garantir que o conteúdo seja compreensível tanto para humanos quanto para máquinas (SEO e acessibilidade).

O projeto reflete minha transição do hardware para o desenvolvimento de software Fullstack, priorizando uma estrutura limpa e funcional.

## O que foi praticado

Neste projeto, a organização do código foi pensada para refletir a hierarquia de um documento profissional:

### Organização e Fluxo

- **Agrupamento Semântico:** Uso da tag `<section>` para separar logicamente os blocos de Apresentação, Habilidades e Educação.
- **Divisões de Bloco:** Utilização de `<div>` para organizar elementos específicos dentro do cabeçalho, como o nome e as informações de contato.
- **Comentários de Código:** Prática de documentação interna usando `` para marcar seções em desenvolvimento (como a área de Projetos).

### Conteúdo e Tipografia

- **Hierarquia Visual:** Aplicação de `<h1>` para o nome principal e `<h2>` para os títulos das seções.
- **Tratamento de Texto:** Uso de parágrafos `<p>` para descrições e a tag `<b>` para dar ênfase visual a rótulos de tecnologias e idiomas.
- **Listas de Dados:** Estruturação de competências técnicas através de listas não ordenadas `<ul>` e itens de lista `<li>`.

---

## Cola: Tags Utilizadas

| Tag                      | Função no Projeto                                             | Exemplo de Uso                |
| :----------------------- | :------------------------------------------------------------ | :---------------------------- |
| `<!DOCTYPE html>`        | Declara o documento como HTML5.                               | Topo do arquivo.              |
| `<html lang="pt-BR">`    | Define o idioma principal da página.                          | Tag raiz.                     |
| `<meta charset="UTF-8">` | Garante a exibição correta de caracteres especiais e acentos. | Dentro do `<head>`.           |
| `<section>`              | Define seções genéricas de conteúdo relacionado.              | Blocos de "Educação".         |
| `<h1>` / `<h2>`          | Define a importância dos títulos (hierarquia).                | Nome e títulos de seções.     |
| `<p>`                    | Define um parágrafo de texto simples.                         | Descrição da apresentação.    |
| `<a>`                    | Cria hiperlinks para endereços externos.                      | Links para GitHub e LinkedIn. |
| `<ul>`                   | Cria uma lista não ordenada (com marcadores).                 | Agrupamento de habilidades.   |
| `<li>`                   | Define um item individual dentro de uma lista.                | Cada categoria de tecnologia. |
| `<b>`                    | Aplica negrito ao texto para destaque visual.                 | Rótulos como "**Idiomas:**".  |

---

## Aprendizados

A construção deste currículo reforçou a ideia de que o **HTML é o alicerce**. Através dele:

- Entendi a importância do atributo `lang` e das metas de `viewport` para a renderização correta.
- Pratiquei a lógica de "aninhamento" (tags dentro de tags), fundamental para a construção de interfaces.
- Percebi como a escolha correta das tags (como usar `<section>` em vez de apenas `<div>`) torna o código muito mais semântico e legível.

## Projeto inspirado em: https://roadmap.sh/projects/single-page-cv
