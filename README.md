# Requisitos Funcionais

## 1. **Cadastro de Usuários**  
   - Permitir o registro de usuários responsáveis pelas movimentações.  
   - Cada usuário deve ter um identificador único e nome completo.  

## 2. **Autenticação Simulada**  
   - Permitir que o usuário faça login com um identificador simples.  
   - O sistema deve reconhecer o responsável e associar suas ações às movimentações.  

## 3. **Cadastro de Produtos**  
   - Permitir o cadastro de produtos com os seguintes campos obrigatórios:  
     - Nome  
     - Marca  
     - Volume/Unidade  
     - Categoria  
     - Estoque inicial  
     - Estoque mínimo  

## 4. **Listagem de Produtos**  
   - Exibir todos os produtos cadastrados.  
   - Permitir filtros por nome, marca e categoria.  
   - Permitir listar apenas produtos abaixo do estoque mínimo.  

## 5. **Consulta de Produto Específico**  
   - Permitir visualizar os detalhes de um produto pelo seu ID.  

## 6. **Movimentações de Estoque**  
   - Registrar **entradas** de produtos com quantidade, responsável e observação.  
   - Registrar **saídas** de produtos com quantidade, responsável e observação.  
   - Atualizar automaticamente o estoque atual após cada movimentação.  

## 7. **Controle de Estoque Mínimo**  
   - Emitir alertas automáticos quando o estoque atual de um produto ficar abaixo do mínimo configurado.  

## 8. **Histórico de Movimentações**  
   - Registrar todas as movimentações com:  
     - Produto  
     - Tipo (entrada/saída)  
     - Quantidade  
     - Estoque anterior e novo  
     - Responsável  
     - Data e hora  
     - Observação  
   - Permitir consulta por produto, tipo de movimentação e período.  

## 9. **Interface Web**  
   - Disponibilizar páginas para:  
     - Login  
     - Menu principal  
     - Cadastro de produtos  
     - Gestão de estoque (entradas e saídas)  
     - Alertas de estoque mínimo  
## 10. **Validações**
  - Garantir que todos os campos obrigatórios sejam preenchidos no cadastro de produtos.  
  - Impedir movimentações com quantidade inválida (zero ou negativa).
  - Impedir saídas maiores que o estoque disponível.



# Diagrama


<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/3467c362-931d-47ac-816b-d5c150c976ac" />
