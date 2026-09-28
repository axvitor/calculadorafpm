# Calculadora de Preço FPM

Calculadora de preço de venda para produtos vendidos na Nuvemshop com pagamento pela Pagar.me.

Abra `calculadora.html` no navegador. Não precisa de instalação.

## Campos
- Custo de produção
- Caixa (R$ 1,50, R$ 3,00 ou R$ 9,00)
- Margem ideal (%)
- Valor de venda (digitado ou pela barra deslizante)

## Custos considerados (sobre o valor de venda)
| Item | Valor |
|---|---|
| Nuvemshop | 2% |
| Pagar.me | 4,28% + R$ 0,20 fixo |
| Anúncio | 20% |
| Imposto | 8,64% |
| Custos fixos | 20% |

Lucro = venda − produto − caixa − R$ 0,20 − 54,92% da venda
Preço mínimo (lucro zero) = (produto + caixa + 0,20) ÷ 0,4508
Preço para a margem M = (produto + caixa + 0,20) ÷ (0,4508 − M)
