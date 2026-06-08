# Como Contribuir com o CarbonLedger

Obrigado por contribuir.
Este guia foi feito para deixar o processo simples, claro e seguro.

## 1. Antes de começar

1. Faça um fork do projeto (se estiver contribuindo via PR).
2. Crie uma branch para sua mudança.
3. Garanta que o ambiente local está funcionando.

## 2. Padrão de branch e commit

Use nomes de branch descritivos, por exemplo:

- `docs/melhora-readme`
- `feat/novo-fluxo-validacao`
- `fix/correcao-marketplace`

Mensagens de commit recomendadas:

- `docs: atualiza seção de trabalhos futuros`
- `feat: adiciona validação de entrada no contrato`
- `fix: corrige cálculo de taxa no marketplace`

## 3. O que revisar antes do commit

1. Código formatado e legível.
2. Nenhuma chave privada ou segredo no commit.
3. Testes relevantes executados com sucesso.
4. Documentação atualizada quando houver mudança de comportamento.

## 4. Testes (backend/contratos)

Comandos úteis na raiz do projeto:

```bash
npm install
npx hardhat compile
npx hardhat test
```

## 5. Frontend

Comandos úteis em `frontend/`:

```bash
npm install
npm run dev
npm run build
```

## 6. Pull Request

Ao abrir PR, inclua:

1. Contexto do problema.
2. O que foi alterado.
3. Como validar.
4. Prints ou evidências (quando aplicável).

## 7. Segurança

Nunca publique:

- private keys;
- `.env` real;
- arquivos com dados sensíveis.

Use sempre o arquivo [.env.example](.env.example) como referência para configuração.

## 8. Código de conduta

Respeito, colaboração e clareza na comunicação são essenciais.
Contribuições construtivas são sempre bem-vindas.
