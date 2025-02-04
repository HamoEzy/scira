# Scira

![Scira](/app/opengraph-image.png)

A minimalistic AI-powered search engine that helps you find information on the internet.

## Special Thanks

<div align="center" markdown="1">

  [![Warp](https://github.com/user-attachments/assets/2bda420d-4211-4900-a37e-e3c7056d799c)](https://www.warp.dev/?utm_source=github&utm_medium=referral&utm_campaign=scira)<br>
  ### **[Warp, the intelligent terminal](https://www.warp.dev/?utm_source=github&utm_medium=referral&utm_campaign=scira)**<br>
  [Available for MacOS and Linux](https://www.warp.dev/?utm_source=github&utm_medium=referral&utm_campaign=scira)<br>
  [Visit warp.dev to learn more](https://www.warp.dev/?utm_source=github&utm_medium=referral&utm_campaign=scira)

</div>

## Features

- **AI-powered search**: Get answers to your questions using Anthropic's Models.
- **Web search**: Search the web using Tavily's API.
- **URL Specific search**: Get information from a specific URL.

## LLM used
- [xAI's Grok](https://x.ai/grok)

## Built with
- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vercel AI SDK](https://sdk.vercel.ai/docs)
- [Shadcn/UI](https://ui.shadcn.com/)
- [Exa.AI](https://exa.ai/)
- [Tavily](https://tavily.com/)
- [OpenWeather](https://openweathermap.org/)
- [E2B](https://e2b.dev/)
- [Google Maps](https://developers.google.com/maps)
- [Mapbox](https://www.mapbox.com/)
- [TripAdvisor](https://www.tripadvisor.com/)
- [AviationStack](https://aviationstack.com/)

### Deploy your own

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fzaidmukaddam%2Fscira&env=XAI_API_KEY,UPSTASH_REDIS_REST_URL,UPSTASH_REDIS_REST_TOKEN,AVIATION_STACK_API_KEY,SANDBOX_TEMPLATE_ID,TMDB_API_KEY,NEXT_PUBLIC_POSTHOG_KEY,NEXT_PUBLIC_POSTHOG_HOST,YT_ENDPOINT,EXA_API_KEY,TRIPADVISOR_API_KEY,BLOB_READ_WRITE_TOKEN,MAPBOX_ACCESS_TOKEN,NEXT_PUBLIC_MAPBOX_TOKEN,FIRECRAWL_API_KEY,TAVILY_API_KEY,OPENWEATHER_API_KEY,E2B_API_KEY,GOOGLE_MAPS_API_KEY,NEXT_PUBLIC_GOOGLE_MAPS_API_KEY&envDescription=All%20environment%20variables%20needed%20for%20application)

### Local development

To run the example locally you need to:

1. Sign up for accounts with the AI providers you want to use. OpenAI and Anthropic are required, Tavily is required for the web search feature.
2. Obtain API keys for each provider.
3. Set the required environment variables as shown in the `.env.example` file, but in a new file called `.env.local`.
4. `pnpm install` to install the required dependencies.
5. `pnpm dev` to launch the development server.

# License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
