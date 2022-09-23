<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
        <title>JavaScript</title>
    </head>
    <body>
        <article id="9a2bce86-4e55-4a36-90a3-6d04f2d5bbb6" class="page sans">
            <header><h1 class="page-title">JavaScript</h1></header>
            <div class="page-body"><h2 id="0b48a70f-991f-4c19-b36a-e0db9ffc34a1" class="">Object {}</h2>
            <p id="ad40eb5a-96d6-4ffa-b832-792fa182e39a" class="">Ao criarmos um objeto em JavaScript usamos:</p>
            <pre id="eeb0b03b-374f-4228-bcb9-f90aa463486c" class="code">
            <code>
	const produto {
		id: 1,
		nome: &quot;Copo&quot;
	}
            </code>
        </pre>
        <p id="eb0b2b69-a3c7-4ac9-943a-3325087c8b9f" class="">Com TypeScrip usaremos interface em vez de inicializarmos com valores:</p>
        <pre id="dd537a1d-b06e-4c75-9deb-609a612e9aef" class="code">
            <code>
	interface Produto {
        id: number;
		name: string;
    }
            </code>
        </pre>
                <p id="1b53b417-3769-4f45-8cdc-db86f0079cce" class=""></p>
                <h2 id="3d1176fe-da4e-45bf-8e3d-918fea2d3e81" class="">Diferrenças entre var, let e const</h2>
                <p id="b1539395-8e93-4329-9c54-9e5478fabde7" class="">Em JS toda variável é eleada, içada (hosting)</p>
                <p id="7fdcc59a-1466-4185-960a-553408f1abed" class="">Var pode ser declarda para todo o contexto do código, não impede de ser declarada posteriormente.</p>
                <p id="34c40ccd-f19f-4068-b48b-738b6b1a8b70" class="">let é declarada apenas no contexto atual.</p>
                <p id="00b090b2-125a-4e66-9e66-a26cafdc3a74" class="">const assegura que a variável haverá valor, será iniciada com valor, quando que diferentemenre de var e let, const não pode ser alterado e possui contexto de bloco.</p>
            </div>
        </article>
    </body>
</html>