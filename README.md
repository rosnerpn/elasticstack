Elastic Stack com Docker e Docker Compose

[![Elastic Stack version](https://img.shields.io/badge/Elastic%20Stack-8.11.4-00bfb3?style=flat&logo=elastic-stack)](https://www.elastic.co/blog/category/releases)
[![Build Status](https://github.com/deviantony/docker-elk/workflows/CI/badge.svg?branch=main)](https://github.com/deviantony/docker-elk/actions?query=workflow%3ACI+branch%3Amain)
[![Join the chat](https://badges.gitter.im/Join%20Chat.svg)](https://app.gitter.im/#/room/#deviantony_docker-elk:gitter.im)

Este repositório fornece um exemplo de como executar a versão mais recente da pilha Elastic com Docker e Docker Compose.

A pilha Elastic é uma plataforma de análise de dados de código aberto que fornece uma ampla gama de recursos para coletar, analisar e visualizar dados. Os componentes da pilha são:

Elasticsearch - um motor de busca e análise distribuído (https://github.com/elastic/elasticsearch/tree/main/distribution/docker)
Kibana - uma ferramenta de visualização de dados
Beats - coletores de dados
Logstash - um agente de coleta e processamento de dados

Este exemplo usa as [imagens oficiais do Docker] da [Elastic] para criar contêineres para cada componente da pilha.

* [Elasticsearch](https://github.com/elastic/elasticsearch/tree/main/distribution/docker)
* [Logstash](https://github.com/elastic/logstash/tree/main/docker)
* [Kibana](https://github.com/elastic/kibana/tree/main/src/dev/build/tasks/os_packages/docker_generator)