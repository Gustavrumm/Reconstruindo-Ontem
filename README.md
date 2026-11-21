# Reconstruindo Ontem — Sistema de Registro de Lembranças

## Integrantes do Grupo
* **Maria Augusta Campanha Lima**
* **Lucas Thiago da Silva Martins**
* **Gustavo Silva Fogaça**

## Tema Escolhido
Aplicação web para registro, consulta, edição e exclusão de lembranças pessoais (**Mural de Lembranças**), desenvolvida com Node.js, Express, EJS e banco de dados MySQL.

## Como Instalar e Executar

1. Clone o repositório e entre na pasta:
   ```bash
   git clone https://github.com/Gustavrumm/Reconstruindo-Ontem.git
   cd Reconstruindo-Ontem
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Execute o arquivo `script.sql` no MySQL Workbench ou terminal MySQL para criar o banco `ReconstruindoOntem`, a tabela `SuaLembranca` e os 3 registros iniciais.

4. Crie um arquivo `.env` na raiz do projeto baseado no `.env.example` e coloque sua senha do MySQL:
   ```env
   DB_HOST=localhost
   DB_USER=root
   DB_PASSWORD=sua_senha
   DB_NAME=ReconstruindoOntem
   ```

5. Inicie o servidor:
   ```bash
   npm start
   ```

6. Abra no navegador: `http://localhost:3000`
