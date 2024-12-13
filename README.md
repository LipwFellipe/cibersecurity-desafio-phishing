# Phishing para captura de senhas do Facebook

### Ferramentas Utilizadas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados

![EmailSenha](https://github.com/user-attachments/assets/9a486516-2307-4ca0-b0b8-1a24efe879f9)

### Atenção
Hoje em dia o site do Facebook não permite que ataques como Phishing aconteçam, para fazer o phishing basta salvar o arquivo ```html``` da pagina desejada, e usar o `Custom import` ao invés do `Site Cloner`.

## Criando um RandomWare com Python

- Estes são simples scripts de Python para criptografar e descriptografar arquivos usando a 
biblioteca `pyaes`.

- ```encrypter.py```: O script lê um arquivo descriptografado, usa uma chave de 
criptografia para criptografar os dados, remove o arquivo descriptografado e cria um novo arquivo criptografado.

- ```decrypter.py```: O script lê um arquivo criptografado, usa uma chave de 
descriptografia para descriptografar os dados, remove o arquivo criptografado e cria um novo arquivo descriptografado.

### Pré-requisitos

- O arquivo criptografado (teste.txt) deve estar na mesma pasta que os scripts.

- Execute os scripts Python para criptografar ou descriptografar o arquivo.


### Contribuição

- Se quiser contribuir para o projeto, sinta-se à vontade para fazer um fork do repositório e enviar pull requests.

### Licença

- Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.



