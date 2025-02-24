# -Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI


<br>
<h2>Capacidades de processamento de linguagem natural do Azure</h2>
<br>
 <h3> Language Studio(Estúdio de Linguagem da Microsoft)</h3>
<br>
<p>Tem como propósito ter um conjunto de ferramentas baseadas no cenário de interface de usuário, permitindo explorar, integrar, criar recursos de linguagem, atráves de uma plataforma que traga ideias acerca daquilo que está sendo escrito.</p>
<br>
Ex: "Passei férias maravilhosas na Suíça"
<br>
Idioma Predominante: Português
<br>
Sentimento: 0,88 (positivo)
<br>
Frase-chave: "Férias maravilhosas"
<br>
Entidades: Suíça<br>
<br>
Ou seja, quando se utiliza o cenário do Language Studio, ele ajuda a dar uma classificação sobre o texto escrito, com base na compreensão do idioma e na classificação personalizada, sendo possível criar um recurso onde se tenha diversos cenários que podem ser metrificados, dizendo o quanto as pessoas estão felizes ou não, de onde são, o idioma utilizado e fazendo a análise de sentimentos e identificando as palavras-chaves, para isso. <br>
<br>

 </h3>Serviços de bot do Azure: </h3>

<p>É visado no momento em que se é necessário dar um retorno ao usuário/cliente sobre alguma dúvida, através de sac.</p>
<br>

- Plataforma baseada em nuvem para desenvolvimento e gerenciamento de bots<br>
- Integração com AI Language e outros serviços<br>
- Conectividade através de vários canais<br>

<br>
 </h3>Compreensão da linguagem coloquial: </h3><br>

- Enunciado(declaração no contexto do que quero que faça)<br>
- Entidade (item específico: automação)<br>
- Intencional(identifica a ação)<br>


 </h3>-Reconhecimento e síntese da fala </h3><br>
<br>

- Usa recurso de fala para texto do serviço Fala para transcrever fala audível em texto.

- Usa os recursos de conver~sao de texto em fala do Serviço de Fala para gerar fala audível a partir de texto.


<br>
<br>

<b><i>Para realizar a análise de sentimentos com o Language Studio:</i></b><br>
No portal, cria uma novo recurso, vai em AI + Machine Learning e clica em Análise de Texto (ou Language service se a página estiver em inglês), em seguida clica em Continue to create your resource e logo após, só seleciona as opções que a aplicação pede, como o grupo de recursos (Resource group), nome(name) e tipo de preço (Pricing tier), ticar a caixinha com o termo de responsabilidade de uso da IA e por último clicar em Examinar + criar (Review + create)<br>
<br>

![Imagem do WhatsApp de 2024-04-11 à(s) 02 16 35_ec84110d](https://github.com/Edivania88Duarte/-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/120994730/dfa68d02-5ab0-4c0d-9e5e-5f8b051c384b)

<br>

![Imagem do WhatsApp de 2024-04-11 à(s) 02 41 11_b9d8e1aa](https://github.com/Edivania88Duarte/-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/120994730/1320991c-7e45-4493-b85c-2c8187b55be8)

<br>

É necessário aguardar a validação do recurso. Finalizado o deploy, clica em Go to Speech Studio.
<br>

![Imagem do WhatsApp de 2024-04-11 à(s) 02 44 15_dbe3abf4](https://github.com/Edivania88Duarte/-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/120994730/abf9d953-74e4-4077-ade8-69498566f1f5)

<br>

![Imagem do WhatsApp de 2024-04-11 à(s) 02 51 25_5d2ce62b](https://github.com/Edivania88Duarte/-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/120994730/743fb912-f5ca-488e-b24e-034227ca3c0a)

<br>


Ao ir para a o studio, é necessário ticar nas opçoes em branco para selecionar o que está dentro das caixinhas, inclusive o recurso que acabou de ser criado e em seguida em Classify Text e em Analyse sentimental and mine opinions. 
<br>

![Imagem do WhatsApp de 2024-04-11 à(s) 02 55 18_22f70898](https://github.com/Edivania88Duarte/-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/120994730/97b7ca47-5d47-4661-8427-e2562f0f0955)

<br>
E então, ir em <b>Text</b> para selecionar o idioma, escrever ou colar o texto que deseja fazer a análise de sentimentos e clicar em <b>Run</b>. A análise identificará palavras-chave e fará as conexões para identificar que tipo de sentimento o usuário está exprimindo, seja ele negativo, neutro ou positivo.<br>
<br>

![feedback](https://github.com/Edivania88Duarte/-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/120994730/e5377a9d-6d5e-4d03-9772-22854a22f8e5)

<br> 


![Imagem do WhatsApp de 2024-04-11 à(s) 04 40 15_902a3ba3](https://github.com/Edivania88Duarte/-Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/120994730/856d792a-33f7-458c-8f92-93142f008b41)



