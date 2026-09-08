# Identidade Visual — Itaú

Guia de estilo (design system) com as cores, tipografia e escala de fontes utilizadas na identidade visual do Itaú.

## Logo

Logo em fundo laranja (`#FF6200`), com o texto "itaú" em branco, em formato de ícone arredondado.

## Cores

### Primário
| Cor | Hex | Preview |
|---|---|---|
| Primário +1 | `#FF8133` | 🟧 |
| Primário | `#FF6200` | 🟧 |
| Primário -1 | `#CC4E00` | 🟧 |

### Secundário
| Cor | Hex | Preview |
|---|---|---|
| Secundário +1 | `#539AE9` | 🟦 |
| Secundário | `#267FE3` | 🟦 |
| Secundário -1 | `#1866BE` | 🟦 |

### Dark
| Cor | Hex | Preview |
|---|---|---|
| Dark -1 | `#0B0A0A` | ⬛ |
| Dark | `#262323` | ⬛ |
| Dark +1 | `#403B3B` | ⬛ |

### Light
| Cor | Hex | Preview |
|---|---|---|
| Light +1 | `#FFFFFF` | ⬜ |
| Light | `#F2F5F7` | ⬜ |
| Light -1 | `#D3DDE4` | ⬜ |

### Sucesso
| Cor | Hex | Preview |
|---|---|---|
| Sucesso +1 | `#7BE085` | 🟩 |
| Sucesso | `#52D65F` | 🟩 |
| Sucesso -1 | `#2FC63E` | 🟩 |

### Perigo (Danger)
| Cor | Hex | Preview |
|---|---|---|
| Danger +1 | `#FF2705` | 🟥 |
| Danger | `#D11C00` | 🟥 |
| Danger -1 | `#9E1500` | 🟥 |

## Tipografia

**Fonte:** Poppins

### Font Scale

| Estilo | Tamanho |
|---|---|
| Small | 14px |
| Parágrafo | 16px |
| H5 | 18px |
| H4 | 24px |
| H3 | 28px |
| H2 | 34px |
| H1 | 40px |

> A escala é aplicada em duas variações de peso: regular e bold (negrito).

## Contraste

A tipografia foi testada sobre três fundos diferentes para garantir legibilidade:

1. **Fundo claro** (`#D3DDE4` — light -1) — texto em laranja (`#FF6200`)
2. **Fundo laranja primário** (`#FF6200`) — texto em branco (`#FFFFFF`)
3. **Fundo escuro** (`#262323` — dark) — texto em laranja (`#FF6200`)

## Estrutura de tokens sugerida

\`\`\`json
{
  "cores": {
    "primario": { "+1": "#FF8133", "base": "#FF6200", "-1": "#CC4E00" },
    "secundario": { "+1": "#539AE9", "base": "#267FE3", "-1": "#1866BE" },
    "dark": { "-1": "#0B0A0A", "base": "#262323", "+1": "#403B3B" },
    "light": { "+1": "#FFFFFF", "base": "#F2F5F7", "-1": "#D3DDE4" },
    "sucesso": { "+1": "#7BE085", "base": "#52D65F", "-1": "#2FC63E" },
    "danger": { "+1": "#FF2705", "base": "#D11C00", "-1": "#9E1500" }
  },
  "tipografia": {
    "fontFamily": "Poppins",
    "fontScale": {
      "small": "14px",
      "paragrafo": "16px",
      "h5": "18px",
      "h4": "24px",
      "h3": "28px",
      "h2": "34px",
      "h1": "40px"
    }
  }
}
\`\`\`
