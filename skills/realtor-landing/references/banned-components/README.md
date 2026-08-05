# banned-components

Lista de elementos visuais que nunca entram nos sites e plataformas que produzimos.

```
banned-components/
├── list.txt          ← a lista (texto puro, é isto que se lê)
└── components/       ← screenshots de referência
    └── _NOMES-ESPERADOS.txt
```

## Como funciona

O `list.txt` não tem imagens embebidas. Cada elemento banido tem uma linha
`REF: components/nome.png` que aponta para o screenshot correspondente.
Assim o ficheiro fica leve, dá para versionar em git, e a imagem só é
aberta quando alguém precisa mesmo de ver do que se trata.

## Como usar num projeto

Ler o `list.txt` **antes** de escrever a primeira linha de HTML/CSS, e
outra vez **antes** de entregar (a Secção 7 é a checklist de entrega).

## Como alimentar

Novo tique de template detetado → screenshot para `components/` →
entrada nova no `list.txt` com o mesmo formato (TITULO / REF / O QUE É /
PORQUÊ / EM VEZ). Registar o nome novo em `components/_NOMES-ESPERADOS.txt`.

## Onde encaixa

Destino: `imogrow-realtor-kit/skills/realtor-landing/references/banned-components/`
— fica ao lado de `design-system.md` e passa a ser leitura obrigatória
da skill. Como é agnóstico de género, também serve para as skills
`smile-clinic-landing`, `b2b-partners-landing`, `auto-stand-landing` e
`noxe-landing`.
