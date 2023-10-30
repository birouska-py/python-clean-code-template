# Template de Projeto Python com Clean Code

Este é um template de projeto Python que segue os princípios do Clean Code e organiza o código em camadas separadas em pastas para manter a clareza e a organização do código. Essa estrutura é adequada para projetos Python de média a grande escala.

## Estrutura do Projeto

O projeto é organizado da seguinte forma:
```javascript
my_project/ 
│
├── app/
│   ├── __init__.py
│   ├── main.py
│   │
│   ├── domain/
│   │   ├── __init__.py
│   │   ├── model1.py
│   │   ├── model2.py
│   │   ├── ...
│   │
│   ├── services/
│   │   ├── __init__.py
│   │   ├── service1.py
│   │   ├── service2.py
│   │   ├── ...
│   │
│   ├── interfaces/
│   │   ├── __init__.py
│   │   ├── interface1.py
│   │   ├── interface2.py
│   │   ├── ...
│   │
│   ├── controllers/
│   │   ├── __init__.py
│   │   ├── controller1.py
│   │   ├── controller2.py
│   │   ├── ...
│
├── tests/
│   ├── __init__.py
│   │
│   ├── test_domain/
│   │   ├── __init__.py
│   │   ├── test_model1.py
│   │   ├── test_model2.py
│   │   ├── ...
│   │
│   ├── test_services/
│   │   ├── __init__.py
│   │   ├── test_service1.py
│   │   ├── test_service2.py
│   │   ├── ...
│   │
│   ├── test_controllers/
│   │   ├── __init__.py
│   │   ├── test_controller1.py
│   │   ├── test_controller2.py
│   │   ├── ...
│
├── data/
│   ├── ...
│
├── requirements.txt
├── README.md
├── .gitignore

```

- `app/`: Esta pasta contém o código-fonte da aplicação e é organizada em várias camadas:

    - `domain/`: Contém os modelos de dados (por exemplo, classes que representam objetos de negócios).

    - `services/`: Contém a lógica de negócios e os serviços da aplicação.

    - `interfaces/`: Contém definições de interfaces ou contratos para componentes do sistema.

    - `controllers/`: Contém os pontos de entrada da aplicação.

- `tests/`: Aqui estão localizados os casos de teste correspondentes às diferentes camadas da aplicação. A estrutura de pastas dos testes segue a mesma organização do código-fonte.

- `data/`: Este diretório é destinado para armazenar dados usados pela aplicação, como arquivos de configuração, arquivos de entrada e saída, etc.

- `requirements.txt`: Lista as dependências do projeto que podem ser instaladas com `pip install -r requirements.txt`.

- `README.md`: Este arquivo, que você está lendo agora, fornece uma visão geral do projeto, sua estrutura e como configurar e executar a aplicação.

- `.gitignore`: Este arquivo lista os arquivos e diretórios que devem ser ignorados ao usar o Git para controle de versão.

## Como Usar

Para usar este template de projeto:

1. Clone ou faça o download deste repositório.

2. Personalize a estrutura do projeto de acordo com as necessidades do seu próprio projeto.

3. Desenvolva seu código-fonte dentro da pasta `app/`, seguindo os princípios do Clean Code.

4. Crie casos de teste correspondentes na pasta `tests/` para garantir a qualidade do código.

5. Atualize o arquivo `requirements.txt` com as dependências do seu projeto.

6. Documente seu projeto no arquivo `README.md`.

## Contribuindo

Fique à vontade para contribuir com melhorias, correções de bugs e outras alterações. Basta abrir uma issue ou enviar um pull request.

## Licença

Este template de projeto é disponibilizado sob a licença [MIT](LICENSE).
