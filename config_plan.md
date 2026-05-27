# Plano de Configuração do Portfolio

Com base no `README.md` e no estado atual do repositório, aqui estão os passos necessários para configurar o seu portfolio.

## 📋 Passos Necessários

### 1. Configuração de Variáveis de Ambiente (.env)
Você já possui o arquivo `.env`, mas ele contém placeholders.
- [ ] **GitHub Token**: Gere um "Classic Personal Access Token" no GitHub (sem scopes necessários) e cole no campo `REACT_APP_GITHUB_TOKEN`.
- [ ] **GitHub Username**: Confirme se `keldenmourato` é o seu usuário correto.
- [ ] **Medium Username**: (Opcional) Adicione seu usuário do Medium se desejar exibir blogs.

### 2. Personalização do Conteúdo (`src/portfolio.js`)
Este é o arquivo principal onde você define suas informações, links sociais, experiências e habilidades.
- [ ] Editar `greeting` (Saudação).
- [ ] Editar `socialMediaLinks`.
- [ ] Editar `skillsSection`, `workExperience`, etc.

### 3. Personalização Visual (`src/_globalColor.scss`)
- [ ] Alterar o esquema de cores global para combinar com sua marca pessoal.

### 4. Upload do Currículo
- [ ] Salvar seu currículo em PDF no diretório `src/containers/greeting/resume` com o nome `resume.pdf`.

### 5. Iniciar o Servidor de Desenvolvimento
- [ ] Executar `npm start` para visualizar as alterações em tempo real.

---

## 🚀 Próximas Ações Sugeridas
1. **Gere o Token do GitHub**: Posso te ajudar a configurar o `.env` assim que você tiver o token.
2. **Edição do `portfolio.js`**: Podemos começar a editar suas informações básicas. Que tal começarmos pela saudação e links sociais?
