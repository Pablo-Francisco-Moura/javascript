<html>
    <body>
        <article>
            <header>
				<h1>JavaScript</h1>
			</header>
            <div>
				<h2>Object {}</h2>
				<p>Ao criarmos um objeto em JavaScript usamos:</p>
				<pre>
					<code>
	const produto {
		id: 1,
		nome: &quot;Copo&quot;
	}
					</code>
        		</pre>
        		<p>Com TypeScrip usaremos interface em vez de inicializarmos com valores:</p>
        		<pre>
            		<code>
	interface Produto {
        id: number;
		name: string;
	}
            		</code>
        		</pre>
                <p></p>
                <h2>Diferrenças entre var, let e const</h2>
                <p>Em JS toda variável é eleada, içada (hosting).</p>
                <p>Var pode ser declarda para todo o contexto do código, não impede de ser declarada posteriormente.</p>
                <p>let é declarada apenas no contexto atual.</p>
                <p>const assegura que a variável haverá valor, será iniciada com valor, quando que diferentemenre de var e let, const não pode ser alterado e possui contexto de bloco.</p>
            </div>
        </article>
    </body>
</html>