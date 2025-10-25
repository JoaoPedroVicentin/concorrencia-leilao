# **Concorrência - Leilão**




## **Pré-requisitos**

Certifique-se de ter as seguintes ferramentas instaladas:

- **Docker** e **Docker Compose**
- **cURL** ou outra ferramenta para testar APIs (como Postman)

---

## **Como Rodar a Aplicação**

```bash
## 1. Clone o Repositório
git clone https://github.com/JoaoPedroVicentin/concorrencia-leilao.git

## 2. Suba o compose 
docker-compose up -d

## 3. Execute o teste
go test ./internal/infra/database/auction -run '^TestCreateAuction_GoroutineUpdatesStatus$' -v
```
