# Uso Básico do Terminal

O terminal é uma das ferramentas mais utilizadas quando estamos desenvolvendo alguma aplicação. Ele consegue nos fornecer várias maneiras mais rápidas de fazer atividades mais triviais como criar, apagar ou renomear arquivos e diretórios. Portanto, é necessário aprender suas funcionalidades mais básicas e , aos poucos, irmos incrementando nossos aprendizados. Neste guia irei mostrar o uso mais básico do terminal e os comandos mais usados no cotidiano, além de algumas técnicas que agilizam seu uso.

Antes de começarmos, precisamos entender dois fatores importantes.

1. **Terminal** - Quando mencionamos a palavra terminal, estamos falando, geralmente, do shell, que é a aplicação que nos fornece os comandos e utilidades. Na maioria das distribuições Linux, o terminal (ou seja, o Shell) utilizado por padrão é o **Bash**.

2. Diferente do shell, terminal também pode referir ao **emulador de terminal**, que é basicamente o ambiente onde o shell está executando. Na maioria das distribuições Linux, o emulador de terminal depende do desktop-enviroment, que de maneira mais leiga podemos dizer que é o ambiente do sistema operacional. Por padrão o desktop-enviroment é o GNOME, e o emulador de terminal é o gnome-terminal. Se o ambiente for KDE, o emulador de terminal será o Konsole, por exemplo.
3. É importantes frizar que o emulador é apenas o ambiente onde o shell própriamente dito está sendo executado, e, geralmente, ele não interfere muito nas situações de uso cotidiano.

**Resumo:** shell é o conjunto de funcionalidades e comandos, emulador de terminal é onde esse shell está sendo 'emulado' ou executado.

_É primordial entender essa diferença pois essa terminologia muitas vezes confunde quem está iniciando sua jornada com o uso do terminal._

## Técnicas

- Tab Completion
  - Trata-se de utilizar o recurso de 'autocomplete' do shell, ou seja, digitamos apenas uma parte do comando ou funcionalidade e apertamos a tecla Tab e o terminal completa o restante do comando/funcionalidade.
- Clear / ctrl + l
  - Podemos digitar o comando **clear** para limpar a tela do terminal. Lembrando que esse comando não limpa realmente o histórico de comandos ou os comandos digitados, ele apenas vai dar um **scrollup** em tudo que está na tela do terminal e deixar a tela 'limpa', esse comando é muito utilizado e, por isso, ele tem um atalho próprio que na maioria dos emuladores é o **ctrl + l**.
- ArrowUp / ArrowDown
  - Tudo que digitamos no terminal fica guardado em um histórico próprio. Para acessá-lo, entre outras formas, usamos as teclas **ArrowUp / ArrowDown** do teclado.
- Stop / ctrl + c
  - Quando digitamos um comando e ele está sendo executado mas, por exemplo percebemos que algo está errado ou que digitamos um comando errado, e o shell está executando outro comando, podemos apertar **ctrl + c** para 'parar' a execução do comando.
