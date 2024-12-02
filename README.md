# Simulador de Loterias - Brasil

Este é um simulador de jogos das loterias federais do Brasil que sincroniza dados com o site da Caixa Econômica Federal.

## Funcionalidades

- Simulação de jogos para Mega-Sena, Lotofácil e Quina
- Atualização automática dos resultados oficiais
- Interface web amigável
- Histórico dos jogos gerados
- Atualização diária dos resultados às 20:00

## Requisitos

- Python 3.8 ou superior
- Pip (gerenciador de pacotes Python)

## Instalação

1. Clone este repositório
2. Instale as dependências:
```bash
pip install -r requirements.txt
```

## Como usar

1. Execute o aplicativo:
```bash
python app.py
```

2. Abra seu navegador e acesse:
```
http://localhost:5000
```

3. Na interface, você pode:
   - Gerar novos jogos para cada loteria
   - Ver os últimos resultados oficiais
   - Acompanhar seu histórico de jogos gerados

## Atualizações

O sistema atualiza automaticamente os resultados das loterias:
- Ao iniciar o aplicativo
- Diariamente às 20:00
- A cada 5 minutos na interface web

## Observações

Este é um simulador para fins de entretenimento. Os números gerados são aleatórios e não garantem qualquer resultado nas loterias oficiais.
