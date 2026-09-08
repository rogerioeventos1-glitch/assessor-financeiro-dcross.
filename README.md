# Assessor Financeiro D'Cross

Aplicativo web/PWA local para controle financeiro.

## Rodar
1. Instale Node.js 18+.
2. `npm install`
3. `npm run dev`

## Build
`npm run build`

## Recursos
- Entradas e saídas por categoria
- Saldo e totais do mês
- Busca e filtros
- Lançamento por voz (SpeechRecognition quando suportado pelo navegador)
- Captura de comprovante pela câmera com preenchimento manual seguro
- Backup/exportação e importação JSON
- Dados persistidos no localStorage

## IA para comprovantes
A leitura automática por IA não deve ser feita diretamente no navegador com uma chave secreta. Para habilitá-la, conecte um endpoint backend/serverless que receba a imagem e chame o provedor de IA usando a chave apenas no servidor.
