<p align="center">
  <a href="https://builderbot.vercel.app/">
    <picture>
      <img src="https://builderbot.vercel.app/assets/thumbnail-vector.png" height="80">
    </picture>
    <h2 align="center">BuilderBot</h2>
  </a>
</p>



<p align="center">
  <a aria-label="NPM version" href="https://www.npmjs.com/package/@builderbot/bot">
    <img alt="" src="https://img.shields.io/npm/v/@builderbot/bot?color=%2300c200&label=%40bot-whatsapp">
  </a>
  <a aria-label="Join the community on GitHub" href="https://link.codigoencasa.com/DISCORD">
    <img alt="" src="https://img.shields.io/discord/915193197645402142?logo=discord">
  </a>
</p>


## Getting Started

With this library, you can build automated conversation flows agnostic to the WhatsApp provider, set up automated responses for frequently asked questions, receive and respond to messages automatically, and track interactions with customers. Additionally, you can easily set up triggers to expand functionalities limitlessly.

```
npm create builderbot@latest
```


## Documentation

Visit [builderbot](https://builderbot.vercel.app/) to view the full documentation.


## Official Course

If you want to discover all the functions and features offered by the library you can take the course.
[View Course](https://app.codigoencasa.com/courses/builderbot?refCode=LEIFER)


## Contact Us
- [💻 Discord](https://link.codigoencasa.com/DISCORD)
- [👌 𝕏 (Twitter)](https://twitter.com/leifermendez)


## Variables de Entorno

El proyecto requiere las siguientes variables de entorno para funcionar correctamente:

| Variable | Descripción |
|----------|-------------|
| `N8N_WEBHOOK_PROD` | URL del webhook de N8N para producción |
| `N8N_WEBHOOK_TEST` | URL del webhook de N8N para pruebas |

### Configuración

1. Las variables se deben configurar en el panel de Railway:
   - Dashboard → Variables → New Variable
   - O usando el CLI: `railway variables set NOMBRE_VARIABLE=valor`

2. Para desarrollo local:
   - Copia `.env.example` a `.env`
   - Rellena los valores necesarios

El archivo `.env.example` se mantiene en el repositorio como referencia, pero los valores reales deben configurarse en el panel de Railway o en tu archivo `.env` local (que no debe subirse al repositorio).