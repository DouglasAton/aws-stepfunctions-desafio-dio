# __AWS Step Functions__

O Step Functions é um serviço da AWS que permite criar fluxos de trabalho de forma visual e prática, ajudando os desenvolvedores a criarem aplicações, desde as mais simples até as mais complexas, utilizando apenas o "arrastar" e "configurar". 
Ele funciona como um organizador de tarefas, onde você pode definir uma série de passos que precisam acontecer em uma ordem específica, testando condições, realizando tarefas em paralelo e até retornando para refazê-las, conforme necessário.

Além disso, o Step Functions se integra a diversos serviços oferecidos pela AWS, como IAs generativas e AWS Lambda, que gerencia automaticamente os recursos de computação do seu código. O serviço permite criar condições para tomar decisões 
baseadas em suas preferências e oferece a capacidade de executar várias etapas simultaneamente, garantindo que o processo seja eficiente e flexível.
<https://aws.amazon.com/pt/step-functions/>

# __ASL__

A ASL (Amazon States Language) é a linguagem usada "por trás" de toda a mágica dos fluxos de trabalho no Step Functions, tornando o processo de criação mais controlável e previsível. 
Ela utiliza o formato JSON, que é um tipo de arquivo de texto muito simples e organizado em chaves e valores. Isso permite que você acompanhe facilmente cada etapa, sabendo exatamente o que vai acontecer e quando. 
Além disso, a ASL possibilita definir cada passo do seu fluxo de trabalho usando um conjunto de regras fáceis de ler e escrever.
<https://docs.aws.amazon.com/step-functions/latest/dg/concepts-amazon-states-language.html>

# __Aprendizado__

Imagine que você está criando uma aplicação para um processo de delivery (como no exemplo do nosso ilustre instrutor Felipe Aguiar, da DIO). Nesse fluxo no Step Functions, você pode começar pedindo sugestões para um jantar romântico, 
onde a IA generativa oferece opções de pratos e sugere acompanhamentos. Após definir a refeição, a IA te orienta sobre qual bebida combina melhor com o prato, e, por fim, sugere até o local ideal para o jantar.
Tudo isso ocorre com uma etapa sendo executada após a outra, e o Step Functions garante que o fluxo seja coordenado de maneira eficiente. 
