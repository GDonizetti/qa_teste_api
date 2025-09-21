# qa_teste_api
Atividades de QA realizadas no Projeto Integrador 2 (PI2) da Univesp, com foco em testes funcionais, validação de API e documentação de erros e correções no sistema de estoque.

--

# API de Estoque (Projeto Integrador)

Este projeto é uma API desenvolvida em **Flask** para gerenciamento de produtos.  
Ela foi criada como parte do Projeto Integrador da UNIVESP e implementa operações básicas de CRUD (Create, Read, Update, Delete).

---

## 🚀 Tecnologias utilizadas
- Python 3
- Flask
- SQLite
- Postman (para testes)

---

## ⚙️ Como rodar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repo.git

--

Acesse a pasta do projeto.

cd seu-repo

--

Instale as dependências:

pip install -r requirements.txt


Execute o servidor:

python app.py


A API ficará disponível em:

http://localhost:5000

❌ Testes com falha
Teste DELETE (remover produto)

Resposta:

{
  "erro": "Produto não encontrado"
}


Status: 404 Not Found

Teste PUT (atualizar produto inexistente)

Resposta:

{
  "erro": "Produto não encontrado"
}


Status: 404 Not Found

📌 Observação: Esses erros são esperados em uma API em desenvolvimento. Mostram que o tratamento para produtos inexistentes ainda precisa ser melhorado.

✅ Testes bem-sucedidos
Teste GET (status da API)

Resposta:

{
  "endpoints": ["/login", "/logout", "/produtos"],
  "status": "API Flask funcionando!"
}

Teste POST (adicionar produto)

Resposta:

{
  "mensagem": "Produto adicionado com sucesso"
}

Teste POST (login)

Resposta:

{
  "mensagem": "Login realizado com sucesso"
}

Teste PUT (atualizar produto existente)

Resposta:

{
  "mensagem": "Produto atualizado com sucesso"
}

📌 Conclusão

Como QA, é fundamental registrar o que falhou e o que passou.

Os testes mostraram que os endpoints básicos (GET, POST, PUT em produto existente) funcionam corretamente.

O endpoint DELETE e o PUT em produto inexistente ainda precisam de ajustes.

👨‍💻 Autor

Gabriel Antonio Donizetti
Estudante de Tecnologia em Informática – UNIVESP


---

Desse jeito você mostra **profissionalismo de QA**: começa pelos erros, dá contexto, depois evidencia os acertos.  

Quer que eu monte também a **versão enxuta para LinkedIn** nesse mesmo espírito? Tipo: “como QA registrei primeiro os erros, depois validei os acertos” — isso chama atenção de recrutadores.
