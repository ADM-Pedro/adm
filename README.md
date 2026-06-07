# Simulador de Ganhos — DK Diário Brawl (ADMs)

Ferramenta **interna dos ADMs**. Calcula o prêmio certo de cada jogador, o lucro de
uma sala e projeta sua renda (dia/semana/mês). Separado do site público — você manda
o link só pros seus ADMs.

## Como publicar (repositório SEPARADO)
1. Crie **outro** repositório no GitHub (ex: `dk-simulador-adms`).
2. **Add file → Upload files** e arraste os 2 arquivos desta pasta (`index.html` e `logo.png`).
3. **Commit changes**.
4. **Settings → Pages** → Branch `main` / `/ (root)` → **Save**.
5. Em ~1 min fica no ar: `https://SEU-USUARIO.github.io/dk-simulador-adms/`
6. Manda esse link só pros 4 ADMs.

## O que ele faz
- **Projeção de renda:** você diz quantas partidas roda por dia e por semana, se é Dono
  (100%) ou ADM (50%), e ele mostra quanto você fatura por dia, semana e mês — já
  descontando o gasto semanal de R$10 (no caso dos ADMs).
- **Quanto pagar a um jogador:** kills + se venceu = quanto ele recebe (sem erro).
- **Lucro de uma sala:** o que sobra pra casa em uma partida e a sua parte.
- **Valores:** dá pra ajustar inscrição, kill, vitória e gasto semanal se as regras mudarem.

> Os números digitados ficam salvos só no aparelho de quem usa. Nada vai pra internet.
> A `logo.png` precisa ficar na mesma pasta do `index.html`.
