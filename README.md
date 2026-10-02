# edicao

Projetos de vídeo com [HyperFrames](https://github.com/heygen-com/hyperframes) (HTML → MP4).

## Requisitos
- Node.js 22+
- FFmpeg

## Estrutura
- `.claude/skills/` — skills oficiais do HyperFrames para o Claude Code (use `/hyperframes`)
- `meu-video/` — projeto inicial criado com `npx hyperframes init`

## Comandos
```bash
cd meu-video
npx hyperframes browser ensure   # baixa o Chrome headless (1ª vez)
npm run dev                      # preview no navegador
npm run check                    # valida a composição
npm run render                   # renderiza para MP4
```

Novo projeto: `npx hyperframes init nome-do-video`
Atualizar skills: `npx hyperframes skills update`
