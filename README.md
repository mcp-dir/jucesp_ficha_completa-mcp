# JUCESP: Ficha Cadastral Completa

### JUCESP: Ficha Cadastral Completa para Claude, ChatGPT e agentes de IA

Ficha cadastral completa de uma empresa na JUCESP (registro, situação e histórico por CNPJ, NIRE ou nome). Hospedado pela plataforma, sem credenciais, pague por consulta com crédito pré-pago.

- 📊 **1 ferramenta**
- 🔒 **Somente leitura**
- 💬 **Funciona com qualquer cliente MCP**: Claude Desktop, Cursor, VS Code, Cline, Continue
- 🔑 **Login via magic-link (sem senha)**

[English version](README.en.md) · [Documentação completa](docs/) · [Skill pra agentes](skills/)

---

## Instalar em 1 clique

### Claude (Web e Desktop)

A Anthropic unificou a instalação de MCPs em `claude.ai/customize/connectors`. **O mesmo link serve pra Claude Web e Claude Desktop** (basta estar logado):

[➕ Abrir no Claude e conectar](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

**Manual** (se o deeplink não abrir): [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Adicionar conector personalizado** → cole **Nome** `JUCESP: Ficha Cadastral Completa` e **URL** `https://api.mcp.ai/p_jucesp_ficha_completa`.

### Cursor

[➕ Instalar JUCESP: Ficha Cadastral Completa no Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=jucesp_ficha_completa&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF9qdWNlc3BfZmljaGFfY29tcGxldGEifQ==)

### VS Code (Copilot Chat)

[➕ Instalar JUCESP: Ficha Cadastral Completa no VS Code](vscode:mcp/install?name=jucesp_ficha_completa&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_jucesp_ficha_completa%22%7D)

### ChatGPT, Manus, OpenClaw e mais 40+ clientes

Funciona em qualquer cliente MCP que suporte **MCP over HTTP**. A URL do servidor é sempre:

```
https://api.mcp.ai/p_jucesp_ficha_completa
```

Detalhes por cliente: [INSTALL.md](INSTALL.md).

---

## Exemplos de uso

```
Ficha cadastral completa do CNPJ na JUCESP
```

---

## 1 ferramenta disponível

| Tool | Descrição |
|---|---|
| `jucesp_ficha_completa_consultar` | Ficha cadastral completa de uma empresa na JUCESP (registro, situação e histórico por CNPJ, NIRE ou nome). |

Detalhe de cada tool: [docs/ferramentas.md](docs/ferramentas.md)

---

## Preços

Pré-pago (carteira de créditos), paga por uso. Veja [docs/precos.md](docs/precos.md).

---

## Privacidade & LGPD

- **Somente leitura**, nenhuma ferramenta altera dados na origem.
- **Sub-processadores**: o LLM host que você escolher (Claude, ChatGPT, Cursor, agente próprio). Lista completa em [docs/privacidade-lgpd.md](docs/privacidade-lgpd.md).
- Os dados retornados pelas tools são enviados ao **LLM host que você escolher**, sub-processador fora do nosso controle. Recomendamos planos com opt-out de treinamento.

---

## Perguntas frequentes

**O servidor é open source?**
O servidor é proprietário (hosted). Este repositório é o wrapper público com manifestos, docs e skills — tudo MIT.

**Posso usar com agente próprio (não Claude/Cursor)?**
Sim — qualquer cliente que suporte MCP over HTTP. URL: `https://api.mcp.ai/p_jucesp_ficha_completa`.


---

## Suporte

- 📧 [jucesp_ficha_completa@mcp.ai](mailto:jucesp_ficha_completa@mcp.ai)
- 🐛 [GitHub Issues](https://github.com/mcp-dir/jucesp_ficha_completa-mcp/issues)
- 📄 [docs/](docs/)

---

## Licença

MIT — veja [LICENSE](LICENSE). O servidor MCP em `api.mcp.ai/p_jucesp_ficha_completa` é proprietário (hosted); este repositório (manifestos, docs, skills) é MIT.
