# Pré Requisito - Provisionar Recursos

## Introdução

Nesta etapa, você irá provisionar recursos dentro da OCI utilizando Terraform com o serviço **Resource Manager**!

- 🌀 [Página oficial do Resource Manager](https://www.oracle.com/br/cloud/cloud-native/resource-manager/)
- 🧾 [Documentação do Resource Manager](https://docs.oracle.com/pt-br/iaas/Content/ResourceManager/home.htm)

Os recursos provisionados serão:

- Compartimento
- Object Storage - Buckets
- Data Catalog
- Metastore
- Data Science
- Data Flow - SQL Endpoint

*Tempo estimado para o Lab:* 20 Minutos
- - -

## Tarefa 1: Download do repositório

Como primeiro passo, devemos fazer o download do arquivo (zip).

 1. Para isso, acesse o link para fazer o download: [**Download ZIP**](https://objectstorage.sa-saopaulo-1.oraclecloud.com/p/qR8ZNXygj3cjhuxiMygYvDyc65ouy3Cm_hlEQFhkuX-UDH80zem7IoDcQ9ykBpnf/n/idi1o0a010nx/b/LiveLabsData/o/%5BALL_FILLES%5D%20OCI%20Data%20&%20AI%20Fast%20Track%20-%20For%20Data%20Engineering.zip).
    
    Neste momento, iremos utilizar o arquivo **terraform\_livelabs\_eng.zip**

## Tarefa 2: Upload do terraform no Resource Manager

1. Faça o [login](https://www.oracle.com/cloud/sign-in.html) em sua conta na OCI.

2. No 🍔 menu de hambúrguer, acesse: **Developer Services** → **Resource Manager** → **Stacks**.

![menu developer services stacks](./images/resource-managerconsole.png)

3. Nesta nova janela, certifique que está no compartment "root" e clique em **Create Stack**.

![imagem compartment botao create stack](./images/create-stack-manager.png)

4. Selecione a opção "My configuration". Abaixo, em Stack Configuration, selecione "Zip file", clique em "browse" e arraste o arquivo (terraform\_livelabs\_eng.zip), que contém os arquivos .tf no seu interior. O Resource Manager irá preencher todos os campos.

![imagem stack ](./images/configure-stack-archivezip.png)

5. Clique em **Next**, para verificarmos se todos os campos da imagem abaixo estão preenchidos.

![imagem stack ](./images/configure-stack-archivezip_2.png)

6. Clique em **Next**.

7. Selecione a opção "Run apply" e clique em "Create"

![imagem stack ](./images/configure-stack-archivezip_3.png)

8. O provisionamento dos recursos deverá durar em torno de 10 minutos.

10. Após finalizar o Apply com sucesso, podemos conferir o provisionamento dos nossos recursos!

## Conclusão

Ambientes provisionados com sucesso! Você provisionou recursos usando Terraform na OCI e terminou os pré-requisitos! 

Você pode seguir para o próximo Lab.

##  Autoria

- *Created By/Date* - Thais Henrique, Heloisa Escobar, Isabelle Anjos, Janeiro 2024
- *Last Updated By* - Isabelle Anjos, Outubro 2025