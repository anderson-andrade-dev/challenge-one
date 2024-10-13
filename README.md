# 🌍 Conversor de Moeda Oracle One

![Conversor de Moeda](https://via.placeholder.com/800x300?text=Conversor+de+Moeda+Oracle+One)

**Este projeto é um conversor de moedas desenvolvido em Java, que utiliza a API** [ExchangeRate-API](https://www.exchangerate-api.com/) **para obter as taxas de câmbio mais recentes. O projeto também incorpora um logger para gerenciamento de logs e testes utilizando JUnit 5.**

## 🚀 Tecnologias Utilizadas

- **Java 21**: Linguagem de programação principal utilizada no projeto.
- **Gson**: Biblioteca para serialização e deserialização de objetos Java em formato JSON e vice-versa.
- **API ExchangeRate**: API utilizada para obter as taxas de câmbio entre diferentes moedas.
- **Logger**: Usado para registrar informações e erros durante a execução do programa.
- **JUnit 5**: Framework utilizado para testes unitários, garantindo a funcionalidade correta do código.

## ✨ Funcionalidades

- **Interface Gráfica**: Desenvolvida com Swing, a interface permite ao usuário selecionar a moeda de origem e a moeda de destino, além de inserir a quantidade de moeda a ser convertida.
- **Conversão de Moedas**: O usuário pode inserir uma quantidade de moeda e obter o valor convertido na moeda de destino selecionada.
- **Validação de Entrada**: O campo de entrada para a quantidade de moeda aceita apenas números e permite a edição completa do valor.

## 📁 Estrutura do Projeto

```
src/
├── main/
│   └── java/
│       └── br/
│           └── dev/
│               └── andersonandrade/
│                   └── moedaOne/
├── test/
│   └── java/
│       └── br/
│           └── dev/
│               └── andersonandrade/
│                   └── moedaOne/
```

## 🛠️ Como Usar

1. Clone este repositório em sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/conversor-moeda-oracle-one.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd conversor-moeda-oracle-one
   ```

3. Compile o projeto usando Maven ou seu IDE favorito.

4. Execute a classe `Principal` para iniciar a interface gráfica do conversor de moeda.

5. Selecione a moeda de origem e a moeda de destino, insira a quantidade de moeda e clique em "Converter" para ver o valor convertido.

## 🤝 Contribuição

Se você deseja contribuir para este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## 📜 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

