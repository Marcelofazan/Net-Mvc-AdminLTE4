## 🌐 Net-Mvc-AdminLTE4 
Exemplo de criação de  Renderizar do AdminLTE4 com Layout em NET MVC5 Razor com banco de dados MySQL.

#### 🎨 Aqui está uma demonstração do Projeto
<img width="800" height="350" alt="AdminLTE4-Net-Mvc5" src="https://github.com/user-attachments/assets/38abc628-4791-49a3-b91a-20acee7a07ec" />

#### 📋 O que você vai encontrar neste projeto
| Tecnologia | Descrição |
|-----------|-----------|
| **AdminLTE** | Template de painel administrativo (Dashboard) de código aberto construído com o framework Bootstrap. |
| **Dicionário de Dados** | Armazenamento de coleções de pares (chave-valor), permitindo busca e recuperação de dados |

#### Requisitos do Projeto
- Para executar a aplicação é necessário executar o Script do MySQL.

#### ⚠️ String de conexão do banco
Modifique a string de conexão no arquivo **Web.config**, no trecho indicado:

```bash
server=127.0.0.1;userid=root;password=SUASENHA;database=SEUBANCO;persistsecurityinfo=True;
```

O script para criação da tabela do exemplo encontra-se na pasta **Database**.

#### 🔄 Executar a aplicação
Baixar Pacote de Distribuição de Download da biblioteca e descompactar

- [AdminLTE](https://github.com/ColorlibHQ/AdminLTE/releases/download/v4.0.0/admin-lte-v4.0.0.zip)

Criar uma nova pasta chamada adminlte no Solution do Projeto
- Acessar o diretorio na pasta AdminLTE-4 /dist ->  Arrastar as pastas (css), (assets) e (js) e Colar dentro da pasta adminlte

Ficara com a seguinte estrutura:

**Solution** Pasta na Raiz do Projeto 
```bash
adminlte
|-------|
        |-------| /css
        |-------| /assets 
        |-------| /js
```
