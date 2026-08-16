# StocKids

Simulador de bolsa para aprender a invertir, con la **historia real** del mercado.

**https://mascochicle.github.io/StocKids/**

## Cómo funciona

Arranca en **enero de 2015** con 1,000 dólares y corre a **un año de bolsa por cada mes de
vida real** — el mundo avanza solo con el calendario, se abra la app o no. Un precio nuevo
cada 14 horas, con los cierres semanales reales de 17 empresas y canastas.

Cada Año Nuevo de bolsa llega una aportación, y las empresas que reparten dividendos los
pagan de verdad, con las cantidades que dieron en su momento.

No es un juego de comprar y vender rápido: eso enseña a apostar. El ritmo lento premia la
paciencia sin sermón — se trata de ver que el mundo se cae y se levanta.

## Los datos

Cierres semanales de Yahoo Finance, ajustados por splits, horneados dentro del archivo: la
app no pide nada a internet ni necesita llaves. Los dividendos van por separado, con lo que
cada empresa pagó realmente.

## La partida

Vive en el navegador del teléfono (`localStorage`) y nunca sale de ahí. Se guardan tres
cosas y ninguna es un saldo: cuándo arrancó, hasta qué semana ha llegado, y cada compra y
venta. El dinero, las ganancias y los dividendos se calculan al vuelo.
