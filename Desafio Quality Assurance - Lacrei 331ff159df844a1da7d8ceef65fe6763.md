# Desafio Quality Assurance - Lacrei

Criado por: Andreia Gomes Marins
Hora da criação: 18 de abril de 2024 10:12
Tags: Desafio, LacreiSaúde, QA, Voluntariado

# **Declaração do desafio - Criar Casos de Testes**

Este documento consiste em descrever os detalhes do desafio para participar da vaga de voluntário para a equipe Lacrei Saúde e consiste em:

1. Criar casos de testes para os fluxos citados abaixo:
- Fluxo da pessoa usuária (Versão Mobile):
    - **Cadastro da pessoa usuária**: Cadastro → Pós Cadastro → Buscar Profissional -
    - **Buscar uma pessoa profissional:** Buscar Profissional → Contatar Profissional -
    - **Editar Perfil da Pessoa Usuária**: Inserir as informações solicitadas com troca de dados -
    - **Esquecer a senha da pessoa usuária.**
    - **Testar reset de senha.**
    
    Será usado como recurso o site [https://paciente.lacreisaude.com.br/](https://paciente.lacreisaude.com.br/)
    
    Documentação será aplicada nas ferramentas Notion e GitHub
    

## 

## **1. Cadastro da pessoa usuária**:

[Cadastro da pessoa usuária.docx](Desafio%20Quality%20Assurance%20-%20Lacrei%20331ff159df844a1da7d8ceef65fe6763/Cadastro_da_pessoa_usuria.docx)

Para realizar o cadastro da pessoa usuária no site deverá ser seguido o seguinte fluxo:

1. Abrir a página de cadastro. (página decadastro:[https://paciente.lacreisaude.com.br/](https://paciente.lacreisaude.com.br/))
2. Preencher o formulário com informações pessoais. (Clicar na opção criar conta e preencher os seguintes dados: Nome, sobrenome, e-mail, senha, repetir a senha). A senha deve possuir os seguintes caracteres mínimos: 8 caracteres, letra maiúscula, letra minúscula, número caractere especial(ex.:#!_&). Aceitar os termos de uso e política de privacidade e confirmar que possui 18 anos ou mais.
3. Clicar em "Enviar" para concluir o cadastro.
4. Testar a funcionalidade de busca de profissional após o cadastro. No campo busca digitar o nome da especialidade que possui interesse em pesquisar e logo depois  clicar em pesquisar.

### Critérios de aceitação:

- Todos os campos obrigatórios devem ser preenchidos.
- O e-mail fornecido deve ser único e válido.
- A senha deve atender aos critérios de segurança definidos pelo sistema.
- A pessoa usuária deve receber uma mensagem de confirmação de cadastro após o registro.

### Resultado Esperado:

O usuário aparecerá logado, podendo visualizar essa informação ao lado superior à direita e a página de pós-cadastro estará exibida corretamente.

## **2. Buscar uma pessoa profissional:**

[Buscar uma pessoa profissional.docx](Desafio%20Quality%20Assurance%20-%20Lacrei%20331ff159df844a1da7d8ceef65fe6763/Buscar_uma_pessoa_profissional.docx)

Para realizar a busca de uma pessoa profissional deverá ser seguido o seguinte fluxo:

1. O usuário deverá realizar o login informando seus dados de acesso como e-mail e senha e clicar em entrar.
2. Será exibida a página principal de busca pelo profissional e o usuário deverá escrever no campo de pesquisa o nome da especialidade que possui interesse em pesquisar e logo clicar em pesquisar.

### Critérios de aceitação:

- Todos os campos obrigatórios da busca devem ser preenchidos, neste caso o nome da especialidade.
- Após o envio do formulário, uma mensagem de confirmação de cadastro bem-sucedido deve ser exibida.
- Os dados cadastrados devem estar corretamente salvos no sistema.

### Resultado Esperado:

O usuário deverá ser capaz de visualizar as respostas encontradas como nome do especialista, CRM e + informações sobre o profissional.

## **3. Editar Perfil da Pessoa Usuária**:

[Editar Perfil da Pessoa Usuária.docx](Desafio%20Quality%20Assurance%20-%20Lacrei%20331ff159df844a1da7d8ceef65fe6763/Editar_Perfil_da_Pessoa_Usuria.docx)

Para editar perfil da pessoa usuária deverá ser seguido o seguinte fluxo:

1. O usuário deverá realizar o login informando seus dados de acesso como e-mail e senha e clicar em entrar.
2. Será exibida a página principal de busca pelo profissional e para editar os dados do perfil o usuário deverá clicar na opção ver perfil, esta informação será visualizada ao lado superior à direita da tela.
3. Será apresentado as informações pessoais do usuário como por exemplo: foto do perfil, nome, data de nascimento, pronome, etnia, gênero, sexualidade e deficiência. Clicar na opção editar dados para os dados pessoais e na opção editar foto para a opção de alterar ou incluir a foto do usuário. Logo após o preenchimento das alterações clicar em salvar.

### Critérios de aceitação:

- Todos os campos do cadastro de edição do perfil devem ser editáveis.
- As alterações feitas nos campos devem ser refletidas corretamente no perfil da pessoa usuária.
- Uma mensagem de confirmação de sucesso deve ser exibida após a atualização do perfil.

### Resultado Esperado:

O usuário deverá ser capaz de acessar seu cadastro com o perfil alterado com sucesso.

## **4. Esquecer a senha da pessoa usuária.**

[Esquecer a senha da pessoa usuária.docx](Desafio%20Quality%20Assurance%20-%20Lacrei%20331ff159df844a1da7d8ceef65fe6763/Esquecer_a_senha_da_pessoa_usuria.docx)

Para esquecer a senha da pessoa usuária deverá ser seguido o seguinte fluxo:

1. O usuário deverá acessar a página do login e logo após clicar na opção esqueci minha que fica localizada abaixo do campo criar conta.
2. Seguidamente o usuário será direcionado para a página “redefinir senha” e o mesmo deverá preencher o campo e-mail com o seu e-mail de cadastro do site e clicar na opção “enviar link”.
3. O usuário deverá acessar o e-mail cadastrado e seguir os passos e orientações para redefinir a senha. 

### Critérios de aceitação:

- O usuário deve receber um e-mail de redefinição de senha após solicitar o reset.
- O link de redefinição de senha no e-mail deve direcionar corretamente para a página de redefinição de senha.
- O sistema deve aceitar e confirmar a nova senha do usuário.
- O usuário deve ser capaz de fazer login no sistema utilizando a nova senha após o reset.

### Resultado Esperado:

O usuário deverá ser capaz de fazer o login com sucesso com a nova senha redefinida.

## 5. Testar Reset de senha:

Para testar o reset de senha deverá ser seguido o seguinte fluxo:

1. No caso de lembrar a senha: O usuário deverá realizar o login informando seus dados de acesso como e-mail e senha e clicar em entrar.

[Testar Reset de senha.docx](Desafio%20Quality%20Assurance%20-%20Lacrei%20331ff159df844a1da7d8ceef65fe6763/Testar_Reset_de_senha.docx)

1. Será exibida a página principal de busca pelo profissional e para o reset da senha o usuário deverá clicar na opção ver perfil, esta informação será visualizada ao lado superior à direita da tela.
2. Será apresentado as informações pessoais do usuário, segurança e privacidade. O usuário deverá  escolher a opção segurança e logo após clicar em “alterar senha”, será solicitado a senha atual e a nova senha, o usuário deverá confirmar a nova senha e clicar em salvar senha.
3. No caso de não recordar a senha, deverá ser seguido os passos da descrição do item “Esquecer a senha do usuário”. 

### Critérios de aceitação:

- O usuário deve ter acesso a senha atual, em caso negativo deverá seguir os passos na opçao esqueci minha senha.
- O sistema deve aceitar e confirmar a nova senha do usuário.
- O usuário deve ser capaz de fazer login no sistema utilizando a nova senha após o reset.

### Resultado Esperado:

 O usuário deverá ser capaz de fazer o login com sucesso com a nova senha resetada.

# 6. Melhorias:

Ao final de cada teste realizado a página é atualizada sem nenhuma informação, a sugestão de melhorias sobre o tema está na condição de gerar uma mensagem padrão de sucesso da alteração realizada. Exemplo:  Reset realizado com sucesso; Alteração de cadastro realizado com sucesso.