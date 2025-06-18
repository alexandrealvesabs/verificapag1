# verificapag1
# 💳 Verificador e Autenticador de Boletos Bancários

Este projeto apresenta uma API que valida e autentica boletos bancários de forma segura e eficaz, utilizando regras oficiais de validação de dígitos verificadores com **módulo 10 e 11**.

---

## 🚀 Objetivos

- Validar boletos de cobrança (47 dígitos) e arrecadação (48 dígitos)
- Verificar autenticidade da linha digitável e código de barras
- Garantir integridade dos dados com algoritmos oficiais
- Expor um endpoint HTTP para consumo de aplicações web

---

## 🧪 Como funciona?

A API recebe um boleto em formato de linha digitável e retorna:

```json
{
  "boleto_valido": true,
  "valor": "150.00",
  "vencimento": "2025-08-12"
}
