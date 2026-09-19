# VanguardFX IA — Frontend

Frontend React/TypeScript/Vite para o backend Python/FastAPI real.

## Instalação
npm install
cp .env.example .env
npm run dev

## Configuração
VITE_API_BASE_URL define a URL do FastAPI. VITE_WS_URL define o WebSocket.

## Regras
Sem mock/fake data, Supabase, Render ou secrets no navegador. O backend é a fonte de verdade. Endpoints ausentes nunca são simulados.

## Build
npm run build

## CORS
O backend precisa permitir a origem do frontend.