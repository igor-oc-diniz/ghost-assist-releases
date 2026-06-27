# GhostAssist — Releases

Canal oficial de distribuição do GhostAssist para macOS.

---

## Download

Acesse a [última release](https://github.com/igor-oc-diniz/ghost-assist-releases/releases/latest) e baixe o arquivo correto para o seu Mac:

| Arquivo | Para quem? |
|---|---|
| `GhostAssist-x.x.x-mac-arm64.dmg` | Mac com Apple Silicon (M1, M2, M3, M4...) |
| `GhostAssist-x.x.x-mac-x64.dmg` | Mac com Intel |

Não sabe qual é o seu? Clique na maçã () → **Sobre este Mac** → veja o chip.

---

## Instalação

1. Abra o `.dmg` baixado
2. Arraste o **GhostAssist** para a pasta **Applications**
3. **Passo obrigatório** — no Terminal, rode:
   ```bash
   xattr -cr /Applications/GhostAssist.app
   ```
4. Abra o GhostAssist normalmente

> **Por que o passo 3?** O macOS marca apps baixados da internet como "em quarentena". Como o GhostAssist ainda não tem assinatura Apple, esse comando remove o bloqueio. É seguro.

---

## Atualização

O app avisa automaticamente quando há uma nova versão disponível. Clique em **Baixar** no banner e repita os passos de instalação acima.
