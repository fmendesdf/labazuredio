
# Introdução ao Azure Cognitive Services for Language

O objetivo desta atividade foi aprender os conceitos de serviços na nuvem, com foco nos recursos da **Azure**, especialmente no **processamento de linguagem natural** por meio do **Azure Cognitive Services for Language**.

A prática foi dividida em 4 etapas principais:

1. Criação da conta Azure  
2. Criação do grupo de recursos e configuração dos serviços  
3. Teste do **Speech-to-Text (STT)** no **Speech Studio**  
4. Teste da **Análise de Sentimentos** no **Language Studio**

---

## 1. Conta Azure

Acesse: [https://portal.azure.com](https://portal.azure.com)

O primeiro passo foi a criação da conta na plataforma. Durante o processo, avaliamos as opções de planos disponíveis:

- **Plano pré-pago**  
- **Plano pós-pago com crédito de $200 por 30 dias**

Ambas opções incluem uma cota gratuita de serviços, suficiente para os testes propostos em laboratório. A opção escolhida foi o **plano pré-pago**.

Após preencher os dados cadastrais e adicionar o cartão de crédito, realizamos a criação do **Resource Group**, configuração de autenticação e geração das chaves de acesso.

> O **Resource Group** é uma unidade lógica usada para organizar e gerenciar os recursos da Azure. Ele funciona como um "container" onde agrupamos diferentes serviços (como bancos de dados, APIs de IA, etc).

O primeiro recurso criado foi um **serviço de Language**, localizado dentro da seção de **Inteligência Artificial (IA)** da Azure.

---

## 2. Teste com Speech-to-Text (TTS)

Acesse: [https://speech.microsoft.com](https://speech.microsoft.com)

No **Speech Studio**, após aceitar os termos de uso e vincular a conta ao recurso criado anteriormente, exploramos a funcionalidade de **conversão de fala em texto**.

> A ferramenta permite gravar ou carregar um áudio e visualizar a transcrição em tempo real, além de oferecer a opção de tradução simultânea para outros idiomas.

Além disso, há instruções claras sobre como integrar o serviço em aplicações próprias, incluindo links diretos para repositórios no **GitHub**, com exemplos de código e configuração de chaves.

---

## 3. Teste com Análise de Sentimento

Acesse: [https://language.cognitive.azure.com](https://language.cognitive.azure.com)

Utilizando o **Language Studio**, realizamos uma configuração semelhante à do Speech Studio e exploramos duas opções:

- **Classificação de Textos**  
- **Análise de Sentimentos e Opiniões**

Essas ferramentas permitem colar um texto e obter como resultado:

- O sentimento predominante (positivo, neutro ou negativo)
- Palavras-chave identificadas
- Probabilidades atribuídas a cada interpretação
- Separação por sentença, com análise individual

> Foi possível compreender como o serviço pode ser integrado a sistemas que necessitem entender a opinião de usuários, como avaliações, comentários em redes sociais ou atendimento ao cliente.

---

## Conclusão

A prática foi essencial para entender o funcionamento da **plataforma Azure**, desde a criação da conta até a integração de serviços de IA, com foco em **Speech-to-Text** e **Análise de Sentimento**. Além de configurar e testar os serviços, também tivemos contato com a documentação e exemplos de código, o que facilita muito a aplicação prática em projetos reais.
