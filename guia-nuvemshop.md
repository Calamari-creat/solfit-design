# Guia de Aplicação — SolFit (Design Base Nuvemshop)

Objetivo: usar `loja-praia-academia/index.html` como referência visual e aplicá-lo no tema da loja em **Nuvemshop / Nuvem Commerce** com o custo mínimo possível (tema grátis + ajustes nativos, sem código).

---

## 1. Identidade visual (copie no editor de tema)

No painel da Nuvemshop: **Loja online → Layout → Personalizar tema atual → Cores e Fontes**.

### Paleta
| Uso | Hex | Onde usar |
|---|---|---|
| Verde profundo | `#064E3B` | Rodapé, blocos institucionais, botão secundário |
| Verde principal | `#059669` | Detalhes, links, ícones, foco |
| Verde escuro (hover/texto) | `#047857` | Hover de links e botões verdes |
| Verde claro | `#10B981` | Badge "Novidade" |
| Laranja (CTA principal) | `#EA580C` | Botão "Comprar/Adicionar", ofertas, destaques |
| Fundo geral | `#ECFDF5` | Fundo da página |
| Fundo dos cards | `#FFFFFF` | Cards de produto, seções |
| Texto principal | `#06342B` | Títulos e textos |
| Texto secundário | `#47565F` | Descrições, parcelamento |
| Bordas | `#A7F3D0` | Divisores, contornos suaves |
| Promoções | `#DC2626` | Badge de desconto, erro |

> Regra simples: **verde = confiança/navegação**, **laranja = ação (compra)**. Laranja aparece sempre que você quer o clique.

### Tipografia (Google Fonts, gratuitas)
- **Títulos:** Barlow Condensed (600–800), UPPERCASE
- **Corpo:** Barlow (400/500/600)
- Tamanho base do corpo: 16px · Títulos grandes: 44–76px · Botões: 17px em Barlow Condensed

---

## 2. Estrutura da home (monte nesta ordem)

1. **Barra de anúncio** (Nuvemshop: "Barra de anúncio / Announcement bar"): "Frete GRÁTIS acima de R$199 · Até 12x sem juros · 10% OFF no Pix"
2. **Cabeçalho sticky**: logo à esquerda, menu central (Praia e Academia com destaque em pill), busca + conta + carrinho à direita
3. **Hero**: frase grande de impacto ("Do mar ao treino, vista sua energia") + 2 CTAs (Praia / Academia) + prova social (clientes, nota, parcelamento)
4. **Barra de benefícios**: frete grátis · troca fácil 30 dias · 12x sem juros · compra segura (irem: Características/Destaques do tema)
5. **2 blocos de categoria grandes**: Moda Praia (verde-turquesa) e Academia (grafite) — amplie com o campo "imagem de categoria"
6. **Destaques da semana**: grade de produtos (4 colunas desktop / 2 mobile) com filtros por coleção
7. **Banner de cupom**: adquira o e-mail + cupom `SOL40` com borda tracejada
8. **Depoimentos**: 3 avaliações com estrelas e "compra verificada"
9. **Newsletter**: formulário no bloco verde profundo + 10% OFF
10. **Rodapé**: 4 colunas + chips de pagamento (Pix, Boleto, Visa, Master, Elo) + CNPJ

---

## 3. Regras de produto (gere confiança e conversão)

- **Badge de status** (Nuvemshop já gera): "Novidade" verde, "-20%" vermelho, "Últimas peças" branco com borda laranja
- **Preço**: preço cheio riscado + preço à vista no **Pix** (destaque verde) + "12x de R$ X sem juros"
- **Botão "Adicionar ao carrinho"** que aparece ao passar o mouse (nativo na maioria dos temas: "Mostrar ação rápida / Quick shop")
- **Fotos**: 3/4 (proporção 3:4), fundo neutro claro. Troque os gradiente do mockup por fotos reais dos produtos
- **Nome do produto curto** (máx. ~35 caracteres) + categoria em mini-maiúsculas acima do nome

---

## 4. Configurações da plataforma (importante, não pule)

- **Envio**: ative **Correios + transportadoras via Melhor Envio**, configure região de frete grátis ≥ R$199
- **Pagamentos**: adicione **Pix, Boleto e Cartão**; configure até 12x sem juros (o minimo é seu diferencial)
- **Apps gratuitos que valem a pena** (orçamento baixo): avaliações de clientes, pop-up de newsletter com cupom, WhatsApp flutuante
- **Páginas institucionais**: Trocas, Prazos, Política de Privacidade e Tabela de Medidas (reduz perguntas e reembolsos)
- **SEO básico**: título paginas "SolFit — Moda Praia & Roupas de Academia", meta description com "frete grátis" e "12x sem juros"

---

## 5. Checklist de lançamento

- [ ] Logo aplicada (o "S" do mockup é placeholder — substituir pela logo real do cliente)
- [ ] Fotos reais dos produtos (mesma proporção 3:4 e mesmo fundo)
- [ ] Barra de anúncio com frete/parcelamento reais
- [ ] Cupom `SOL40` criado em **Promoções** (40% na 1ª compra ou ajuste conforme margem)
- [ ] Depoimentos reais (peça 3 a 5 primeiros clientes ou use verificador de apps)
- [ ] WhatsApp flutuante com número real do cliente
- [ ] Teste no celular (375px) : menu, botão de carrinho e checkout funcionando
- [ ] Fazer uma compra de teste completa (Pix + cartão)

---

## 6. Responsividade incluída no mockup

- ≤1024px: produtos em 3 colunas
- ≤768px: menu colapsado, produtos em 2 colunas, hero empilhado
- ≤420px: produtos em 1 coluna
- Suporte a `prefers-reduced-motion` e foco visível de teclado (acessibilidade)

Arquivo de referência: `loja-praia-academia/index.html` (abra no navegador).

Design system completo salvo em: `design-system/loja-praia-academia/MASTER.md`
