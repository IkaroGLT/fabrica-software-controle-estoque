# Fábrica de Software — MVP de Controle de Estoque

## Etapa 7 — RF06 Indicadores / Dashboard

Nesta versão, o MVP permite:

- cadastrar produtos;
- registrar entradas;
- registrar saídas;
- consultar o saldo atual;
- visualizar o histórico;
- visualizar indicadores e gráficos do estoque.

Indicadores apresentados:

- quantidade de produtos cadastrados;
- total de unidades em estoque;
- total de entradas registradas;
- total de saídas registradas.

Gráficos:

- quantidade atual por produto;
- quantidade movimentada por tipo.

## Importante

Mantenha o seu arquivo `estoque.db` atual.

Substitua somente:

- `app.py`
- `database.py`

## Como executar

```powershell
python -m streamlit run app.py
```
