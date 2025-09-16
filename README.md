# Projeto — Rede Mais Social
*Isadora Luisa Candini Marques*  
RA: **10730955**

Este repositório concentra a implementação e a documentação dos dois cenários definidos na Especificação da disciplina:
- UC002 — Solicita Afiliação (Visão Voluntário)
- UC003 — Aprova Afiliação (Visão Rede Mais Social/Admin)

Toda a documentação detalhada está na Wiki do projeto:
- [Home](https://github.com/euisalu/Projeto_Software_Mackenzie2025.2_Isalu/wiki/Home)
- [Cenário 1 – Solicita Afiliação](https://github.com/euisalu/Projeto_Software_Mackenzie2025.2_Isalu/wiki/Cen%C3%A1rio-1-–-Solicita-Afilia%C3%A7%C3%A3o)
- [Cenário 2 – Aprova Afiliação](https://github.com/euisalu/Projeto_Software_Mackenzie2025.2_Isalu/wiki/Cen%C3%A1rio-2-–-Aprova-Afilia%C3%A7%C3%A3o)


##  Como navegar

### Cenário 1 — Voluntário 
1. papel = **Voluntário**  
2. **Criar conta** → preenche o perfil e salva.  
3. **Buscar organizações** → escolhe uma → **Ver detalhes**.  
4. seleciona unidade / área / disponibilidade → **Solicitar afiliação**.  
5. escreve a carta de motivação → **Upload docs** → **Revisão**.  
6. **Confirmar envio** → status muda pra **EM_ANALISE**.  
7. olha as **Notificações**, tem a mensagem do envio.  

### Cenário 2 — Admin 
1. papel = **Admin** → faz login.  
2. entra em **Pendentes** → clica em **Analisar**.  
3. (pode abrir **Verificar docs** se quiser).  
4. decide: **Aprovar** ou **Rejeitar** → confirma.  
5. voluntário recebe notificação.  
6. em **Auditoria** dá pra ver todo histórico de ações.  

Fluxo de Telas

Voluntário: Home → Auth → Perfil → Dashboard → Lista Org → Detalhe Org → Form Solicitação → Upload Docs → Revisão → Confirmação → Status/Notificações

Admin: Login → Pendentes → Detalhe → Verificação Docs → Decisão → Confirmação → Auditoria




