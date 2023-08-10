# Projeto Flutter com MobX

Este é um projeto Flutter que demonstra o uso do MobX como gerenciador de estado. MobX é uma biblioteca de gerenciamento de estado que torna a tarefa de manter o estado da aplicação mais simples e reativa.

## Sobre o Projeto

Este aplicativo Flutter apresenta um contador simples com uma interface de usuário que permite ao usuário aumentar o valor do contador pressionando um botão. O estado do contador é gerenciado pelo MobX, que permite atualizar automaticamente a interface de usuário sempre que o estado é modificado.

### Recursos Principais

- Uso do MobX para gerenciar o estado da aplicação.
- Interface de usuário amigável com contador e botão de incremento.
- Atualização automática da interface de usuário conforme o estado é modificado.

## Instalação

1. Certifique-se de ter o Flutter instalado em seu sistema. Se não tiver, siga as instruções em [flutter.dev](https://flutter.dev/docs/get-started/install) para instalá-lo.

2. Clone este repositório para sua máquina local:

```bash
git clone https://github.com/seu-usuario/projeto-flutter-mobx.git
```

3. Navegue até o diretório do projeto:

```bash
cd projeto-flutter-mobx
```

4. Execute o aplicativo:

```bash
flutter run
```

## Dependências

As seguintes dependências e packages foram utilizados neste projeto:

- [mobx](https://pub.dev/packages/mobx): Uma biblioteca de gerenciamento de estado que ajuda a tornar o código mais reativo e fácil de manter.
- [flutter_mobx](https://pub.dev/packages/flutter_mobx): Um pacote que integra o MobX com o Flutter, permitindo que o estado reativo seja automaticamente refletido na interface de usuário.

Certifique-se de que essas dependências estão listadas no seu arquivo `pubspec.yaml`.

## Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
