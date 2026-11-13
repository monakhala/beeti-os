# Beeti (بيتي) — Egyptian Household AI Operations Platform

> **"Your home, in good hands."**  
> An autonomous life administration and household operations system engineered for families in Egypt and the MENA region.

---

## 1. Product Thesis
The administrative burden of modern life is scattered across disjointed services:
- Fragmented telecom and internet contracts (WE Egypt, Vodafone, Orange, e&)
- Prepaid utility meters and fluctuating electricity tariffs (North/South Cairo Distribution)
- Compound and property maintenance schedules (New Administrative Capital, New Cairo, Sheikh Zayed)
- Scattered physical and PDF documents (leases, warranties, medical records)

Today, the household administrator is the manual integration layer. **Beeti** replaces that manual overhead with a calm, permission-gated operations agent that moves tasks from awareness to resolution.

---

## 2. Design System & Anti-AI-Slop Manifesto
Designed with extreme restraint and editorial craft:
- **Zero AI Clichés**: No neon-purple gradient blobs, no floating spark emojis, no over-stylized "eyebrow" badges over headers.
- **Fluid Timeline River**: Obligations and upcoming deadlines flow chronologically without boxy, nested card-in-card grids.
- **Contextual Inspection Drawers**: High signal-to-noise ratio where secondary details, raw contracts, and audit trails slide over quietly on demand.
- **Bilingual Typographic Nuance**: Clean English typography paired with authentic Arabic brand identity (*بيتي*).

---

## 3. Token Optimization Architecture
85%+ of household management is deterministic logic. Beeti implements a strict 3-tier token budget protocol:

| Tier | Component | Token Cost | Implementation |
|---|---|---|---|
| **Tier 1: Deterministic Engine** | Countdown timers, deadline alerts, status machines, role permissions | **0 tokens** | Client/PostgreSQL business logic |
| **Tier 2: Structured Document Parsing** | OCR extraction of Egyptian bills and tenancy contracts | **< 250 tokens** | Pydantic / Zod schema extraction with prompt caching |
| **Tier 3: Negotiation & Communication** | Provider comparison diffs and bilingual outbound inquiries | **< 350 tokens** | Scoped agent prompts with strict action diffs |

---

## 4. Flagship Interactive Workflows
1. **Contract Expiry & Renewal Negotiation**:
   - Monitors active contracts (e.g. WE Home Fiber Mega 200 Mbps expiring in 12 days).
   - Identifies alternatives (Vodafone VDSL Super with promotional loyalty discount).
   - Computes net savings (EGP 350/month = EGP 4,200/year).
   - Human-in-the-loop Trust Center approval with outbound notice draft.
2. **Personal Vault**:
   - Searchable household document index (contracts, maintenance invoices, electricity statements, leases).
   - Structured JSON metadata extraction with source verification.
3. **Trust Center & Audit Trail**:
   - Every agent action requires explicit user authorization before execution.
   - Comprehensive immutable audit log with timestamps, risk ratings, and reversible states.

---

## 5. Development & Sync
- **Lovable App**: Built with TanStack Start, React 19, TypeScript, and Tailwind CSS.
- **Live Lovable Project**: [Beeti Home Command](https://lovable.dev/projects/267b8a9c-bcda-4534-ad66-5d8ad2638425)
