# Rede Esperança — Plataforma Web para ONG

Projeto acadêmico desenvolvido para demonstrar os fundamentos de HTML5, CSS3 e JavaScript em uma plataforma digital de apoio a uma ONG.

## Primeira entrega

- `index.html`: página institucional e contato;
- `projetos.html`: projetos sociais, voluntariado, doação e transparência;
- `cadastro.html`: formulário complexo com validação nativa e máscaras;
- `css/styles.css`: sistema visual responsivo com abordagem mobile-first;
- `js/script.js`: navegação mobile, contadores, máscaras e interações;
- `assets/images/`: imagens locais em SVG, PNG e WebP.

## Estrutura

```text
ong-plataforma/
├── assets/
│   └── images/
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── cadastro.html
├── index.html
├── projetos.html
└── README.md
```

## Como executar

Abra `index.html` em um navegador ou utilize uma extensão como Live Server no VS Code.

## Validação

Valide as páginas no W3C Nu HTML Checker antes da entrega:
https://validator.w3.org/nu/

Recomenda-se validar `index.html`, `projetos.html` e `cadastro.html` individualmente.

## Acessibilidade implementada

- HTML semântico (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `form`, `fieldset` e `legend`);
- hierarquia de títulos consistente;
- link para pular ao conteúdo;
- labels associados aos controles;
- `aria-current`, `aria-live`, `aria-label` e estados de menu;
- navegação por teclado e foco visível;
- suporte a `prefers-reduced-motion`;
- contraste tratado pelo sistema visual.

## Observação acadêmica

Doações e envio do cadastro são simulações de interface. Não há backend, banco de dados ou processamento financeiro real nesta primeira entrega.
