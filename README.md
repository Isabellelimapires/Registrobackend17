# RouteWise Backend

## Introdução
Este projeto faz parte do desafio proposto para a Semana 17 do curso. O objetivo é desenvolver um serviço de backend para a startup fictícia "RouteWise", responsável por otimizar entregas e rotas de logística.  
A aplicação foi desenvolvida utilizando Node.js com o framework Express e faz integração com a API do OpenRouteService para calcular rotas entre dois pontos.

---

## Escolha do Framework
O framework escolhido foi o **Express (Node.js)**.  
A escolha se justifica pelos seguintes motivos:
- É minimalista e flexível, permitindo construir APIs de maneira rápida e organizada.  
- Possui uma grande comunidade, ampla documentação e suporte em diversas bibliotecas.  
- É indicado para serviços que precisam de endpoints simples e escaláveis, como no caso deste projeto.  

---

## Integração com API de Terceiros
O serviço de terceiros utilizado foi a **OpenRouteService API**, que oferece recursos de cálculo de rotas, distância e tempo de percurso.  
A integração foi feita de forma direta, utilizando chamadas HTTP com a biblioteca Axios.  

Sobre a forma de integração:  
- **API Direta:** permite realizar requisições HTTP diretamente para o serviço, controlando os parâmetros e os retornos da forma mais flexível possível.  
- **SDK (quando disponível):** encapsula funcionalidades em bibliotecas prontas, simplificando o uso, mas reduzindo a flexibilidade.  
Neste projeto, optou-se pela utilização da **API direta** por não haver necessidade de um SDK mais complexo.  

---

## Estrutura do Projeto

