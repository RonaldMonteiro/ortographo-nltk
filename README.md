<p align="center">
<image src="https://33333.cdn.cke-cs.com/kSW7V9NHUXugvhoQeFaf/images/1367dd1f3cd86a33009eebd1a8dc20a2ab01dc94cba6fba7.png" />
</p>

---

## Descriçao

O _ortographo_.**NLTK** é um microssistema que corrigi palavras a nível ortográfico na língua portuguesa. O sistema usa o corpus textual Mac-Morpho e funciona com base na concepção probabilística da linguagem humana, usando a teoria da distância de Levenshtein e a teoria do coeficiente de similaridade de Jaccard. Seu funcionamento se dá em três etapas:

*   A primeira etapa é a análise da probabilidade para encontrar as palavras mais próximas à palavra que está sendo corrigida.
*   A segunda etapa é a aplicação da distância de Levenshtein que calcula a quantidade mínima de edições para transformar uma palavra em outra.
*   Por fim, a terceira etapa é a aplicação do Coeficiente de Similaridade de Jaccard para garantir que as palavras mais próximas sejam as mais apropriadas para a correção desejada.

##### STACKS UTILIZADAS

O projeto foi criado na linguagem **Python** usando a biblioteca **NLTK** de processamento natural de linguagem. 

[![](https://camo.githubusercontent.com/a27f28ea5d54d3f4711a376236b9f4c78116ce5e80228f45c970cf66f196f2e7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f707970692d3337373541393f7374796c653d666f722d7468652d6261646765266c6f676f3d70797069266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/a27f28ea5d54d3f4711a376236b9f4c78116ce5e80228f45c970cf66f196f2e7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f707970692d3337373541393f7374796c653d666f722d7468652d6261646765266c6f676f3d70797069266c6f676f436f6c6f723d7768697465) [![](https://camo.githubusercontent.com/a00abd8cea4105fa1cad91f7235d11206b492f51afeb9b23a25d04e8f36935e3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d4646443433423f7374796c653d666f722d7468652d6261646765266c6f676f3d707974686f6e266c6f676f436f6c6f723d626c7565)](https://camo.githubusercontent.com/a00abd8cea4105fa1cad91f7235d11206b492f51afeb9b23a25d04e8f36935e3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d4646443433423f7374796c653d666f722d7468652d6261646765266c6f676f3d707974686f6e266c6f676f436f6c6f723d626c7565) [![](https://camo.githubusercontent.com/88ab3c0f78016111d88ef82030375fb740d82dd0c16c1b078c441e22479009b3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5653436f64652d3030373844343f7374796c653d666f722d7468652d6261646765266c6f676f3d76697375616c25323073747564696f253230636f6465266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/88ab3c0f78016111d88ef82030375fb740d82dd0c16c1b078c441e22479009b3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5653436f64652d3030373844343f7374796c653d666f722d7468652d6261646765266c6f676f3d76697375616c25323073747564696f253230636f6465266c6f676f436f6c6f723d7768697465) [![](https://camo.githubusercontent.com/3e216ef6dce0992d9ac7402b82794440093eb6c1e7ec2603dde5555950b8dd24/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f57696e646f77735f31312d3030373864343f7374796c653d666f722d7468652d6261646765266c6f676f3d77696e646f77732d3131266c6f676f436f6c6f723d7768697465)](https://camo.githubusercontent.com/3e216ef6dce0992d9ac7402b82794440093eb6c1e7ec2603dde5555950b8dd24/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f57696e646f77735f31312d3030373864343f7374796c653d666f722d7468652d6261646765266c6f676f3d77696e646f77732d3131266c6f676f436f6c6f723d7768697465)

## Iniciando o Sistema

Primeiro, executar o arquivo com:

```plaintext
python ortographo.py
# ou
python3 ortographo.py
```

Veja o resultado no console do terminal.

---
