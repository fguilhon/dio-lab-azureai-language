# dio-lab-azureai-language

Neste laboratório aprendemos a utilizar o Language Studio da Azure. É uma ferramenta extremamente poderosa que consegue processar textos em linguagem natural e realizar análises, classificação, extrar informações, traduzir entre diferentes línguas, entender e responder perguntas. 

Na pasta inputs está um exemplo de texto que utilizamos para testar a ferramenta. A intenção era verificar se a análise de sentimentos e opiniões iria funcionar com sarcasmo. 

![Sentença 1](/prints/sentenca1.png?raw=true "Sentença 1")

Nessa primeira sentença, a análise errou completamente não entendendo que se tratava de sarcasmo.

![Sentença 2](/prints/sentenca2.png?raw=true "Sentença 2")

Pela divisão das porcentagens conseguimos perceber que a análise compreendeu um pouco melhor o sarcasmo e classificou como sentimento negativo essa segunda sentença.

![Sentença 3](/prints/sentenca3.png?raw=true "Sentença 3")

Mais uma vez, a análise se perdeu e classificou como sentimento positivo.

![Sentença 4](/prints/sentenca4.png?raw=true "Sentença 4")

![Sentença 5](/prints/sentenca5.png?raw=true "Sentença 5")

Aqui novamente a análise percebeu um pouco o sarcasmo e classificou como negativo.

![Sentença 6](/prints/sentenca6.png?raw=true "Sentença 6")

![Sentença 7](/prints/sentenca7.png?raw=true "Sentença 7")

![Sentença 8](/prints/sentenca8.png?raw=true "Sentença 8")


Como podemos ver, a performance não foi boa quando envolvia o sarcasmo por que a ferramenta não compreende muito bem o contexto. Mas para análises mais superficiais a ferramenta se sai muito bem.
