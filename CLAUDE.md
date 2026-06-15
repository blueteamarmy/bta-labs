# BTA Labs — Contexto para Claude Code

## Projeto
Labs estáticos para os cursos Blue Team Army hospedados no GitHub Pages.
Repositório: bta-labs (monorepo)
URL base: https://blueteamarmy.github.io/bta-labs/

## Design System BTA
- Cores: --bg #060a12, --blue #1e90ff, --cyan #00e5ff, --green #00e676
- Fontes: Rajdhani (headings), Exo 2 (body), Share Tech Mono (terminal/mono)
- Referência visual: https://blueteamarmy.github.io/bta-lab-linux/

## Estrutura de Pastas
/bto/         → curso Blue Team Operations (BTO)
/bto/engines/ → motores reutilizáveis por módulo
/bto/mod1-lab/ até /bto/mod9-lab/ → labs dos módulos 1–9
/csf/         → curso Cybersecurity Fundamentals (CSF)
/csf/csf-lab/ → lab do curso CSF (a desenvolver)

## Regras
- Tudo HTML/CSS/JS estático — sem dependências de servidor
- Dados dos labs em JSON local
- Cada motor em /bto/engines/ deve ser reutilizável via parâmetros
