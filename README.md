# Docker & Kubernetes

# Arquitetura

![Visão Geral](https://github.com/joaovictorino/docker-k8s-voting-app/blob/master/docs/architecture.png?raw=true)

## Instalação Docker, Kubernetes e VSCode

[VSCode no Windows](https://www.youtube.com/watch?v=57iaJtuKL_I)  
[Docker Desktop e Kubernetes no Windows](https://www.youtube.com/watch?v=n0bxjsGi_BY)  
[Docker e Kubernetes no WSL](https://www.youtube.com/watch?v=Ow8LM3mkGmY)

# Docker

## Docker Online

[Playground](https://labs.play-with-docker.com/)

# Kubernetes

## Kubernetes Online

[Playground](https://labs.play-with-k8s.com/)

## Aula 01

1. [Rode seu primeiro contêiner](https://gist.github.com/joaovictorino/189b7afae55f44564ebef9eb9bee7730)
2. [Arquitetura do Linux e Docker](https://gist.github.com/joaovictorino/e1cde368a99238a83f6bbb5eb9b8229f)
3. [Isolamento de recursos](https://gist.github.com/joaovictorino/e865bf635b0364e71299400c521af397)
4. [Trabalhando com estados de contêineres](https://gist.github.com/joaovictorino/5324443e4abc4375f050d49c8cceb2ae)
5. [Entendendo processos em contêineres](https://gist.github.com/joaovictorino/712fbc15f300566b6b0516a85488d180)
6. [Vamos trabalhar com volumes](https://gist.github.com/joaovictorino/619425106c1f21ff6b05670770695569)
7. [Trabalhando tmpfs e pause](https://gist.github.com/joaovictorino/e3c8215ed62191ff50c66d2d2fe268d4)
8. [Vamos trabalhar com rede (bridge)](https://gist.github.com/joaovictorino/3e34bf4b2b861f4238d339985e4feba7)
9. [Vamos trabalhar com rede (bridge e DNS)](https://gist.github.com/joaovictorino/dcd85caa004a2d5ced3ace1ced5ccaed)
10. [Conectar e desconectar da rede](https://gist.github.com/joaovictorino/fb168f2111d466b298625f41ca30a3e1)
11. [Entendendo as camadas das imagens](https://gist.github.com/joaovictorino/5a49da6c2d4e4fab4fe688ca0d3a1352)
12. [Trabalhando com variáveis de ambiente](https://gist.github.com/joaovictorino/beb740af49c2ca9bccfbe883afa0abaf)
13. [MySQL + redes + volumes](https://gist.github.com/joaovictorino/ecf3dc76b806b7e921ff4c05dcc951c1)

## Aula 02

1. [Vamos criar nossa primeira imagem](https://gist.github.com/joaovictorino/2ee531bb9e7a36938f3ca794af8bd806)
2. [ENTRYPOINT e CMD na execução](https://gist.github.com/joaovictorino/a4fef50a88db6d9db17e3a20f88b92c5)
3. [Entrypoint e CMD na herança](https://gist.github.com/joaovictorino/71f19d17bcf616e6fe04e39595d2ca89)
4. [Entendendo ARG e ENV](https://gist.github.com/joaovictorino/c63171e205e57b2339e051d8e0209a02)
5. [Subindo a imagem no Docker Hub](https://gist.github.com/joaovictorino/6343d11cdb0a7ed79068c8b930c19805)
6. [Criando imagem voting-app](https://gist.github.com/joaovictorino/dce835681c9425b26559942d9518e336)
7. [Criando imagem result-app](https://gist.github.com/joaovictorino/5734d8caad407bed3b8399b3e88c60c3)
8. [Criando imagem worker](https://gist.github.com/joaovictorino/3b2e92583d4486c637c13d0144e667cd)
9. [Juntando todos os contêineres](https://gist.github.com/joaovictorino/6e844fa34b02e889d94cdf15f289e204)
10. [Usando serviços no Docker Compose](https://gist.github.com/joaovictorino/f44f60a6e8c81abde553f8bf51246b5b)
11. [Usando portas no Docker Compose](https://gist.github.com/joaovictorino/3bc0751c8e8f5050d1936f332d5e5e05)
12. [MySQL no Docker Compose](https://gist.github.com/joaovictorino/e3ba761480bc72220d9ca236db5bc475)
13. [Subindo Wordpress com Docker Compose](https://gist.github.com/joaovictorino/38f19f0ef469271704eb328487f9e0d4)
14. [Usando Docker Compose na aplicação](https://gist.github.com/joaovictorino/31fa70ad3010fb01f6fb23dc48c95848)

## Aula 03

1. [Verificando a instalação do k8s](https://gist.github.com/joaovictorino/e8b422eb0dc5124e10d6276759fa8e48)
2. [Rode seu primeiro pod pelo terminal](https://gist.github.com/joaovictorino/6b437968a8e920a21e33c386417f0def)
3. [Trabalhando com IaC no kubectl](https://gist.github.com/joaovictorino/1ed45b988fddbcc1688b42addb7bbb34)
4. [Testando a idempotência](https://gist.github.com/joaovictorino/6443e1cb8f292e351100c5bb5111030a)
5. [Analisando logs e eventos](https://gist.github.com/joaovictorino/3457fe929d95fd52bea0038b7657060b)
6. [Criando um serviço do tipo ClusterIP](https://gist.github.com/joaovictorino/ff5282a1a04f46d29843d95a4d604783)
7. [Criando um serviço do tipo NodePort](https://gist.github.com/joaovictorino/11735e9b6a8bda21f0aa85da103565a7)
8. [Criando um serviço do tipo Ingress](https://gist.github.com/joaovictorino/ec99b17cbb4d4c412f0d10e0ce041b26)
9. [Criando um ReplicaSet](https://gist.github.com/joaovictorino/0fce6038ecaeb58250a1eccdf4bec153)
10. [Criando um Deployment](https://gist.github.com/joaovictorino/a3f9ebbda511a06994ea4bd1e77a932d)
11. [Entendendo imutabilidade](https://gist.github.com/joaovictorino/35d4f6b497b8715d3894cb193a779586)
12. [Algoritmos de implantação](https://gist.github.com/joaovictorino/d1a8e1a5ff0c7970acef354563e92fbc)
13. [Testando a implantação canário](https://gist.github.com/joaovictorino/646fa8e07e25d5b8db3b7520098197c5)
14. [Entendendo o versionamento do deploy](https://gist.github.com/joaovictorino/e9df14fa7364537976deeddbc2878620)

## Aula 04

1. [Escalando os pods do Deployment](https://gist.github.com/joaovictorino/8ad9248a1039106f2fe2d532f64c2bc2)
2. [Trabalhando com HPA](https://gist.github.com/joaovictorino/0ffa240dcf84a3c0b680bab6d4573fe7)
3. [Usando volumes](https://gist.github.com/joaovictorino/004a1dad447d8b79ad24fd96a056e348)
4. [Criando um StatefulSet](https://gist.github.com/joaovictorino/8c8e41822802a0f908e979e78b85b002)
5. [Criando Namespaces](https://gist.github.com/joaovictorino/c1cbaba580794402f676b115cf499626)
6. [Criando um ConfigMap](https://gist.github.com/joaovictorino/897aa460bd79b016dd63cf889f32cf50)
7. [Criando um Secret](https://gist.github.com/joaovictorino/a7a5f2857dd58f7a4fdf23097d26b8d5)
8. [Criando um CronJob](https://gist.github.com/joaovictorino/32720c0e03e2db5a176d8d65771da4cc)
9. [Criando um Job](https://gist.github.com/joaovictorino/d8d386553517cf025d067935aa277698)
10. [Subindo as imagens para o Docker Hub](https://gist.github.com/joaovictorino/a61d0596fab84ebf7cf8358609cf3514)
11. [Subindo fila e banco no Kubernetes](https://gist.github.com/joaovictorino/41b9c7995ddcb7ef3fa6b7ce333fbec7)
12. [Subindo aplicação no Kubernetes](https://gist.github.com/joaovictorino/63ad8d869aecb5aca21330d4660956ca)
13. [Subindo outra aplicação no Kubernetes](https://gist.github.com/joaovictorino/af9ba480acc459e7685cb364a87a606f)
