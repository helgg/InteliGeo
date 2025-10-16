## 🚀 InteliGeo — Inteligência Geográfica Aplicada à Logística

O **InteliGeo** é um projeto desenvolvido em Python que utiliza **Machine Learning (K-Means)** e o **Método do Cotovelo (Elbow Method)** para identificar regiões ideais para instalação de **Centros de Distribuição (CDs)** com base em **coordenadas geográficas de falhas de entrega**.

---

### 🧠 Conceitos-Chave

- **K-Means Clustering:** algoritmo não supervisionado que agrupa pontos com base na proximidade, minimizando a distância entre os dados e seus respectivos centros.
- **Método do Cotovelo:** técnica para determinar o número ideal de clusters analisando a taxa de redução da inércia (WCSS) à medida que o número de clusters aumenta.
- **Geolocalização:** aplicação de coordenadas de latitude e longitude para análise espacial de padrões de entrega.

Esses conceitos permitem identificar agrupamentos de falhas e propor locais estratégicos para novos centros de distribuição — reduzindo custos e otimizando rotas.

---

### ⚙️ Instalação e Dependências

Clone o repositório:

```bash
git clone https://github.com/helgg/InteliGeo.git
cd InteliGeo
```

Crie e ative um ambiente virtual (opcional, mas recomendado):

```bash
python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows
```

Instale as bibliotecas necessárias:

```bash
pip install pandas scikit-learn matplotlib   # libs principais
pip install -r requirements.txt              # recomendado   
```
