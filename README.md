# Deno, NextJs And Deploying

Did not get this example to work (2024-11-01).
Deployed fine but get `Internal Server Error` when viewing the site.

## Creation History

The code in this repository is base on:

- https://youtu.be/puoorw7jUoc?si=woXFHuUUuZPywUQ0

## Code History

```bash
deno -A npm:create-next-app@latest
cd deno-next-ex1
deno task build
deno install -gArf jsr:@deno/deployctl
deplyctl deploy --include=.next --include=public jsr:@deno/nextjs-start
```
