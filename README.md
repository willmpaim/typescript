# Aprendendo TypeScript

Simulando metodos de negociacao de financeira: 

## Primieros passos

<li>Download do TypeScript, Configuração do compilador e papel do tsconfig.json
<li>Integração com scripts do Node.js
<li>Modificadores de acesso private e public
<li>Benefícios iniciais da linguagem TypeScript


**Benefícios da tipagem estática**
```
export class Negociacao {
    private _data: Date;
    private _quantidade: number;
    private _valor: number;

    constructor(data: Date, quantidade: number, valor: number) {
        this._data = data;
        this._quantidade = quantidade;
        this._valor = valor;
    }
    
 Importância dos modificadores de acesso *Private* e *Public* e a Tipagem nos metodos.
```

**Arrays** 
```
import { Negociacao } from './negociacao.js';

export class Negociacoes {
    private negociacoes: Array<Negociacao> = [];

    adiciona(negociacao: Negociacao) {
        this.negociacoes.push(negociacao);
    }

    lista(): ReadonlyArray<Negociacao> {
        return this.negociacoes;
    }
}

tipo *Generic* e *ReadonlyArray*

```
