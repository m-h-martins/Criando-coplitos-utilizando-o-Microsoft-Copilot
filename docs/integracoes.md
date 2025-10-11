# 🔗 Integrações do Copiloto com Microsoft 365

Após configurar seu copiloto, é possível integrá-lo a diferentes ferramentas do ecossistema Microsoft.

---

## 💬 1. Microsoft Teams

1. No Copilot Studio, acesse **Publicar → Canais**.  
2. Selecione **Microsoft Teams**.  
3. Clique em **Conectar** e autorize o acesso.  
4. Escolha se o copiloto será visível para:
   - Toda a organização  
   - Grupos específicos  
   - Usuários selecionados

> 💡 Use o Teams para testes rápidos com a equipe.

---

## 🗂️ 2. SharePoint

1. Gere um link público de incorporação via **“Configurações → Canal Web”**.  
2. No SharePoint, adicione um **Web Part → Inserir → HTML personalizado**.  
3. Cole o código de incorporação do copiloto.  
4. Publique a página.

---

## 🌐 3. Canal Web ou Site Externo

1. Ative o **Canal Web** no Copilot Studio.  
2. Copie o **iframe** gerado.  
3. Cole o trecho no HTML do seu site.

Exemplo:
```html
<iframe src="https://copilotstudio.microsoft.com/embed/SeuCopilotoID" width="400" height="600"></iframe>
