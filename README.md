<h1 align="center">
  Copa do Mundo de 2022 📱


## 💻 Projeto

Sou Fernando Rubini e este repositório foi criado para o Bootcamp Santander 2023: Criar um App com listagem e notificações dos jogos da Copa do Mundo de 2022 da DIO.
Aplicativo Android desenvolvido com Kotlin e o projeto foi criado com fins de estudo e prática de arquitetura moderna, consumo de APIs REST e uso de componentes do Android Jetpack.

## 📱 Funcionalidades

- Lista de seleções participantes
- Visualização de jogadores por time
- Detalhes de partidas e resultados
- Interface intuitiva e responsiva com Jetpack Compose
- Integração com API REST para dados em tempo real (ou mockados)

## 🧱 Arquitetura

O app segue uma arquitetura limpa baseada em **MVVM** com separação de camadas:

- `data`: fontes de dados, repositórios, models
- `domain`: casos de uso
- `presentation`: telas, estados e ViewModels
- `di`: injeção de dependências com Koin

## 🛠️ Tecnologias Utilizadas

- **Kotlin**
- **Android Jetpack (ViewModel, LiveData, Navigation, Compose)**
- **Retrofit** para chamadas de API
- **Koin** para injeção de dependência
- **Room** (se houver persistência local)
- **Jetpack Compose** para UI declarativa
- **Coroutines + Flow** para programação assíncrona

## 🚀 Como rodar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/fernandorubini/Copa2022.git




