# Briefing YouTube · CURSOR-LOOP
## Medo de tocar o código com Cursor: branch, revert, PR

Alvo: ~12–18 min (corta se a verdade for menor). PT na voz/tela. Legenda EN depois. Faceless (a demo é o rosto). Victor monta no Premiere/AE.
Fase 1: não publicar. Sem upload. Sem travessão no título.

Tese (dizer em voz alta antes dos 3 min):
eu dirijo, o agente executa, o trabalho termina em PR. Se estragar, eu reverte. O medo de tocar some quando o loop tem freio.

Origem:
comentário no X do Victor sobre não temer editar porque dá pra reverter e testar mais versões. Victor é o rosto do método. Não nomear handle de terceiro como protagonista. Creditar só se virar reply pública útil; senão, a origem fica como “comentário no feed” e segue o ofício.

Ângulo: medo → revert → loop Cursor (humano no volante, agente nas mãos, fim em PR). Fila v4 #3.
Lane: ofício · nível inter · frente agentes.
ZERO Remotion · zero remotion-agent-catalog · zero render preto · zero 3D.

Artefato (recibo sugerido · **precisa rodar** antes de gravar):
- 1 branch limpa a partir do main
- 1 edit ruim do agente (diff errado, arquivo errado, ou regressão óbvia na tela)
- 1 revert (git restore / git revert / reset seguro na branch; mostrar o comando e o estado depois)
- 1 PR aberto com o caminho bom (humano aprovou o fim)
- Sem inventar número de PR. Quando existir, cola o link/hash no card de Artefato. Até lá: rótulo **precisa rodar**.

Thumb (rascunho): tela com revert (ou git status limpo) | card de PR · texto 2–4 palavras: "REVERT + PR" ou "EU DIRIJO"
Victor aprova. Sem upload.

Persona / Faraday (obrigatório neste card):
- Mother line: "Método com recibo: IA do básico ao avançado, o que eu rodei e onde quebrou."
- Audiência: coder BR com medo de o agente bagunçar o repo.
- Vantagem única: ele já posta o loop Cursor→PR; aqui mostra falha + revert de verdade, não “Composer resolveu”.
- Formato: hábitos com freio, detalhado (mercado raso = milagre Composer).
- Promessa: thumb com revert/PR, não guru.

---

## Corte Librarian (10 linhas, voz montage)

1. Abre no diff ruim. Silêncio. Depois: isso veio do agente.
2. Medo do coder BR: tocar = estragar o repo. O freio é branch + revert.
3. Regra 1: eu dirijo. Agente executa. Trabalho termina em PR.
4. Abre branch. Pedido curto. Agente mexe. Diff na tela.
5. Edit ruim de propósito ou de verdade. Não esconde.
6. Revert. Comando. Estado limpo. Medo cai um degrau.
7. Segundo passe: pedido melhor, escopo menor, eu no volante.
8. PR aberto. Título do commit. Humano aprovou o fim.
9. Habits: branch sempre · pedido com borda · ler diff · revert sem drama · PR é o recibo.
10. Fecha sem triunfo. Onde quebrou fica no vídeo. Sem hype.

## Ordem dos capítulos

### 0. Abre no defeito (0:00–0:40)
Diff feio fullscreen. Um segundo de silêncio. Depois: isso saiu do agente. Não explica ainda. Só o fato estranho.

### 1. O medo e a aposta (0:40–2:30)
Coder BR: “se eu deixar o agente mexer, estraga o repo.”
Aposta do episódio: branch + revert tiram o medo; o loop (eu dirijo → agente executa → PR) é o método.
Comentário no X inspirador: creditar o *insight* (reverter / testar versões), sem protagonizar handle alheio. Victor conduz.

### 2. A regra em uma frase (2:30–4:00)
Eu dirijo. O agente executa. O trabalho termina em PR.
Não é “IA faz por mim”. É volante + freio.
MOSTRAR: card simples com as três partes (sem animação 3D, sem Remotion).

### 3. Branch antes do medo (4:00–6:00)
Repo real (ou pasta de trabalho honestamente rotulada). `git status` limpo. Nova branch.
Pedido curto ao agente: escopo, arquivo, o que NÃO tocar.
Habits aqui: borda no pedido > prompt longo.

### 4. O edit ruim (6:00–9:00)
Agente mexe. Diff na tela. Onde quebrou: arquivo errado, teste quebrado, ou mudança fora do pedido.
Não narrar como vitória. Mostrar o erro como ofício.
Se o erro for encenado pra aula: dizer. Se for de sessão real: melhor. Sem fake PR number.

### 5. Revert sem drama (9:00–11:30)
Comando de volta. Working tree limpa ou commit revertido.
Tese em voz: o medo de tocar some quando o custo de errar cai.
MOSTRAR: antes (diff ruim) | depois (limpo).

### 6. Segundo passe, eu no volante (11:30–14:30)
Mesmo objetivo. Pedido mais apertado. Eu leio o diff linha a linha.
Aceito o que presta. Recuso o resto. Agente não edita o meio sem eu ver.
Fecha o caminho bom. Commit com mensagem humana.

### 7. PR = recibo (14:30–16:30)
Abre PR. Título. Description curta: o que pedi, o que quebrou, o que ficou.
Sem número inventado. Se ainda **precisa rodar**, grava só até o `gh pr create` / tela do PR na sessão real e cola o link depois no Artefato.
Promessa da thumb: revert + PR, não cara de guru.

### 8. Habits / Rules (pode fundir com 7 se o tempo apertar)
1. Sempre branch.
2. Pedido com borda (arquivo / fora de escopo).
3. Ler o diff inteiro.
4. Revert é ferramenta, não fracasso.
5. Fim do loop é PR, não chat.
6. Se o agente falhou em silêncio, o pedido estava vago.

### 9. Fecha (16:30–18:00+)
Onde está: branch, revert, PR (links quando existirem).
Se a verdade for menor que 12–18 min: corta. Sem enchimento.
Cortar primeiro: alongar menos o §2; priorizar §4–§7 (falha + revert + PR).
Não fechar com “e a IA resolveu tudo”.

---

## Takes / B-roll (ordem sugerida)
1. Diff ruim fullscreen
2. `git status` / nova branch
3. Chat do Cursor com pedido bordado
4. Diff lado a lado (ruim | limpo pós-revert)
5. Segundo passe: aceitar/recusar hunks
6. Tela do PR (ou fluxo até abrir)
7. Card Habits 1–6 (texto seco, sem motion 3D)

## Recusar
- Remotion, catálogo, render preto, three.js, bloom, SHA de frame
- “Composer resolveu” como tese
- Talking-head guru / renda com IA
- Nomear handle de terceiro como herói do método
- Inventar número de PR / “7 PRs” na manchete sem tela
- Travessão (—) no título
- Narrar tweet linha a linha
- Fechar com “funcionou perfeito”

## Dual
X = PT text-only (THREAD.md neste pacote; Victor posta).
YT = PT + legenda EN na descrição (fase 1: não publicar).

## Checklist pré-gravação
- [ ] Sessão **precisa rodar**: branch + edit ruim + revert + PR
- [ ] Links/hashes reais colados no Artefato (sem inventar)
- [ ] Thumb rascunho aprovado por Victor
- [ ] Corte Librarian gravável em 10 takes
- [ ] Zero asset Remotion/3D no timeline

---

## Voice-cut (Librarian) · aplicado
Ângulo sem jargão Scout/Faraday na linha. Formato em PT. Corte montage 10 linhas já no card (§ acima) — mantém. Zero Remotion. Sem travessão no título. Sem publicar.
