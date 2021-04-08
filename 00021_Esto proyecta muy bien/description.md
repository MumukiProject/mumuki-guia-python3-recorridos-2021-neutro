Ana realiza muchas proyecciones sobre los balances de su empresa, por lo que le dijimos que podíamos ayudarla ahora que sabemos mapear. Lo que quiere hacer es poder ver cuáles serían las ganancias de un balance si todas hubieran sido del doble :moneybag:. Por ejemplo:

``` python
ム balances_ultimo_semestre = [
	{ "mes": "julio", "ganancia": 50 }, 
	{ "mes": "agosto", "ganancia": -12 }, 
	{ "mes": "septiembre", "ganancia": 1000 }, 
	{ "mes": "octubre", "ganancia": 300 }, 
	{ "mes":  "noviembre", "ganancia": 200 }, 
	{ "mes": "diciembre", "ganancia": 0 }
]

ム doble_de_ganancias(balances_ultimo_semestre)
[100, -24, 2000, 600, 400, 0]
```

Como verás, si las ganancias fueran negativas ahora serán ¡doblemente negativas! :chart_with_downwards_trend:

> Define la función `doble_de_ganancias`. Puedes utilizar tanto `for...in` como listas por comprensión, lo que tu  prefieras. :relaxed: