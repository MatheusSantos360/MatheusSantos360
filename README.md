<a href="https://github.com/MatheusSantos360">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=200&color=gradient&customColorList=6,11,20&text=Matheus%20dos%20Santos&fontColor=fff&fontSize=50&animation=fadeIn&fontAlignY=38&desc=Full-stack%20dev%20que%20reescreve%20o%20backend%20do%20zero%20por%20esporte&descAlignY=58&descSize=18"/>
</a>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&pause=1200&color=A78BFA&center=true&vCenter=true&width=650&lines=Backend+em+SparkZen+%2B+Fastify+%2B+Mongoose;Autor+do+framework+SparkZen+(sim%2C+eu+mesmo+fiz);Programando+desde+os+14+(sim,+sobrevivi)" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=MatheusSantos360&label=Deu%20ruim%20quantas%20vezes%20visitaram%20aqui&color=6a0dad&style=for-the-badge" alt="Profile views" />
</p>

---

### 🧃 Sobre mim (a versão sem enrolação)

17 anos, comecei a programar aos 14 sozinho, sem curso, sem mentor, só eu e o Stack Overflow numa relação tóxica (Ah, quanta index não fechada eu já dei drop sem entender direito — e olha que deu certo, sorte de principiante).

Hoje sou dev full-stack de verdade — não "full-stack de bootcamp de 3 semanas" — e passei por bastante chão de fábrica antes disso: hamburgueria, mercado, clínica, freela de site de prefeitura (é, governo confiou em mim, imagina). Cada um desses lugares me ensinou mais sobre entregar coisa que funciona do que qualquer curso online (nenhum curso te ensina a lidar com cliente que muda o requisito 4x na mesma call).

Bruh, e sim, eu escrevo certo até quando tô de zoeira. É proposital (eu acho).

---

### 🛠️ O que eu tô aprontando agora

Refazendo o backend inteiro do zero de um WMS (sistema de gestão de almoxarifado) pra uma empresa de construção/elevadores. Descartei a arquitetura antiga inteira e reconstruí em cima do meu próprio framework (SparkZen + Fastify + Mongoose), porque aparentemente eu curto sofrimento recreativo.

- 🔥 [**SparkZen**](https://github.com/MatheusSantos360/SparkZen) — framework de API TypeScript-first, zero-config, roteamento por pasta. Cansei de escrever Express na mão em 2026 feito refém do passado, então fiz o meu (Nah, não tava difícil o suficiente sem isso).
- 📦 [**Logfy-X**](https://github.com/MatheusSantos360/logfy-x) — lib de logging pra Node focada em simplicidade e performance.

---

### ⚙️ Stack Principal — Engenharia de Software

> **Filosofia:** simplicidade primeiro. Cada tecnologia resolve um problema específico, complexidade só entra quando é necessária de verdade (eu falando isso enquanto reescrevo o mesmo backend pela terceira vez, eu sei, eu sei — mas dessa vez é diferente, juro).

<details open>
<summary><b>🎨 Frontend</b> — interface, SSR/SSG/CSR, forms, auth de sessão</summary>
<br>

<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind&theme=dark" /><br />
  <img src="https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white" />
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" />
  <img src="https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white" />
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white" />
  <img src="https://img.shields.io/badge/Auth.js-000000?style=for-the-badge&logo=auth0&logoColor=white" />
</p>

Renderização híbrida, estado de servidor gerenciado direito, formulário validado com Zod (porque `any` é sinônimo de "vou debugar isso às 2h da manhã").

</details>

<details open>
<summary><b>⚙️ Backend</b> — API REST, arquitetura modular, regra de negócio</summary>
<br>

<p align="center">
  <img src="https://skillicons.dev/icons?i=nestjs,ts&theme=dark" /><br />
  <img src="https://img.shields.io/badge/Swagger%2FOpenAPI-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" />
</p>

Doc de API sempre atualizada automaticamente. Se a doc tá desatualizada, o problema não é a ferramenta, sou eu sendo preguiçoso (raro, mas acontece).

</details>

<details open>
<summary><b>🗄️ Persistência</b> — o banco certo pro problema certo, não pro meu ego</summary>
<br>

<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mongodb&theme=dark" /><br />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white" />
</p>

**PostgreSQL + Prisma** pra dado transacional sério (usuário, empresa, permissão, financeiro — coisa que não pode dar zebra).
**MongoDB + Mongoose** quando o problema pede flexibilidade (log, evento, histórico, conteúdo dinâmico).

Princípio: escolho o banco pelo problema, não por preferência pessoal (sim, isso é uma indireta pra mim mesmo de anos atrás usando Mongo pra tudo).

</details>

<details>
<summary><b>🔐 Autenticação</b></summary>
<br>

<p align="center">
  <img src="https://img.shields.io/badge/Auth.js-000000?style=for-the-badge&logo=auth0&logoColor=white" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_OAuth-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/RBAC-6a0dad?style=for-the-badge" />
</p>

Evolução quando o projeto pede: Refresh Tokens, permissões granulares, MFA. Sem over-engineering no dia 1 (isso eu já aprendi na marra).

</details>

<details>
<summary><b>📦 Organização, 🐳 Infra e 🧪 Qualidade</b></summary>
<br>

<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,vercel,githubactions&theme=dark" /><br />
  <img src="https://img.shields.io/badge/pnpm_Workspaces-F69220?style=for-the-badge&logo=pnpm&logoColor=white" />
  <img src="https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white" />
  <img src="https://img.shields.io/badge/Fly.io-8B5CF6?style=for-the-badge&logo=flydotio&logoColor=white" />
</p>
<br />
<p align="center">
  <img src="https://skillicons.dev/icons?i=vitest&theme=dark" /><br />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" />
  <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" />
  <img src="https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=black" />
  <img src="https://img.shields.io/badge/Husky-000000?style=for-the-badge" />
</p>

Monorepo com pnpm Workspaces pra compartilhar código entre front, back e lib interna. Docker no dev, Vercel no front, Railway/Fly.io/VPS no back a depender da fome de recurso do projeto. Teste unitário, integração e E2E — porque "funcionou na minha máquina" não é uma estratégia de deploy.

</details>

---

### 🏗️ Arquitetura de referência (a que eu sigo quando ninguém tá me apressando)

```
                    Usuário
                        │
                        ▼
             Next.js + Auth.js
                        │
                        ▼
                   NestJS API
                        │
              ┌─────────┴─────────┐
              ▼                   ▼
       PostgreSQL             MongoDB
      (transacional)      (flexível/log)
              │                   │
        Prisma ORM           Mongoose
```

SOLID, Clean Code, DRY, KISS, Separation of Concerns — os cinco mandamentos que eu sigo até quando tô com preguiça (principalmente quando tô com preguiça, na real, porque código bagunçado dá mais trabalho depois).

---

### 📊 Números (pra quem gosta de gráfico)

<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=MatheusSantos360&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165em" src="https://github-readme-streak-stats.herokuapp.com/?user=MatheusSantos360&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MatheusSantos360&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</p>

---

### 🐛 Fatos aleatórios (que ninguém pediu, mas toma)

- Já rodei `dropIndex()` no MongoDB de produção com uma confiança que eu não deveria ter (deu certo, mas foi no talento, não no preparo)
- Uso `.filter(Boolean)` depois de `populate()` como quem reza terço — não é fé, é experiência de dor
- Já debugei 4 horas um erro que era um `useEffect` chamando `setState` dentro dele mesmo (a cascata de re-render mais bonita e mais dolorosa que eu já vi)
- Leio a doc oficial antes de perguntar pro ChatGPT (mentira, é o contrário, mas fica bonito escrito)
- Eu juraria fidelidade eterna a um `returnDocument: "after"` funcionando de primeira — é tão raro quanto parece

---

### 📬 Bora trocar ideia

<p align="center">
  <a href="mailto:matheusworkcontact@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/MatheusSantos360">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Discord-%40cody__tryhard-5865F2?style=for-the-badge&logo=discord&logoColor=white" />
</p>

<p align="center"><i>Se você chegou até aqui lendo tudo isso, ou você tá me stalkeando pra contratar ou tá procrastinando igual eu faço quando devia tá codando. De boa, eu também faria isso.</i></p>

<a href="https://github.com/MatheusSantos360">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&color=gradient&customColorList=6,11,20&section=footer"/>
</a>
