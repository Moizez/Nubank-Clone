<h1 align="center">
 
![picpay-logo](https://user-images.githubusercontent.com/29413231/94051938-ab66cf80-fdae-11ea-9077-c2ef6bfa17f9.png)

</h1>

 # Nubank | Clone
> Clone da interface do banco digital mais popular no Brail, o Nubank feito em React Native CLI.
<img src="https://img.shields.io/static/v1?label=react-native&message=framework&color=blue&style=for-the-badge&logo=REACT"/>

## Índice
- [Demonstração](#Demonstração)
- [Apresentação](#Apresentação)
- [Instalação](#Instalação)
- [Etapas](#Etapas)
- [Tecnologias](#Tecnologias)
- [Contato](#Contato)

## Demonstração
<h1 align="center">
 
 ![PicPay-Clone](/picpay.gif)
 
</h1>

## Apresentação
Este projeto foi realizado para minha prática pessoal e como forma de contribuição para a comunidade de desenvolvedores, não visando nenhum lucro, apenas focado em compartilhar conhecimento e crescimento profissional. Para a criação deste clone do **Nubank** utilizei como base o [vídeo](https://youtu.be/DDm0M_rZLJo) da Rocketseat do Diego Fernandes.

## Instalação
```java
  # Para instalar e utilizar esse template o processo é bem simples, basta criar um projeto novo utilizando o comando:
  $ react-native init AwesomeExample --template rocketseat-basic

  # Depois do projeto criado você pode deletar o arquivo `App.js` da raiz, pois o arquivo `index.js` agora aponta para a pasta **src**.
  
  # Faça o download deste repositório:
  $ git clone https://github.com/Moizez/Nubank-Clone

  Com isso o projeto será criado com todas as dependências do template devidamente instaladas e linkadas, tal como os arquivos de configuração que são copiados para o projeto.

```
Obs: Em caso de dúvidas consulte a documentação oficial do [react native](https://reactnative.dev/docs/0.60/getting-started).

---

#### Passo Adicional no Android

Para que os gestos sejam habilitados no Android é necessário um passo a mais, que é bem simples, abra o arquivo `android/app/src/main/java/<pacote_do_projeto>/MainActivity.java`, e começe importando os pacotes como abaixo:

```java
// ...
import com.facebook.react.ReactActivity;
// Importações adicionadas
import com.facebook.react.ReactActivityDelegate;
import com.facebook.react.ReactRootView;
import com.swmansion.gesturehandler.react.RNGestureHandlerEnabledRootView;
```

Feito a importação vamos criar um método novo, logo abaixo do `getMainComponentName()`, ficando:

```java
public class MainActivity extends ReactActivity {
  @Override
  protected String getMainComponentName() { ... }
  // Método adicionado
  @Override
  protected ReactActivityDelegate createReactActivityDelegate() {
    return new ReactActivityDelegate(this, getMainComponentName()) {
      @Override
      protected ReactRootView createRootView() {
        return new RNGestureHandlerEnabledRootView(MainActivity.this);
      }
    };
  }
}
  
```

## Etapas
- [x] Criação
- [x] Criação da tela inicial
- [x] Criação da tela da carteira
- [x] Criação da tela de pagamentos
- [x] Criação da tela de notificações
- [x] Criação da tela de ajustes

## Tecnologias
|Tecnologias | Versão |
|------------|--------|
|react        |**16.13.1** |
|react-native |**0.63.2** |
|react-native-gesture-handler |**^1.8.0** |
|react-native-linear-gradient     |**^2.5.6** |
|react-native-reanimated     |**^1.13.0** |
|moment     |**^2.27.0** |
|react-native-emoji     |**^1.8.0** |
|react-native-safe-area-context     |**^3.1.8** |
|react-native-screens     |**^2.11.0** |
|react-native-vector-icons     |**^7.1.0** |
|styled-components     |**^5.1.1** |

## Contato
Moisés Henrique | Analista de Sistemas
- E-mail: moizezhenrique@gmail.com
- Twitter: [@moizezhenrique](https://twitter.com/moizezhenrique)
- Instagram: [@moizezhenrique](https://www.instagram.com/moizezhenrique)

