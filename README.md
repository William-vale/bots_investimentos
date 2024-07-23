# Bot Python Invest

## Objetivo

Este projeto tem como objetivo criar um bot de investimento utilizando Python, que realiza compras e vendas de ativos de forma automática, acessando sites e plataformas de trading como se fosse uma pessoa. O bot será configurado para comprar e vender ativos com base em análises de mercado e indicadores técnicos.

## Configuração do Ambiente

Para configurar o ambiente de desenvolvimento, siga os passos abaixo:

1. Crie um diretório para o projeto e navegue até ele:
    
    ```
    mkdir investment_bot
    cd investment_bot
    ```
    
2. Crie um ambiente virtual:
    
    ```
    python -m venv [nome_ambiente_virtual]
    ```
    
3. Ative o ambiente virtual:
    - No Windows:
        
        ```
        .\venv\Scripts\activate
        ```
        
    - No macOS/Linux:
        
        ```
        source venv/bin/activate
        ```
        
4. Instale as bibliotecas necessárias:
    
    ```
    pip install requests beautifulsoup4 pandas numpy scikit-learn selenium
    ```
    

## Ativos com Altos Dividendos

### Ações com Dividendos Acima de 6% ao Ano

- **Banco do Brasil (BBAS3)**: Dividend Yield de aproximadamente 7.5%
- **Taesa (TAEE11)**: Dividend Yield de aproximadamente 8%
- **Engie Brasil (EGIE3)**: Dividend Yield de aproximadamente 6.5%
- **Transmissora Aliança de Energia Elétrica (TAEE11)**: Dividend Yield de aproximadamente 7.2%
- **Copel (CPLE6)**: Dividend Yield de aproximadamente 6.8%

### Fundos de Investimento Imobiliário (FIIs) com Dividendos Acima de 10% ao Ano

- **HGLG11 (CSHG Logística)**: Dividend Yield de aproximadamente 10.5%
- **KNCR11 (Kinea Rendimentos Imobiliários)**: Dividend Yield de aproximadamente 11%
- **MXRF11 (Maxi Renda)**: Dividend Yield de aproximadamente 10.8%
- **HCTR11 (Hectare CE)**: Dividend Yield de aproximadamente 12%
- **XPML11 (XP Malls)**: Dividend Yield de aproximadamente 10.2%

## Estrutura do Projeto

O projeto está organizado nas seguintes etapas:

1. **Definição do Projeto e Configuração do Ambiente**
2. **Coleta de Dados**
3. **Análise de Dados e Desenvolvimento de Algoritmo de Trading**
4. **Automação de Navegação**
5. **Integração do Algoritmo com a Automação de Navegação**
6. **Gerenciamento de Sessões e Erros**
7. **Monitoramento e Logs**
8. **Testes e Validação**
9. **Implantação**
10. **Manutenção e Atualização**

## Como Contribuir

1. Faça um fork do repositório.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`).
4. Faça push para a branch (`git push origin feature/nova-feature`).
5. Crie um novo Pull Request.

## Licença

Este projeto é licenciado sob a MIT License.

---

Este README serve como um guia inicial para configurar o ambiente e listar ativos com altos dividendos. Conforme o projeto avança, este documento será atualizado com mais informações detalhadas sobre cada etapa.