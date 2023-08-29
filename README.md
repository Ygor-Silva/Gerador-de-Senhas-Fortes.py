# Gerador de Senhas Fortes

## Propósito

Ter senhas realmente fortes e imprevisíveis é essencial para segurança. Este gerador visa tornar trivial a geração de senhas que são muito difíceis de serem advinhadas ou quebradas por força bruta.

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

Para testar o código do gerador de senhas aleatórias no site testedesenha.com.br, você pode seguir estes passos:

1. Copie o código Python completo para gerar a senha (função gerar_senha_forte() e código principal)

2. Acesse o site https://www.testedesenha.com.br/ e clique em "Testar Senha"

3. Cole o código Python em um editor de texto de sua preferência (como Visual Studio Code) e salve como um arquivo .py, por exemplo gerador_senha.py

4. Abra o terminal/prompt de comando na pasta onde salvou o arquivo e execute:

```
python gerador_senha.py
```

5. Insira o tamanho de senha desejado quando solicitado.

6. Copie a senha gerada pelo programa.

7. Volte ao site testedesenha.com.br, cole a senha no campo "Senha" e clique em "Avaliar Senha".

8. O site irá analisar e avaliar a força da senha gerada pelo programa Python.

9. Repita o processo para diferentes tamanhos de senha e veja como a pontuação de segurança irá aumentar conforme o tamanho.

Dessa forma você poderá verificar na prática a eficiência do gerador de senhas aleatórias e testar a segurança das senhas produzidas.


Contribuindo
Pull requests são bem vindos! Sinta-se à vontade para contribuir com este projeto.# Gerador-de-Senhas-Fortes.py
