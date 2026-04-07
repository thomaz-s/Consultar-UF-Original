# Consulta de Origem de Placas de Veículos

Este aplicativo consulta o local onde um veículo foi originalmente emplacado, com base nas letras iniciais da placa.
Está publicado no [Pages](https://thomaz-s.github.io/Consultar-UF-Original/).

👉 A fonte dos dados é o artigo da [Wikipédia](https://pt.wikipedia.org/wiki/Placas_de_identificação_de_veículos_no_Brasil#Distribuição_de_sequências_por_ordem_alfabética) sobre as placas no Brasil

Sempre que há alguma atualização na fonte, é necessário atualizar manualmente os dados na constante `sequencias`.

---

## 🚀 Como utilizar

1. Digite **apenas os três primeiros caracteres da placa**
2. Clique no botão **Consultar** ou pressione **Enter**
3. O resultado aparecerá logo abaixo

📌 Ao realizar novas consultas, também será exibido o **histórico das 5 últimas consultas**.

---

## ⚠️ Observações

* O resultado indica **apenas o estado onde o veículo foi originalmente emplacado**.
  Isso significa que, mesmo que o veículo tenha sido vendido ou transferido para outro estado, a placa permanece a mesma.

  **Exemplo:**
  Um veículo com placa iniciando em **HTX** foi emplacado no Ceará.
  Mesmo que seja transferido para um novo proprietário no Maranhão, a placa continuará **HTX**, e a consulta indicará **Ceará**.

---

### 🔁 Troca de placa por clonagem

Existe a possibilidade de um veículo ter sua placa alterada após a comprovação de clonagem.

Seguindo o exemplo anterior:

* Um veículo com placa iniciando em **HTX** (Ceará) foi clonado
* O Detran do estado atual (ex: Maranhão) pode autorizar um novo emplacamento
* Nesse caso, o veículo receberá uma nova sequência do Maranhão, como **ROD**

---

### 🚗 Veículos antigos

Veículos muito antigos, que ainda utilizavam placas de **duas letras** (modelo abolido no início da década de 1990), podem apresentar inconsistências:

* Caso tenham sido reemplacados em outro estado
* Receberão uma sequência correspondente **à nova UF**, e não à original

---

### 💰 Escolha personalizada de placas

Alguns estados permitem que o proprietário escolha a sequência da placa mediante pagamento de taxa adicional.

> Não há confirmação se é possível escolher sequências de outro estado nesses casos.

---

### 🧩 Caso específico: sequência SAV

* A sequência **SAV** está oficialmente atribuída ao **Ceará**
* Porém, por volta de **2009**, alguns veículos em **São Paulo** foram emplacados com essa sequência
* O motivo não é conhecido
* A maioria dos veículos com essa sequência foi registrada no Ceará em **2022**

---

## 📌 Resumo

Este sistema é útil para identificar a **origem inicial do veículo**, mas não necessariamente reflete sua localização atual ou histórico completo de propriedade.
