# 🌤 Condições do Tempo

Este é um projeto simples que utiliza HTML, CSS e TypeScript para exibir informações sobre o clima de uma determinada localização, utilizando a API do OpenWeatherMap.

## 📋 Descrição

O projeto permite ao usuário pesquisar por uma cidade e visualizar as condições climáticas atuais, incluindo:
- Nome da cidade.
- Temperatura em graus Celsius.
- Ícone representando as condições climáticas (sol, chuva, nuvens, etc.).

## 🚀 Funcionalidades

- Pesquisa de clima por localização.
- Integração com a API do OpenWeatherMap para obter dados climáticos em tempo real.
- Tratamento de erros, como entradas inválidas e falhas na obtenção de dados.

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estruturação da página.
- **CSS3**: Estilização da interface.
- **TypeScript**: Lógica para buscar e exibir os dados do clima.
- **API OpenWeatherMap**: Obtenção de dados meteorológicos.

## 🔧 Como Utilizar

### Pré-requisitos
- Navegador atualizado.
- Conexão com a internet para acessar a API.

### Passo a Passo
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd seu-repositorio
   ```
3. Abra o arquivo `index.html` em seu navegador.

4. Digite o nome de uma cidade no campo de pesquisa e clique em "Pesquisar".

5. Visualize as informações do clima.

### Configuração da API
Certifique-se de substituir a chave da API no arquivo `index.ts` pela sua chave pessoal obtida no site [OpenWeatherMap](https://openweathermap.org/api):

```typescript
const response = await fetch(`https://api.openweathermap.org/data/2.5/weather?q=${localizacao}&appid=SUA_API_KEY&lang=pt_br&units=metric`);
```

## 🖼️ Interface

A interface possui os seguintes elementos:
- **Campo de pesquisa**: Para inserir o nome da cidade.
- **Botão de pesquisa**: Para enviar a consulta.
- **Seção de informações**: Exibe os dados climáticos obtidos.

## 💡 Melhorias Futuras

- Adicionar um design mais avançado usando frameworks como Bootstrap ou Tailwind CSS.
- Exibir dados adicionais, como umidade, velocidade do vento e previsão para os próximos dias.
- Implementar suporte a múltiplos idiomas.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais informações.
