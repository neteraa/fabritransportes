# 🚌 Fabri Transportes — Sistema de Gestão de Frota

> **Demonstração de MVP** — Site institucional + Painel de gestão completo com GPS, câmeras ao vivo, IA no WhatsApp, agenda, manutenção e alertas de segurança.

---

## 🔗 Links

| | URL |
|---|---|
| 🌐 Site | `index.html` |
| ⚙️ Painel | `painel.html` |

---

## 📦 O que está incluído

### 🌐 Site Institucional (`index.html`)
- Landing page profissional com identidade visual da empresa
- Seções: Hero, Serviços, Diferenciais, CTA, Contato, Footer
- Formulário de orçamento integrado ao WhatsApp
- Botão WhatsApp flutuante animado
- 100% responsivo — funciona em mobile e desktop
- Sem backend — arquivo único, hospedagem gratuita

### ⚙️ Painel de Gestão (`painel.html`) — DEMONSTRAÇÃO
Sistema completo de gestão de frota com 9 módulos:

| Módulo | Funcionalidade |
|---|---|
| 📊 **Dashboard** | Visão geral em tempo real — GPS, câmeras, eventos, stats |
| 🗺️ **Rastreamento GPS** | Mapa ao vivo com veículos se movendo (Leaflet + OpenStreetMap) |
| 📷 **Câmeras ao Vivo** | 6 feeds animados — dashcam frontal, interior, traseira |
| 🤖 **IA WhatsApp** | Chat automático com clientes e funcionários — agenda, orçamento, agendamento |
| 👥 **Funcionários** | Gestão de motoristas, escala, notificações |
| 👤 **Clientes** | CRM com histórico de reservas e contatos |
| 📅 **Agenda** | Calendário de viagens, ocupação da frota, reservas |
| 🔧 **Manutenção** | Preventiva por veículo — óleo, pneus, revisão com progress bars |
| 🚨 **Alertas** | Score de segurança, excesso de velocidade, frenagem brusca |
| 📈 **Relatórios** | Analytics — Chart.js com viagens, receita, km, tipos de serviço |

---

## 🚀 Como Usar

```bash
# Servir localmente
python3 -m http.server 8080

# Abrir
# Site:   http://localhost:8080
# Painel: http://localhost:8080/painel.html
```

Ou abra os arquivos `.html` diretamente no browser — funciona offline.

---

## 🛠️ Stack — O que pode ser construído de verdade

| Componente | Tecnologia real | Custo estimado |
|---|---|---|
| GPS Tracker | Teltonika FMB920 / Suntech ST4315 | ~R$300/veículo + R$40/mês |
| Câmeras 4G | Milesight MS-C2986-X / Hikvision | ~R$800/câmera |
| WhatsApp IA | Evolution API (self-hosted) + GPT-4 | ~R$0 + R$50/mês uso |
| Backend | Node.js + PostgreSQL + WebSockets | ~R$80/mês (VPS) |
| Dashboard | Next.js + React + Recharts | incluso |
| Hospedagem site | Vercel / Netlify | **Grátis** |

---

## 📋 Roadmap (se o cliente fechar)

- [ ] **Fase 1** — Site no ar + domínio + Google Meu Negócio
- [ ] **Fase 2** — GPS real + câmeras + dashboard ao vivo
- [ ] **Fase 3** — Bot IA WhatsApp + agendamento automático
- [ ] **Fase 4** — App mobile motoristas + relatórios automáticos

---

## 📞 Fabri Transportes

- 📍 Itapeva — SP
- 📱 (15) 99740-7754 / (15) 99627-9346
- 📸 [@fabri_transportes](https://instagram.com/fabri_transportes)

---

*Desenvolvido como MVP de demonstração — 2025*
