# Password Generator

Este projeto visa gerar senhas seguras de forma aleatória. O programa é escrito em Python e contém algumas funções úteis para a geração de senhas aleatórias.

## Recursos

- Geração de senhas seguras aleatórias.
- Possibilidade de especificar o comprimento da senha.
- Possibilidade de incluir símbolos, números e letras maiúsculas em sua senha.

## Uso

Para usar este programa, você deve baixá-lo e abri-lo no seu editor de texto favorito. A partir daí, você pode usar a função `generate_password` para gerar uma senha segura aleatória. Por exemplo, para gerar uma senha com 8 caracteres, você pode usar:

```
password = generate_password(8)
```

Você também pode especificar parâmetros adicionais para incluir letras maiúsculas, números e símbolos. Por exemplo, para gerar uma senha com 8 caracteres contendo letras maiúsculas, números e símbolos, você pode usar:

```
password = generate_password(8, include_uppercase=True, include_numbers=True, include_symbols=True)
```

## Contribuição

Se você deseja contribuir para este projeto, fique à vontade para criar uma [nova issue](https://github.com/Fe7rodrigues/password-generator/issues/new) ou enviar um [pull request](https://github.com/Fe7rodrigues/password-generator/pulls).

## Licença

Este projeto está sob a [licença MIT](https://github.com/Fe7rodrigues/password-generator/blob/main/LICENSE).