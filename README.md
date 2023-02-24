### Criando um SQL Azure e um database. ###

1. Vamos criar o recurso, para isso clicar em CREATE:
![image](https://user-images.githubusercontent.com/119356073/221269569-ae13f2b9-f32b-47cd-bce2-c39aab9ef85b.png)

2.  Selecionar Azure SQL:
![image](https://user-images.githubusercontent.com/119356073/221269640-2d6d2e2e-2a1e-4f81-a627-91680b0ddfef.png)

3. Nesse caso vamos criar um Database Server:
![image](https://user-images.githubusercontent.com/119356073/221269684-1592de37-215a-4e20-a981-491eea63f690.png)

4. Precisamos preencher algumas informações importante

  4.1 Server name

  4.2 Location

  4.3 Authentication Method

  4.4 Server admin/Password

![image](https://user-images.githubusercontent.com/119356073/221269997-faf0c3e9-50ee-419d-8bae-15f2336658ee.png)

5. Em Newtwork deixar do jeito que está:

![image](https://user-images.githubusercontent.com/119356073/221270876-94ffe61a-dac3-40c0-bb71-bf8f6a132d5a.png)

6. Em Additional Settings deixar do jeito que está:

![image](https://user-images.githubusercontent.com/119356073/221271035-a9a42d27-214b-4fd9-bd61-ce970e71665c.png)

7. Em Review + Create ira mostrar a nossa configuração e após valir, clicar em Create:
![image](https://user-images.githubusercontent.com/119356073/221271093-64c8bd4b-a9d6-448b-9a4d-a46785fbb5d8.png)

8. Criado:
![image](https://user-images.githubusercontent.com/119356073/221271234-98e62ee2-8298-44bb-8e27-35bb6d99d571.png)

## **Criando um Database**

1. Clicar em **“Create database”**
![image](https://user-images.githubusercontent.com/119356073/221271419-264c23ff-2279-47ba-91db-e04a0236e21b.png)

2. Nessa etapa precimos definir as configurações do Database, nesse caso só iremos definir o nome, e configuração vCPU’s - DTUs…
![image](https://user-images.githubusercontent.com/119356073/221271516-aaeabc35-99e1-4b04-b6d0-5b591db30623.png)

2.1 Configuração
![image](https://user-images.githubusercontent.com/119356073/221271642-bc26906d-f5f1-4cdb-a56e-f0fff4a8decc.png)

2.2 Podemos definir as configurações por vCORE ou DTU

![image](https://user-images.githubusercontent.com/119356073/221271694-cd73ace3-00ba-4378-acbb-5ad493b3c669.png)

2.3 Custos:
 Note que os valores mensais

![image](https://user-images.githubusercontent.com/119356073/221271762-216ae2ec-4c2b-44b1-b88b-dd6e9e37a1ed.png)

3. Nas abas Network, Security e Additional Settings não precisamos configurar nada por enquanto.
4. Em Review + create, revisar as configurações e clicar em **CREATE**
![image](https://user-images.githubusercontent.com/119356073/221271966-0e0a743f-46b7-40da-899c-138611a7edc5.png)

5. Informações do Database criado:
![image](https://user-images.githubusercontent.com/119356073/221272028-4da98e3a-dafb-40d7-bf14-c9b0c8441e8f.png)

6. Liberando IP do Firewall para poder acessar o Banco.
 6.1 No SQL Server, na opção “Networking”
![image](https://user-images.githubusercontent.com/119356073/221272102-549210cf-1ddb-417c-9c40-0f3f3189c57c.png)

6.2 Em Firewall rules, adicionar o seu ip de saída (geralmente ele já pega qual ip que você está utilizando)
![image](https://user-images.githubusercontent.com/119356073/221272264-d402aee5-3bb3-4540-a922-8f4eb02a7125.png)
![image](https://user-images.githubusercontent.com/119356073/221272313-2fde9f45-9c30-496f-81ab-77bb88ca03fe.png)

7. Agora vamos acessar o Banco via SSMS (SQL Server Management Studio)
 7.1 No Server Name, vamos colocar o nome do Banco de dados e na Authentication deixar “SQL Server Authentication” e coloca o usuário e senha definido no momento da criação.
![image](https://user-images.githubusercontent.com/119356073/221272437-897ed525-f176-4548-a3ab-381b6f4b33cd.png)

7.2 Onde encontrar o Server Name:
![image](https://user-images.githubusercontent.com/119356073/221272493-4216152a-2665-453e-ac35-f60851d3926e.png)

8. Agora estamos dentro do banco e conseguirmos visualizar o database criamos!
![image](https://user-images.githubusercontent.com/119356073/221272556-820442a3-b4f5-4a46-a2ec-1a755230d736.png)




