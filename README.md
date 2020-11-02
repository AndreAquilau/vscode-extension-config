## Produtividade com VScode

#### Extensions
- Install Extension Theme Dracula Official **Dracula**.
- Install Extension **Reload**.
- Font **Fira Code** [link](https://github.com/tonsky/FiraCode)
  - > How to Install => VScode
  - > Download & Install Fire_Code.zip
  - > Click control painel => Fonts coloque as fonts ttf e coloque na tela de fonts
  - > In VScode options => settings => open json.
  - > Reload VScode
```json
/*add two line in settings.json*/
"editor.fontFamily": "Fira Code",
"editor.fontLigatures": true,
```
```js
const soma = () => {
    `teste`
}
```
--------------------------------------------------------------------------------
- Install Extension **Auto Rename Tag** utilizados nos arquivos **tsx**, **jsx** e **html**.
- Install Extension **Color HighLight** quando utiliza cores em hexadecimal mostra a cor no fundo.
- Install Extension **Rainbow Rrackets** coloca uma cor diferente para cada abertura e fechamento de parênteses (()).
- Install Extension **Material Icon Theme** vai colocar icones para os arquivos e pastas.
> Icones Personalizados => associations
> settings.json
> Verificar na biblioteca de icons do material icon e escolher uma.
```json
    /*icons de arquivos*/
    "material-icon-theme.files.associations": {

    },
    /*icons de pastas*/
    "material-icon-theme.folders.associations": {
      "batata": "Ändroid"  
    }
```
---------------------------------------------------------------------------------------
- Install Extension __SVG Preview__, visualizar imagens vetorizadas no VsCode.
- Install Extension __VScode-Styled-Components__, utilizada em conjunto com a biblioteca styled-components.