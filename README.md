# Gerador de Senhas Fortes

Este programa em Python gera senhas fortes aleatórias com alta segurança.

## Funcionalidades

- Uso do módulo `secrets` para gerar aleatoriedade criptográfica 
- Obrigatoriedade de letras maiúsculas, minúsculas, números e símbolos
- Tamanho mínimo de 6 caracteres
- Embaralhamento aleatório da ordem dos caracteres

## Uso 

Basta chamar a função gerar_senha_forte() passando o tamanho desejado. Ou execute o programa diretamente e informe o tamanho quando solicitado; 

Execute o programa e informe o tamanho desejado da senha quando solicitado:

```
python strong_password.py
Tamanho desejado da senha (mínimo 6): 12
```

Uma senha com os requisitos de segurança será gerada.

## Explicação

O código importa os módulos `secrets` e `string`, define a função `gerar_senha_forte()` que implementa a lógica de:

- Verificar o tamanho mínimo 
- Inicializar a senha com caracteres obrigatórios
- Adicionar caracteres aleatórios
- Embaralhar a senha
- Retornar a senha gerada

Por fim, o código principal pede o tamanho da senha ao usuário e exibe o resultado.

## Teste Online

Você pode testar uma demo interativa online do gerador de senhas fortes aqui:

https://repl.it/@seunome/strong-password-generator-python


Propósito
Ter senhas realmente fortes e imprevisíveis é essencial para segurança. Este gerador visa tornar trivial a geração de senhas que são muito difíceis de serem advinhadas ou quebradas por força bruta.



Contribuindo
Pull requests são bem vindos! Sinta-se à vontade para contribuir com este projeto.# Gerador-de-Senhas-Fortes.py
