FROM denoland/deno:1.41.3

WORKDIR /app

COPY . .

RUN deno task build

ENV PORT=8000

EXPOSE 8000

CMD ["deno", "task", "preview"]
