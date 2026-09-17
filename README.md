# 🔎 Mergulho nos Fundamentos de Testes de Software

Este repositório contém o trabalho **“Mergulho nos Fundamentos de Testes de Software”**, desenvolvido como atividade de pesquisa do curso Técnico em Desenvolvimento de Sistemas do **SENAI A. Jacob Lafer**.

O trabalho apresenta conceitos fundamentais relacionados à qualidade e aos testes de software, relacionando a parte teórica com situações práticas e casos reais.

## 📚 Sobre o projeto

O estudo aborda diferentes conceitos de testes de software e demonstra sua importância durante o desenvolvimento e a manutenção de sistemas.

Entre os principais assuntos estudados estão:

* Testes de software
* Testes unitários
* Testes de integração
* Testes de sistema
* Testes de aceitação
* Testes de regressão
* Requisitos funcionais
* Requisitos não funcionais
* Testes de estresse
* Qualidade de software

## 💻 Conteúdo do trabalho

### 1. O custo do erro

Foi analisado o incidente ocorrido em **19 de julho de 2024**, envolvendo uma atualização do **CrowdStrike Falcon** que provocou falhas em computadores com Windows.

O estudo apresenta:

* A causa técnica do problema;
* Os impactos financeiros e operacionais;
* A relação do incidente com os diferentes níveis de teste;
* A importância de testes de integração, sistema, estabilidade, stress testing, fuzzing e fault injection.

A análise mostra como um problema em um componente de software pode gerar impactos em grande escala.

### 2. Requisitos funcionais e não funcionais

Foi utilizado o **WhatsApp** como exemplo para diferenciar requisitos funcionais e não funcionais.

#### Requisitos funcionais

Exemplos analisados:

* Envio de mensagens de texto;
* Envio de imagens e arquivos;
* Realização de chamadas de voz e vídeo.

#### Requisitos não funcionais

Foram considerados aspectos como:

* Baixa latência;
* Segurança;
* Estabilidade;
* Disponibilidade;
* Capacidade de suportar grande quantidade de usuários e mensagens.

### 3. Teste de estresse

Também foi elaborado um cenário de teste de estresse para avaliar o comportamento de um aplicativo diante de uma grande quantidade de usuários simultâneos.

A proposta considera cargas progressivas de usuários virtuais e monitora fatores como:

* Tempo de resposta;
* Taxa de erros;
* Mensagens processadas;
* Uso de CPU;
* Uso de memória;
* Uso da rede;
* Filas de processamento;
* Capacidade de recuperação do sistema.

### 4. Teste unitário x teste de integração

O trabalho apresenta a diferença entre os dois níveis:

**Teste unitário:** verifica uma pequena parte do software de maneira isolada, como uma função, método ou componente.

**Teste de integração:** verifica se diferentes componentes funcionam corretamente quando conectados.

Os dois tipos são complementares e ajudam a encontrar diferentes categorias de problemas.

### 5. Teste de regressão

O teste de regressão verifica se funcionalidades que já funcionavam continuam funcionando depois de uma alteração no sistema.

Um exemplo apresentado é a implementação de uma função de **“Esqueci minha senha”**, que pode alterar partes do login, navegação, banco de dados ou autenticação.

Depois da alteração, os testes anteriores devem ser executados novamente para verificar se nenhuma funcionalidade existente foi prejudicada.

## 🎯 Objetivos

* Compreender os fundamentos de testes de software;
* Identificar diferentes níveis e tipos de teste;
* Diferenciar requisitos funcionais e não funcionais;
* Compreender a importância dos testes durante o desenvolvimento;
* Analisar um caso real de falha de software;
* Entender a importância dos testes de regressão;
* Relacionar conceitos teóricos com situações práticas.

