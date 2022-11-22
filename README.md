# :key: TypeScript


:mag_right:  ``` Estudo sobre typeScript, primeiros passos ```

**Configurando o ambiente com Typescript** :

```
configurando node , instalando TypeScript e configurando servers 
```
<h3> Tipagem </h3>

<li>O tipo implícito any e a importancia da tipagem estáica
<li>Mais configurações do compilador tsc
<li>Retorno de método explícito
<li>Conversão de valores da interface do usuário

<h3>Exemplo: de atribuição de tipagem, colocado os tipos nos metodos da classe</h3>

```
export class Negociacao {
    private _data: Date;
    private _quantidade: number;
    private _valor: number;

    constructor(data: Date, quantidade: number, valor: number) {
        this._data = data;
        this._quantidade = quantidade;
        this._valor = valor;
```

<img src="https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-blue">
