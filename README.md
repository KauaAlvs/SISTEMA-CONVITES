<div align="center">
  <div align="center" style="display: flex; justify-content: center; align-items: center; gap: 30px;">
  <img src="https://ik.imagekit.io/38cojzdyt/LOGO%20PNG.png?updatedAt=1779186643051" alt="Logo Festa das Nações" height="150"/>
</div>

# 🌍 Papa Mike | Gestão de Passaportes & Festa das Nações 2026
  
  **Experiência digital premium na palma da mão.** <br>
  Plataforma completa para emissão, gestão de passaportes e controle de acesso, com automação inteligente de convites via WhatsApp.

  ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
  ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
  ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
  ![Supabase](https://img.shields.io/badge/Supabase-181818?style=for-the-badge&logo=supabase&logoColor=3ECF8E)
  ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

</div>

---

## 📖 Visão Geral

O sistema **Papa Mike | Festa das Nações** foi desenhado para eliminar a burocracia na organização de eventos escolares de grande porte. Unificamos a gestão de reservas com uma experiência de usuário (UX) de alto nível, permitindo que cada família receba seus "Passaportes Oficiais" de forma automatizada, profissional e moderna.

Com foco na agilidade, o sistema centraliza desde o cadastro dos convidados até a validação na portaria, proporcionando um fluxo de acesso fluido e seguro.

---

## ✨ Funcionalidades Principais

### 🎫 Gestão & Emissão de Passaportes
- **Design Premium:** Passaportes com QR Codes de alta performance, estética unificada (Normal e VIP) e efeito de picote digital.
- **Visualização Pública:** Landing page exclusiva por reserva (`convite.papamike.com.br/t/[ID]`), onde os pais acessam, selecionam e baixam seus convites (PNG ou PDF unificado).
- **Emissão em Massa:** Impressão otimizada via portal direto, eliminando a paginação indesejada do navegador.

### 📱 Automação Inteligente (WhatsApp)
- **Envio Direto:** Integração nativa com a API do WhatsApp para envio imediato de convites.
- **Link Único:** Mensagem personalizada que direciona a família para a sua página de convites, sem necessidade de login ou senhas complexas.

### 🛡️ Controle de Acesso e Auditoria
- **Validação Ágil:** Interface de portaria pensada para tablets, com feedback visual imediato para acesso autorizado.
- **Auditoria Completa:** Registro transparente de todas as entradas, evitando fraudes por duplicidade de QR Codes.

---

## 🛠️ Arquitetura Técnica

Utilizamos uma stack robusta para garantir estabilidade e alta performance durante os dias do evento:

* **Framework:** [Next.js (App Router)](https://nextjs.org/)
* **Backend / Database:** [Supabase](https://supabase.com/) (PostgreSQL + RLS)
* **Performance:** [Vercel Edge Network](https://vercel.com/)
* **Geração de Assets:** [html-to-image](https://github.com/bubkoo/html-to-image) & [jsPDF](https://github.com/parallax/js-jspdf)
* **Estilização:** [Tailwind CSS](https://tailwindcss.com/) + [Lucide Icons](https://lucide.dev/)

---

## 🔐 Segurança & Performance
- **Segurança Pública:** Rotas de convites protegidas por IDs/Tokens, garantindo que o acesso público seja apenas para os donos da reserva.
- **UX Adaptativa:** Interface 100% responsiva, garantindo que a equipe de operação no tablet tenha a mesma experiência que o gestor no desktop.
- **Sincronização:** Infraestrutura pensada para lidar com picos de acesso no momento de abertura dos portões.

---

## 🚀 Roadmap
- [ ] Implementação de leitura via câmera integrada (Webcam/Tablet).
- [ ] Relatórios de métricas de ocupação em tempo real por categoria (VIP/Geral).
- [ ] Exportação de relatórios de auditoria em CSV para a direção escolar.

---
*Desenvolvido com excelência por **HEIKA SOLUCTIONS LTDA**.*
