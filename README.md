# FLORAÉ Boutique

Protótipo de e-commerce de moda feminina — **Holambra, SP**.

> *Floresça no seu estilo.*

## Sobre

Curadoria de peças leves, femininas e atuais, em poucas unidades.  
Checkout via **WhatsApp**. Design minimalista com a identidade visual da marca (paleta cream / sage / dusty rose / gold).

## Produtos (v1)

| Produto | Preço | Descrição |
|---------|-------|-----------|
| Vestido Linho Rosa | R$ 279 | Midi em linho dusty pink |
| Macacão Sage | R$ 329 | Linho sage, pernas amplas |
| Vestido Linho Off-White | R$ 249 | Silhueta clean |
| Conjunto Linho Cream | R$ 359 | Camisa + calça |
| Vestido Renda Off-White | R$ 319 | Longo, delicado |
| Vestido Linho Natural | R$ 269 | Caimento fluido |

Imagens livres de uso comercial, alinhadas às descrições.

## Demo

**Produção:** [florae-boutique.vercel.app](https://florae-boutique.vercel.app)

## Estrutura

```
florae-boutique/
├── index.html              # Página única (HTML + Tailwind CDN)
├── assets/images/          # Fotos dos produtos
├── .github/workflows/
│   └── deploy.yml          # CI/CD → Vercel
├── vercel.json
└── README.md
```

## Stack

- HTML5 + Tailwind CSS (CDN)
- JavaScript vanilla (carrinho + WhatsApp)
- Deploy estático na **Vercel**
- CI/CD via **GitHub Actions**

## Desenvolvimento local

```bash
npx serve .
# ou
python3 -m http.server 3000
```

## Deploy (CI/CD)

A cada push na branch `main`:

1. GitHub Actions executa o workflow
2. Vercel recebe o deploy de produção

### Secrets necessários (GitHub → Settings → Secrets)

| Secret | Onde obter |
|--------|------------|
| `VERCEL_TOKEN` | [vercel.com/account/tokens](https://vercel.com/account/tokens) |
| `VERCEL_ORG_ID` | `.vercel/project.json` ou dashboard |
| `VERCEL_PROJECT_ID` | `.vercel/project.json` ou dashboard |

## Identidade

- **Cream** `#F7F4EF`
- **Sage** `#7D8F74`
- **Dusty** `#D9A7A1`
- **Gold** `#C9B27B`

## Licença

Protótipo privado / demonstração. Imagens de uso livre (referência comercial).

---

Feito com carinho para a FLORAÉ • Holambra – SP
