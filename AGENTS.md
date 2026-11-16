# 🤖 AGENTS — Regras de operação (organização)

> Regras para agentes (IA) operando nos repositórios da org **FBSO Technology Solutions**
> (`github.com/fbso-techsolutions`). Leia o [INTENT.md](INTENT.md) antes de qualquer coisa.

## 1. Convenções da org (obrigatórias)

- **"Promover o genérico, manter o específico."** O que é transversal a mais de um repo sobe para
  [`platform-standards`](https://github.com/fbso-techsolutions/platform-standards); cada repo guarda
  o delta e **linka** (nunca copia).
- **"Aponta, não copia."** Um documento vive em um só lugar; referências são links.
- **IDs de entidades** seguem `{ENTIDADE}-{NNNN}`: [padrão](https://github.com/fbso-techsolutions/platform-standards/blob/main/standards/agile/padrao-identificacao-entidades.md).

## 2. Estrutura da org

Taxonomia, regras e donos: [GOVERNANCE.md](GOVERNANCE.md).

## 3. Como cada repo instrui agentes

Todo repo tem duas portas de entrada:

- **`AGENTS.md`** — regras de operação **enxutas** (sempre carregado).
- **`INTENT.md`** — o **porquê/o quê/pra onde** do repo (lido 1× no início).

Convenção e template: [platform-standards/standards/engineering/agentes-ia.md](https://github.com/fbso-techsolutions/platform-standards/blob/main/standards/engineering/agentes-ia.md).

## 4. Regras deste repo (`.github`)

- Templates de issue/PR e starter workflows são **copiados** no bootstrap de um repo; não são código.
- Reusable workflows vivem em `platform-standards/.github/workflows/` (chamados via `uses:`).
- Segurança: [SECURITY.md](SECURITY.md) · Contribuição: [CONTRIBUTING.md](CONTRIBUTING.md).
