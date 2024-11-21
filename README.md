# ts-score-bot

### installation

Install [deno](https://deno.com/)

`deno install` to install everything in `deno.lock`

[./openapi.yaml](./openapi.yaml) is sourced from [dword4](https://gitlab.com/dword4/nhlapi/-/blob/master/swagger/openapi.yaml)

`deno run npm:openapi-typescript ./openapi.yaml -o ./schema.d.ts` will generate new client types from the openapi.yaml file
