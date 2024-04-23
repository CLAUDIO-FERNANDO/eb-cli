## **Instalar a CLI do EB**

fonte tutorial : https://www.youtube.com/watch?v=LcIpHF7JbZw

PASSO A PASSO:

**passso 1**

sudo pip3 install awsebcli --force-reinstall --upgrade

passo 2

which eb
<img src="https://prod-files-secure.s3.us-west-2.amazonaws.com/8c013206-1127-46aa-9ae9-66e3a3c99cc2/71d77bcd-d9d2-4579-875b-682ec05cd2c1/Untitled.png">



passo 3

export PATH=/usr/local/bin:$PATH

<img src="https://prod-files-secure.s3.us-west-2.amazonaws.com/8c013206-1127-46aa-9ae9-66e3a3c99cc2/d5ad3366-3467-461f-9a58-c36806c2853c/Untitled.png">


CONSULTAR A VERSAO: eb - - version
<img src="https://prod-files-secure.s3.us-west-2.amazonaws.com/8c013206-1127-46aa-9ae9-66e3a3c99cc2/d75ac177-3f6c-48ad-8a0e-f8680e07573b/Untitled.png">


agora podemos exercutar init para inicar as configuraçoes do eb cli: 
comando: eb init
