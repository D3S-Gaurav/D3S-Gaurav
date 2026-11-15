[![Linkedin Badge](https://img.shields.io/badge/-kumar--gaurav--cs-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://linkedin.com/in/kumar-gaurav-cs)](https://linkedin.com/in/kumar-gaurav-cs) [![Codeforces Badge](https://img.shields.io/badge/-Specialist%20(1440)-03A89E?style=flat-square&logo=codeforces&logoColor=white&link=https://codeforces.com/profile/ATHEUS)](https://codeforces.com/profile/ATHEUS) [![LeetCode Badge](https://img.shields.io/badge/-ATHEUS__007-FFA116?style=flat-square&logo=leetcode&logoColor=white&link=https://leetcode.com/u/ATHEUS_007/)](https://leetcode.com/u/ATHEUS_007/)

### Works

**Open Source**

1. **[Oppia](https://github.com/oppia/oppia)**:
   * **Key Contributions:**
     * Shipped a custom **ESLint rule** that fails CI when `ViewEncapsulation.None` is used without a justification comment — with a 10-test RuleTester suite and a legacy allowlist so CI stayed green.
     * Fixed the **Install Chrome** CI step crashing with `kill EPERM` on hung commands, by giving each command its own time limit so retries run cleanly.

2. **[FOSSology](https://github.com/fossology/fossology)**
   * **Key Contributions:**
     * Migrated the Vagrant dev box off end-of-life Ubuntu 20.04 to 22.04 to match CI.


**Internships**

1. **AgriPulse** — Software Development Engineer: Made the all-crops soil scan **2.3× faster** with one endpoint scoring all 22 crops per request. Blocked prompt injection on the Gemini route, split the FastAPI backend into routers/services/workers, and migrated the front end to Next.js.
2. **BIT Mesra** — Research Intern (ML): Built a toxic comment classifier on 198K comments reaching **0.836 macro-F1** (vs 0.544 baseline) with a LightGBM + Logistic Regression blend.

**Personal**

1. **[HiveGraph](https://github.com/D3S-Gaurav/HiveGraph)** ([Live ↗](https://hivegraph.vercel.app)): Multi-agent LLM orchestrator that turns one goal into a validated task graph run in parallel. Replay-safe events via Redis Lua, a Go fan-out service over **Kafka → gRPC/WebSockets**, SSRF protection, and 100+ tests plus Go race tests in CI.
2. **[ChatFlow](https://github.com/D3S-Gaurav/chat-fullstack)**: Real-time group chat holding **5,000 concurrent sockets** and ~97K deliveries/sec with zero loss in k6 load tests. Zod-typed API, JWT auth on REST and sockets, rate limits, RBAC and 32 integration tests.
