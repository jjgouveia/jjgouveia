### Oi, eu sou o Jarbas 👋

CTO e sócio da [Ativos Precatórios](https://github.com/ativos-tecnologia), em Recife. Meu trabalho é achar o processo chato que alguém faz na mão todo dia e transformar em software. Processo chato vira dado, dado vira decisão.

O exemplo que eu mais gosto: recalcular um precatório levava uns 20 minutos. Fiz uma automação e passou a levar 2 segundos. É esse tipo de coisa que me faz levantar da cadeira.

[LinkedIn](https://www.linkedin.com/in/jarbasgouveia) · [Email](mailto:gouvik.dev@gmail.com)

## Como começou

Lá por 2011 eu tinha um LG P350. Tela de 2.8", 600 MHz, 140 MB de memória interna, e a LG largou ele no Android 2.2. Eu não aceitei.

Virei o "Jr Gouveia" nos fóruns de ROM e passei os anos seguintes mantendo CyanogenMod e a minha própria ROM, a Androm, até o aparelho rodar Android 4.4. No meio do caminho compilei o `tun.ko` na mão pra ele ter OpenVPN, e as builds foram parar na base de compatibilidade do TUN.ko Installer como referência pro P350.

Com 140 MB não sobra espaço pra desperdício. Levei isso pra tudo que fiz depois: software bom desperdiça menos.

## O que estou construindo agora

- **Celer**: a plataforma onde a Ativos opera precatório. Precificação, due diligence, CRM, KYC e pagamento num fluxo só. Django, DRF, Celery e Postgres com pgvector.
- **Ativos Intelligence**: agentes em LangGraph que leem documento jurídico e financeiro pro time. Nenhum agente vai pra produção sem passar no golden set.
- **[Portal OAB-PE × Ativos](https://portal-oab-ativos.vercel.app)**: onde advogado de Pernambuco consulta e acompanha precatório. Roda no mesmo motor de cálculo do Celer.
- **Nexo**: trocamos o Dropbox por um drive nosso, com permissão por hierarquia e trilha de auditoria.

## Pittaya

Fora da Ativos, toco a [Pittaya](https://github.com/pittaya-ui) com o Marcos Bueno e o Lucas Ribeiro. A [Pittaya UI](https://github.com/pittaya-ui/ui) é nossa biblioteca de componentes React, com uma CLI pra adicionar e remover componente no seu projeto.

## Coisas que fiz porque me incomodavam

- **[mandajobs](https://github.com/jjgouveia/mandajobs)**: achar vaga de tecnologia no LinkedIn com filtro decente dava trabalho. Ele monta a busca pra você, no LinkedIn e na web.
- **[maestro-express-async-errors](https://www.npmjs.com/package/maestro-express-async-errors)**: pra parar de escrever try/catch em todo middleware async do Express. Zero dependência.
- **[show-react](https://www.npmjs.com/package/show-react)**: pra parar de empilhar ternário dentro de ternário no JSX.
- **[Poetry Syntax Highlight](https://marketplace.visualstudio.com/items?itemName=jarbasgouveia.poetry-syntax-highlight)**: o `pyproject.toml` era um bloco sem cor no VS Code enquanto eu fazia o backend do Celer. Agora não é mais.

## No meio do caminho

Programador.TV, depois Skill Labs como CTO, depois bementor, onde a API ficou 43% mais rápida e as páginas críticas caíram de 11 s pra 3 s de carregamento. Aí veio a Ativos.

Se quiser trocar ideia sobre automação, IA aplicada ou ROM de aparelho velho, me chama no [LinkedIn](https://www.linkedin.com/in/jarbasgouveia).
