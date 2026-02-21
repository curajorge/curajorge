
# < JorgeCura />

```csharp
public class Engineer : IPolyglot, IArchitect
{
    public string Name => "Jorge Cura";
    public string Philosophy => "Language Agnostic (The right tool for the job)";
    public string Obsession => "Deterministic Systems & Context Engineering";
    public bool IsCoffeeDependent => true;
}
```

### `> whoami`

I am a Senior Backend & Distributed Systems Engineer with 7+ years of experience building high-availability payment processors and developer tooling. 

I am **language agnostic** by design. While I have deep roots in the .NET ecosystem, I believe syntax is secondary to architecture. Whether it's **Rust** for local-first performance, **Python** for data pipelines, or **C#** for enterprise stability, I focus on building **idempotent, fault-tolerant systems** regardless of the stack.

When I'm not managing memory safety or optimizing SQL queries, I am obsessing over the physics of extraction—applying engineering rigor to **AI Agents** and **Specialty Coffee**.

---

## `0x01` // The Current Toolbelt

| Context | Technology |
| :--- | :--- |
| **Core Backend** | C# (.NET), Python |
| **Systems** | Rust (Tauri v2), Distributed Locking (RedLock), Event Sourcing |
| **Frontend** | Vue.js 3 (Composition API), TypeScript, Pinia, Tailwind |
| **Data** | SQL Server, PostgreSQL, Redis, MongoDB |
| **Infra** | Azure, AWS (ECS), Docker, GitHub Actions |

---

## `0x02` // Build Artifacts

### ⚡ **[Project Desk App]** (Local-First Tooling)
*Bridging the gap between local filesystems and LLM reasoning.*
*   **The Tech:** Rust (Backend), Tauri, Vue 3, Tiktoken-rs.
*   **The Engineering:** Implemented a recursive filesystem traversal in Rust (10x faster than Node) and a deterministic JSON-to-File patcher to allow LLMs to safely refactor code with human-in-the-loop gates.

### 💳 **Enterprise Payment Orchestration**
*Building rails for millions in transactions at RT² & InComm.*
*   **Resilience:** Designed custom idempotency layers to ensure network retries never result in double-charges.
*   **Migration:** Led zero-downtime migrations from legacy monoliths to modular Vue 3 micro-frontends.

---

## `0x03` // System.Runtime.Caffeine ☕

I treat coffee brewing like a deployment pipeline: it requires precise variables, consistent execution, and constant debugging. I follow the **James Hoffmann** school of thought—maximizing extraction without hitting astringency.

Here are my current production configurations:

### 🚀 The "Daily Driver" (Aeropress)
*Source: James Hoffmann's Ultimate Aeropress Technique*

```yaml
config:
  method: Inverted? No. Standard.
  ratio: 11g : 200g (Light Roast)
  grind_size: Medium-Fine (Salt)
  temp: 100°C (Boiling)

execution:
  - step: "0:00"
    action: "Pour 200g water"
    notes: "Ensure all grounds are wet."
  - step: "0:00 - 2:00"
    action: "Wait"
    notes: "Let thermal energy do the work."
  - step: "2:00"
    action: "Swirl"
    notes: "Gently breaking the crust. Do not plunge yet."
  - step: "2:30"
    action: "Press"
    notes: "Press gently. Stop at the hiss."
```

### 🧪 The "Weekend Release" (V60)
*Source: James Hoffmann's "Better 1 Cup V60"*

```json
{
  "profile": "V60_02",
  "dose": "15g",
  "water_total": "250g",
  "temp": "100°C",
  "phases": [
    { "time": "0:00", "action": "Bloom", "mass": "50g", "desc": "Swirl to wet all grounds" },
    { "time": "0:45", "action": "Pour",  "mass": "to 250g", "desc": "Pour center, slow circles. Aim for 60% of total." },
    { "time": "1:15", "action": "Swirl", "mass": "N/A", "desc": "Gently swirl brewer to flatten bed." },
    { "time": "2:30", "action": "Drawdown", "status": "Complete" }
  ]
}
```

---

## `0x04` // Telemetry

<p align="center">
  <img src="assets/github-stats.png" alt="GitHub Stats" width="495" />
  <br />
  <img src="assets/languages.png" alt="Top Languages" width="495" />
</p>

---

## `0x05` // Connect

If you want to talk about distributed systems, why Rust is the future of desktop apps, or why your espresso tastes sour, hit me up.

*   [LinkedIn](https://linkedin.com/in/jorgecura)
*   [Email](mailto:curajorge21@gmail.com)
