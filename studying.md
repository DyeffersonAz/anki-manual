Estudando
========

Quando você tiver encontrado um baralho que goste ou adicionado algumas notas, chegou a hora de começar a estudar.

Baralhos
-----

O estudo no Anki é limitado ao baralho que está atualmente selecionado bem como a qualquer sub-baralho que ele contenha.

Na tela dos baralhos, seus baralhos serão exibidos em uma lista. Nela há duas colunas numéricas: 'pendente' e 'novo'. 'Pendente' é a contagem de cartões em estudo que está aguardando revisão. 'Novo' é o número de cartões novos que estão prontos para serem estudados naquele dia.

Quando você clica em um baralho ele se tornará o 'baralho atual' e o Anki vai mudar para a tela de estudo. Você pode retornar para a lista de baralhos e mudar o baralho atualmente selecionado a qualquer momento clicando em "Baralhos" no topo da janela principal. (Você também pode usar a ação Estudar Baralho no menu para selecionar um novo deck utilizando o teclado, ou você pode pressionar o botão 's' para estudar o baralho atualmente selecionado)

Você pode pressionar o botão de engrenagem no lado direito do baralho para renomeá-lo, apagá-lo, mudar suas opções ou exportá-lo.

Quando um baralho tem sub-baralhos, os cartões destes aparecerão conjuntos [cada baralho por vez](studying.md#ordem-de-exibição).

Visão Geral do Estudo
--------------

Depois de clicar num baralho para estudá-lo, você verá uma tela que demonstra quantos cartões estão pendentes no dia de hoje. Isso é chamado de tela de 'visão geral'.
Os cartões são divididos em três tipos:

-   **Novo** refere-se aos cartões que você baixou ou inseriu, mas que nunca foram estudados antes.
    
-   **Estudando** faz referência aos cartões que foram vistos pela primeira vez recentemente e continuam sendo estudados.
    
-   **A rever** diz respeito aos cartões que foram previamente estudados e agora precisam ser revisados para que você não os esqueça.

Para iniciar uma sessão de estudo, clique no botão **Estudar Agora**. O Anki irá proceder para exibir-lhe cartões até que acabem aqueles a serem exibidos no dia.

Enquanto estiver estudando, você pode retornar à visão geral ao pressionar a tecla “s” no seu teclado.

Questões
---------

Quando um cartão é exibido, apenas a questão é apresentada primeiro. Depois de pensar sobre a resposta, você tanto pode clicar no botão **Mostrar Resposta**, quando pressionar a barra de espaço no teclado. A resposta então será exibida. Está tudo bem se você precisar de algum tempo para lembrar da resposta, mas via de regra se você não puder responder dentro de 10 segundos, provavelmente é melhor você desistir e exibir a resposta do que ficar sofrendo para recordá-la.

Quando a resposta é apresentada, você deve comparar a resposta que você pensou com a resposta que foi exibida e informar ao Anki o qual bem você lembrou. Se você não tem confiança em comparar sua resposta com exatidão, você pode pedir que o Anki [solicite que você digite a resposta](templates/fields.md#checking-your-answer) ao invés de apenas exibir para você.

O número de botões disponíveis para avaliar a resposta depende se o cartão está sendo 'aprendido' ou 'revisado'.

Aprendizagem
--------

Seja aprendendo novos cartões, seja revisando cartões que você tenha esquecido, o Anki irá exibir os cartões uma ou mais vezes para ajudá-lo a memorizá-los. Cada passo desse é chamado de 'etapa de aprendizado'. Por padrão há duas etapas: 1 minuto e 10 minutos. Você pode mudar o número de etapas e o intervalo entre elas nas [opções do baralho](deck-options.md).

Há três botões de classificação quando estiver estudando:

**Errei** move o cartão de volta para a primeira etapa.

**Bom** coloca o cartão na próxima etapa. Se o cartão já estiver na última etapa, então ele será convertido num cartão de revisão (ele é promovido). Por padrão, uma vez que o cartão tenha alcançado o fim das etapas de aprendizagem, o cartão será novamente exibido no próximo dia, e então sucessivamente em intervalos cada vez mais longos (veja a próxima seção).

**Fácil** o cartão é imediatamente convertido em cartão de revisão, mesmo que ainda lhe faltem etapas. Por padrão, o cartão será exibido novamente 4 dias mais tarde, e então em intervalos cada vez mais longos. O botão Fácil não será exibido se você estiver no modo recordação e ele dará o mesmo intervalo que o botão "Bom".

Quando os cartões são vistos pela primeira vez, eles começam na primeira etapa. Isso quer dizer que ao responder  **Bom** a um cartão pela primeira vez, ele será exibido novamente em 10 minutos, e a etapa inicial de um minuto será saltada. Entretanto, de você pressionar Errei o cartão será exibido novamente em 1 minuto.

Você pode usar as teclas 1, 2 e 3 do seu teclado para selecionar um dos botões, onde 1 representa **Errei**. Pressionar a barra de espaço deu teclado irá selecionar **Bom**.

Se não houver cartões a serem exibidos para você, o Anki irá exibir novamente os cartões de aprendizado mesmo que o intervalo deles não tenha decorrido completamente. Se você preferir esperar o intervalo completo de aprendizado, você pode modificar esse comportamento nas [preferências](preferences.md).

Revisando
---------

Quando um cartão foi anteriormente aprendido e está pronto para ser revisado novamente, haverá quatro botões para avaliar sua resposta:

**Errei** marca sua resposta como incorreta e pede ao Anki que exiba o cartão com mais frequência no futuro. O cartão é considerado como 'falha' de memória. Por favor veja a seção [falhas](deck-options.md) para saber mais sobre como os cartões com falha são tratados.

**Difícil** exibe o cartão num período um pouco menor de tempo do que da última vez, e diz ao Anki para exibí-lo mais frequentemente no futuro.

**Bom** informa ao Anki que o último intervalo de tempo foi adequado e a facilidade do cartão não exige ajuste para mais ou para menos. No padrão inicial de facilidade, o cartão será exibido novamente 2,5 vezes mais tarde do que da vez anterior, de modo que caso tenha anteriormente esperado 10 dias para visualizar o cartão, da próxima vez a espera será por volta de 25 dias.

**Fácil** diz ao Anki que você acho o intervalo muito curto. O cartão será agendado para um futuro mais distante do que quando escolhida o botão 'Bom', além de que no futuro o Anki irá agendar o cartão numa frequência menor. Pelo fato de 'Fácil' aumentar rapidamente o intervalo, ele é melhor utilizado apenas nos cartões mais fáceis. Ao invés dele, na maior parte do tempo você deve se encontrar respondendo 'Bom'.

De igual modo como quando estudando os cartões, você pode utilizar os números de 1 a 4 do teclado para selecionar uma resposta. Pressionar a barra de espaço selecionará 'Bom'.

Contagem de Pendências
----------

Quando apenas a pergunta é exibida, o Anki exibe três números parecidos com 12 + 34 + 56 na parte inferior da tela. Eles representam a contagem de novos cartões, cartões sendo estudados e cartões a revisar. Se você preferir não ver esses números, você pode desativar-los nas preferências do Anki.

No agendador antigo, os números do contador de *revisão* denotam os cartões que precisam ser finalizados na fila, não o número total de *cartões*. Se você tiver múltiplas etapas configuradas para cartões com falha, o número irá crescer em mais de um quando você falhar um cartão, já que o cartão precisa ser exibido algumas vezes.

No novo agendador, os números equivalem a *cartões*, então o número irá sempre crescer um por um, independentemente do número de etapas restantes.

Quando a resposta é exibida, o Anki exibe uma estimativa de quando o cartão será exibido da próxima vez sobre cada um dos botões. Se você preferir não ver essas estimativas, você pode desabilitá-las nas [preferencias](preferences.md) do Anki.

Além disso o Anki adiciona uma pequena quantidade de variação aleatória nos próximos períodos, isso para evitar que os cartões sejam introduzidos juntos e sempre avaliados da mesma forma por sempre estarem próximos uns dos outros. Essa variação não é exibida nos tempos estimados mas será aplicada depois da seleção do botão.

Editando e Mais
----------------

Você pode clicar no botão **Editar** na parte inferior esquerda para editar a nota atual. Quando terminar a edição, você retornará ao estudo. A tela de edição funciona semelhantemente à tela [Adicionar Notas](editing.md).

Na parte inferior direita da tela de revisão há um botão entitulado **Mais**.
Este botão disponibiliza algumas outras operações que você pode fazer no cartão ou nota atuais:

Marcar Nota  
Adiciona uma etiqueta “marcado” à nota atual, de modo que seja mais fácil encontrá-la no navegador. Isso lhe será útil quando quiser fazer algo com a nota mais tarde, como procurar por uma palavra quando chegar em casa. Cartões marcados também exibem uma pequena estrela no canto extremo superior direito durante as revisões.

Ocultar Cartão / Nota  
Retira da revisão o cartão ou todos os cartões da nota até o próximo dia.
(Se você quiser desocultar os cartões antes disso, você pode fazê-lo clicando no botão “desocultar” na parte inferior da tela de [Visão Geral do Baralho](studying.md#visão-geral-do-estudo).) É conveniente para quando você não pode responder o cartão naquele momento ou deseja voltar para ele numa outra ocasião. A ocultação também pode [acontecer automaticamente](studying.md#irmãos-e-ocultação) para cartões de uma mesma nota. Se cartões estiverem sendo aprendidos quando eles foram ocultados, eles são devolvidos para as filas "cartões novos" ou "revisão" antes de serem ocultados.

Suspender Cartão / Nota  
Retira da revisão o cartão ou todos os cartões da nota até que eles sejam manualmente restabelecidos ( ao clicar no botão de suspender no navegador). É útil quando você tem interesse em deixar de revisar determinada nota por um tempo, mas não quer apagá-la. Se os cartões estiverem sendo aprendidos quando eles forem suspensos, eles serão devolvidos para as filas "cartões novos" ou "revisão" antes de serem suspensos.

Apagar Nota  
Apaga a nota e todos os seus cartões.

Opções  
Edita as opções do baralho atual.

Repetir Audio  
Se o cartão possui um áudio na frente ou no verso, toca ele novamente.

Record Own Voice  
Record from your microphone for the purposes of checking your
pronunciation. This recording is temporary and will go away when you
move to the next card. If you want to add audio to a card permanently,
you can do that in the edit window.

Replay Own Voice  
Replay the previous recording of your voice (presumably after showing
the answer).

Ordem de Exibição
-------------

Studying will show cards from the selected deck and any decks it
contains. Thus, if you select your “French” deck, the subdecks
“French::Vocab” and “French::My Textbook::Lesson 1” will be shown as
well.

For new cards and reviews, Anki fetches cards from the decks in
alphabetical order. So in the above example, you would get cards first
from “French”, then “My Textbook”, and finally “Vocab”. You can use this
to control the order cards appear in, placing high priority cards in
decks that appear higher in the list. When computers sort text
alphabetically, the “-” character comes before alphabetical characters,
and “\\~” comes after them. So you could call the deck “-Vocab” to make
them appear first, and you could call the other deck “~My Textbook” to
force it to appear after everything else.

New cards and reviews are fetched separately, and Anki won’t wait until
both queues are empty before moving on to the next deck, so it’s
possible you’ll be exposed to new cards from one deck while seeing
reviews from another deck, or vice versa. If you don’t want this, click
directly on the deck you want to study instead of one of the parent
decks.

Since cards in learning are somewhat time-critical, they are fetched
from all decks at once and shown in the order they are due.

To control the order reviews from a given deck appear in, or change new
cards from ordered to random order, please see the [deck
options](deck-options.md). For more fine-grained ordering of new cards, you
can change the order in the [browser](browsing.md).

Irmãos e Ocultação
--------------------

Recall from [the basics](getting-started.md) that Anki can create more than one
card for each thing you input, such as a front→back card and a
back→front card, or two different cloze deletions from the same text.
These related cards are called 'siblings'.

When you answer a card that has siblings, Anki can prevent the card’s
siblings from being shown in the same session by automatically 'burying'
them. Buried cards are hidden from review until the clock rolls over to
a new day or you manually unbury them using the “Unbury” button that’s
visible at the bottom of the [deck overview](studying.md#study-overview) screen. Anki
will bury siblings even if the siblings are not in the same deck (for
instance, if you use the [deck override](templates/intro.md) feature).

You can enable burying from the [deck options](deck-options.md) screen -
there are separate settings for new cards and reviews.

Anki will only bury siblings that are new or review cards. It will not
hide cards in learning, as time is of the essence for those cards. On
the other hand, when you study a learning card, any new/review siblings
will be buried.

Keyboard Shortcuts
------------------

Most of the common operations in Anki have keyboard shortcuts. Most of
them are discoverable in the interface: menu items list their shortcuts
next to them, and hovering the mouse cursor over a button will generally
show its shortcut in a tooltip.

When studying, either space or enter will show the answer. When the
answer is shown, you can use space or enter to select the Good button.
You can use the 1-4 keys to select a specific ease button. Many people
find it convenient to answer most cards with space and keep one finger
on 1 for when they forget.

The "Study Deck" item in the Tools menu allows you to quickly switch to
a deck with the keyboard. You can trigger it with the '/' key. When
opened, it will display all of your decks and show a filter area at the
top. As you type characters, Anki will display only decks matching the
characters you type. You can add a space to separate multiple search
terms, and Anki will show only decks that match all the terms. So “ja 1”
or “on1 ja” would both match a deck called “Japanese::Lesson1”.

Falling Behind
--------------

If you fall behind in your reviews, Anki will prioritize cards that have
been waiting the longest. It does this by taking the the cards that have
been waiting the longest and showing them to you in a random order up
until your daily review limit. This ordering ensures that no cards will
be left waiting indefinitely, but it means that if you introduce new
cards, their reviews won’t appear until you’ve gotten through your
backlog.

If you wish to change the order of the overdue reviews, you can do so by
creating a [filtered deck](filtered-decks.md).

When you answer cards that have been waiting for a while, Anki factors
in that delay when determining the next time a card should be shown.
Please see the section on Anki’s spaced-repetition
[algorithm](faqs.md) for more information.
