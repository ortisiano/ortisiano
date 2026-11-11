<div align="center">

# 🤖 Carlos (`@ortisiano`) · Agentic AI & Local-First Apps

**Diseñando agentes de IA útiles, herramientas *Local-First* y aplicaciones abiertas con privacidad desde el diseño.**

![Status](https://img.shields.io/badge/Agent_Orchestrator-Online-8B5CF6?style=for-the-badge)
![Privacy](https://img.shields.io/badge/Guardrails-Zero_PII_Retention-06B6D4?style=for-the-badge)
![Edge](https://img.shields.io/badge/Runtime-Cloudflare_Edge-10B981?style=for-the-badge)

</div>

---

### ⚡ Pipeline de Agentes & Privacidad en el Edge

```text
[ Dispositivo del Usuario ] ──► [ Guardrail RGPD + Anti-Prompt-Injection ] ──► [ Agente IA en Cloudflare Edge ]
             ▲                                                                                │
             └──────────────◄── [ Respuesta Estructurada · 0 Datos en Servidor ] ◄────────────┘
```

---

### 🧠 Agentes y Aplicaciones en Producción

<table>
  <tr>
    <td width="68%">
      <h4>🌙 <a href="https://dinnerkids.es">DinnerKids</a> · <code>Agent-01 (Nutrition & Vision)</code></h4>
      <p>
        Planificador y agente inteligente de cenas infantiles que interpreta el menú del comedor escolar (mediante visión artificial OCR y motor local determinista), evita repetir grupos nutricionales, filtra alérgenos e intolerancias y genera la lista de la compra semanal.
      </p>
      <p>
        <a href="https://dinnerkids.es">🌐 <b>dinnerkids.es</b></a> &nbsp;·&nbsp;
        <a href="https://github.com/ortisiano/dinnerkids">💻 <b>Código Abierto en GitHub</b></a>
      </p>
    </td>
    <td width="32%">
      <kbd>Claude Haiku Vision</kbd><br>
      <kbd>Cloudflare Workers</kbd><br>
      <kbd>Zero-PII Sanitizer</kbd><br>
      <kbd>PWA 100% Local</kbd>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <i>🤖 <code>Agent-02</code> · Nuevo agente autónomo y herramienta abierta en entrenamiento...</i>
    </td>
  </tr>
</table>

---

### 🛡️ Principios de Ingeniería (Guardrails)

| Pilar | Implementación |
|---|---|
| **Zero-Data Guardrails** | Anonimización automática en el propio dispositivo (`anonymizePII` + `B-02`) antes de consultar cualquier modelo de IA. |
| **Arquitectura Híbrida** | Motores instantáneos en el navegador (0 ms, 0 coste, offline) combinados bajo demanda con agentes ligeros en el Edge. |
| **Privacidad por Diseño** | Sin cuentas de usuario, sin cookies de rastreo y sin bases de datos con información sensible. |

---

### ☕ Recarga de Tokens & Soporte Independiente

Si mis agentes y aplicaciones te ahorran tiempo cada semana, puedes apoyar el desarrollo para cubrir costes de inferencia de IA y servidores:

<p>
  <a href="https://ko-fi.com/ortisiano">
    <img src="https://img.shields.io/badge/Ko--fi-Invitar_a_un_Café-8B5CF6?style=for-the-badge&logo=ko-fi&logoColor=white" alt="Ko-fi" />
  </a>
  &nbsp;
  <a href="https://github.com/sponsors/ortisiano">
    <img src="https://img.shields.io/badge/Sponsor-GitHub_Sponsors-06B6D4?style=for-the-badge&logo=github-sponsors&logoColor=white" alt="GitHub Sponsors" />
  </a>
</p>

