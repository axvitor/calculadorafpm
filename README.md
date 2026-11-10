# Calculadora de Preço FPM

Calculadora de preço de venda para produtos vendidos na Nuvemshop com pagamento pela Pagar.me.

Abra `calculadora.html` no navegador. Não precisa de instalação.

## Campos
- Produto: escolher um produto da lista preenche o custo de produção e a caixa (a lista fica na constante `PRODUTOS` em `calculadora.html`; "Outro" deixa digitar o custo)
- Custo de produção
- Caixa (R$ 1,50, R$ 3,00 ou R$ 9,00)
- Margem ideal (%): automática por padrão, com lucro igual ao custo de produção; pode ser trocada
- Valor de venda (digitado ou pela barra deslizante)

## Custos considerados
Sobre o valor de venda:

| Item | Valor |
|---|---|
| Nuvemshop | 1% |
| Pagar.me (cartão à vista) | 4,28% |
| Anúncio | 20% |
| Imposto | 8,64% |
| Custos fixos | 20% |

Fixos por venda:

| Item | Valor |
|---|---|
| Pagar.me: processamento | R$ 0,20 |
| Pagar.me: antifraude do cartão | R$ 0,20 |
| Brindes e embalagem (além da caixa) | R$ 4,00 |

Lucro = venda − produto − caixa − R$ 4,00 − R$ 0,40 − 53,92% da venda
Preço mínimo (lucro zero) = (produto + caixa + 4,40) ÷ 0,4608
Preço para a margem M = (produto + caixa + 4,40) ÷ (0,4608 − M)
