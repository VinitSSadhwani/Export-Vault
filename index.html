import { useState } from "react";
import {
  Package, Globe, FileText, Users, BookOpen,
  ChevronDown, ChevronUp, Download, ShieldCheck,
  Zap, AlertTriangle, Lock, Star, ArrowRight, Menu, X
} from "lucide-react";

// ─── CONFIG — edit all content here ───────────────────────────────────────────
const CONFIG = {
  brand: {
    name: "ExportVault",
    tld: ".in",
    tagline: "India's #1 Export Intelligence Kit",
    contact: "support@exportvault.in",
    gst: "GST No: 27XXXXX0000X1ZX",
  },
  hero: {
    badge: "🇮🇳 Trusted by 2,000+ Indian Exporters",
    headline: "Stop Searching. Start Exporting.",
    subheadline:
      "Get verified importer lists, HSN guides, CHA contacts & more — everything an Indian exporter needs, in one instant-download toolkit.",
    price: "₹499",
    originalPrice: "₹2,999",
    cta: "Get Instant Access →",
    subCta: "Instant Download · GST Invoice Included",
  },
  problem: {
    title: "Sound familiar?",
    subtitle: "Finding reliable export data shouldn't cost you lakhs or weeks of research.",
    points: [
      { icon: AlertTriangle, text: "Paid ₹5,000+ for outdated importer lists that went nowhere" },
      { icon: AlertTriangle, text: "Spent weeks Googling HSN codes and got conflicting answers" },
      { icon: AlertTriangle, text: "Lost deals because you couldn't find a trusted CHA on time" },
      { icon: AlertTriangle, text: "Export documentation errors caused costly shipment delays" },
    ],
  },
  features: [
    {
      icon: Globe,
      title: "Importer Lists",
      subtitle: "40+ Countries",
      desc: "Verified buyer databases across USA, UAE, UK, Germany, Australia & 35+ more markets. Name, email, product category included.",
    },
    {
      icon: Users,
      title: "CHA Directory",
      subtitle: "Nationwide Coverage",
      desc: "Custom House Agents listed by port — JNPT, Mundra, Chennai, Delhi ICD. Save days finding a trusted CHA.",
    },
    {
      icon: BookOpen,
      title: "HSN Code Guide",
      subtitle: "Comprehensive & Updated",
      desc: "Searchable HSN master for 500+ product categories with applicable duty rates. No more guesswork on customs.",
    },
    {
      icon: Package,
      title: "MSME Directory",
      subtitle: "Verified Suppliers",
      desc: "Curated list of MSME-registered manufacturers by sector. Perfect for sourcing or partnership outreach.",
    },
    {
      icon: FileText,
      title: "Documentation Guide",
      subtitle: "Step-by-Step",
      desc: "From Shipping Bill to Bill of Lading — every export document explained with templates you can use today.",
    },
  ],
  trust: [
    { icon: Download, label: "Instant Download", sub: "Access in under 60 seconds" },
    { icon: ShieldCheck, label: "GST Compliant", sub: "Tax invoice provided" },
    { icon: Zap, label: "Always Updated", sub: "Refreshed every quarter" },
    { icon: Lock, label: "Secure Payment", sub: "Razorpay encrypted checkout" },
  ],
  faqs: [
    {
      q: "What format are the files in?",
      a: "You get Excel (.xlsx) files for all lists and a PDF guide for the documentation walkthrough. Works on Windows, Mac, and mobile.",
    },
    {
      q: "Is this a subscription or one-time payment?",
      a: "Completely one-time. Pay ₹499 once and the files are yours forever. No recurring charges, ever.",
    },
    {
      q: "How current is the importer data?",
      a: "We refresh all lists every quarter. Your download always reflects the latest version available at time of purchase.",
    },
    {
      q: "Will I get a GST invoice?",
      a: "Yes. A proper GST-compliant invoice is automatically emailed to you right after purchase.",
    },
    {
      q: "Can I use this for my business or agency?",
      a: "The ₹499 license covers a single business entity. For agencies serving multiple clients, contact us for a team license.",
    },
  ],
  buyUrl: "#buy",
};
// ──────────────────────────────────────────────────────────────────────────────

const gold = "#F0B429";
const goldLight = "#FFD96A";
const navy = "#0B1120";
const navyMid = "#131E35";
const navyCard = "#192340";
const navyBorder = "#243058";

const styles = `
  @import url('https://fonts.googleapis.com/css2?family=Syne:wght@700;800&family=DM+Sans:wght@400;500;600&display=swap');
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { background: ${navy}; color: #E8EDF5; font-family: 'DM Sans', sans-serif; }
  ::selection { background: ${gold}33; }
  ::-webkit-scrollbar { width: 6px; } ::-webkit-scrollbar-track { background: ${navy}; } ::-webkit-scrollbar-thumb { background: ${navyBorder}; border-radius: 3px; }

  .syne { font-family: 'Syne', sans-serif; }

  .gold { color: ${gold}; }
  .gold-grad { background: linear-gradient(135deg, ${goldLight}, ${gold}); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; }

  .btn-primary {
    display: inline-flex; align-items: center; gap: 8px;
    background: linear-gradient(135deg, ${goldLight}, #D4920A);
    color: #0B1120; font-weight: 700; font-family: 'Syne', sans-serif;
    padding: 14px 28px; border-radius: 8px; border: none; cursor: pointer;
    font-size: 1rem; letter-spacing: 0.01em;
    box-shadow: 0 0 32px #F0B42940, 0 4px 16px #00000060;
    transition: transform 0.15s, box-shadow 0.15s;
  }
  .btn-primary:hover { transform: translateY(-2px); box-shadow: 0 0 48px #F0B42955, 0 8px 24px #00000070; }
  .btn-primary:active { transform: translateY(0); }

  .card {
    background: ${navyCard};
    border: 1px solid ${navyBorder};
    border-radius: 16px;
    transition: border-color 0.2s, transform 0.2s, box-shadow 0.2s;
  }
  .card:hover {
    border-color: ${gold}88;
    transform: translateY(-4px);
    box-shadow: 0 8px 32px #F0B42918;
  }

  .badge {
    display: inline-flex; align-items: center; gap: 6px;
    background: ${gold}18; border: 1px solid ${gold}44;
    color: ${gold}; border-radius: 999px;
    padding: 6px 16px; font-size: 0.82rem; font-weight: 600;
  }

  .section-label {
    font-size: 0.75rem; font-weight: 700; letter-spacing: 0.15em;
    text-transform: uppercase; color: ${gold};
  }

  .noise-bg {
    position: relative;
    background: radial-gradient(ellipse 80% 60% at 50% -10%, #1E3A6A55, transparent),
                radial-gradient(ellipse 50% 40% at 80% 80%, #0F2A5022, transparent),
                ${navy};
  }
  .noise-bg::before {
    content: ''; position: absolute; inset: 0; opacity: 0.03;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
    pointer-events: none;
  }

  .divider { border: none; border-top: 1px solid ${navyBorder}; margin: 0; }

  .sticky-bar {
    position: fixed; bottom: 0; left: 0; right: 0; z-index: 50;
    background: ${navyMid}EE; backdrop-filter: blur(12px);
    border-top: 1px solid ${navyBorder};
    padding: 12px 20px;
    display: flex; align-items: center; justify-content: space-between; gap: 12px;
  }

  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(24px); }
    to   { opacity: 1; transform: translateY(0); }
  }
  .fade-up { animation: fadeUp 0.6s ease both; }
  .delay-1 { animation-delay: 0.1s; } .delay-2 { animation-delay: 0.2s; }
  .delay-3 { animation-delay: 0.3s; } .delay-4 { animation-delay: 0.4s; }

  @media (min-width: 768px) { .sticky-bar { display: none; } }
`;

function Nav() {
  const [open, setOpen] = useState(false);
  return (
    <nav style={{
      position: "sticky", top: 0, zIndex: 40,
      background: `${navy}EE`, backdropFilter: "blur(14px)",
      borderBottom: `1px solid ${navyBorder}`,
    }}>
      <div style={{ maxWidth: 1100, margin: "0 auto", padding: "0 24px", display: "flex", alignItems: "center", justifyContent: "space-between", height: 64 }}>
        <span className="syne" style={{ fontSize: "1.3rem", fontWeight: 800, color: "#fff" }}>
          Export<span style={{ color: gold }}>Vault</span>
          <span style={{ color: "#6B7E9E", fontSize: "0.9rem" }}>.in</span>
        </span>
        <div style={{ display: "flex", gap: 24, alignItems: "center" }}>
          <a href="#features" style={{ color: "#A0AEC0", fontSize: "0.9rem", textDecoration: "none", display: open ? "block" : undefined }} className="nav-link">What's Inside</a>
          <a href="#faq" style={{ color: "#A0AEC0", fontSize: "0.9rem", textDecoration: "none" }}>FAQ</a>
          <a href={CONFIG.buyUrl} className="btn-primary" style={{ padding: "8px 18px", fontSize: "0.85rem" }}>Buy ₹499</a>
        </div>
      </div>
    </nav>
  );
}

function Hero() {
  return (
    <section className="noise-bg" style={{ padding: "96px 24px 80px", textAlign: "center", position: "relative", overflow: "hidden" }}>
      <div style={{
        position: "absolute", top: "20%", left: "50%", transform: "translate(-50%,-50%)",
        width: 600, height: 300,
        background: `radial-gradient(ellipse, ${gold}18 0%, transparent 70%)`,
        pointerEvents: "none",
      }} />
      <div style={{ maxWidth: 760, margin: "0 auto", position: "relative" }}>
        <div className="badge fade-up">{CONFIG.hero.badge}</div>
        <h1 className="syne gold-grad fade-up delay-1" style={{ fontSize: "clamp(2.4rem, 6vw, 4rem)", fontWeight: 800, lineHeight: 1.1, margin: "24px 0 20px" }}>
          {CONFIG.hero.headline}
        </h1>
        <p className="fade-up delay-2" style={{ fontSize: "clamp(1rem, 2.5vw, 1.2rem)", color: "#94A3B8", lineHeight: 1.7, maxWidth: 580, margin: "0 auto 36px" }}>
          {CONFIG.hero.subheadline}
        </p>
        <div className="fade-up delay-3" style={{ display: "flex", flexDirection: "column", alignItems: "center", gap: 14 }}>
          <div style={{ display: "flex", alignItems: "baseline", gap: 12 }}>
            <span className="syne" style={{ fontSize: "clamp(2rem, 5vw, 3rem)", fontWeight: 800, color: gold }}>{CONFIG.hero.price}</span>
            <span style={{ fontSize: "1.1rem", color: "#4A5568", textDecoration: "line-through" }}>{CONFIG.hero.originalPrice}</span>
            <span style={{ background: "#16A34A22", color: "#4ADE80", border: "1px solid #4ADE8033", borderRadius: 6, padding: "2px 8px", fontSize: "0.78rem", fontWeight: 700 }}>83% OFF</span>
          </div>
          <a href={CONFIG.buyUrl} className="btn-primary" style={{ fontSize: "1.05rem", padding: "16px 36px" }}>{CONFIG.hero.cta}</a>
          <p style={{ fontSize: "0.82rem", color: "#4A5568" }}>{CONFIG.hero.subCta}</p>
        </div>
        <div className="fade-up delay-4" style={{ display: "flex", justifyContent: "center", gap: 8, marginTop: 32 }}>
          {[...Array(5)].map((_, i) => <Star key={i} size={16} fill={gold} color={gold} />)}
          <span style={{ color: "#64748B", fontSize: "0.85rem", marginLeft: 6 }}>Rated 4.9/5 by 2,000+ exporters</span>
        </div>
      </div>
    </section>
  );
}

function Problem() {
  return (
    <section style={{ padding: "80px 24px", background: navyMid }}>
      <div style={{ maxWidth: 860, margin: "0 auto" }}>
        <p className="section-label" style={{ textAlign: "center" }}>The Problem</p>
        <h2 className="syne" style={{ fontSize: "clamp(1.6rem, 4vw, 2.4rem)", fontWeight: 800, textAlign: "center", marginTop: 12, marginBottom: 48, color: "#E2E8F0" }}>
          {CONFIG.problem.title}
        </h2>
        <div style={{ display: "grid", gridTemplateColumns: "repeat(auto-fit, minmax(280px, 1fr))", gap: 16 }}>
          {CONFIG.problem.points.map((p, i) => (
            <div key={i} style={{ display: "flex", gap: 14, alignItems: "flex-start", background: "#0F1826", border: `1px solid #E5454522`, borderRadius: 12, padding: "18px 20px" }}>
              <p.icon size={20} color="#F87171" style={{ flexShrink: 0, marginTop: 2 }} />
              <p style={{ color: "#94A3B8", fontSize: "0.95rem", lineHeight: 1.6 }}>{p.text}</p>
            </div>
          ))}
        </div>
        <p style={{ textAlign: "center", marginTop: 36, color: "#4ADE80", fontWeight: 600, fontSize: "1.05rem" }}>
          ExportVault fixes all of this — for just ₹499. ✓
        </p>
      </div>
    </section>
  );
}

function Features() {
  const [hovered, setHovered] = useState(null);
  return (
    <section id="features" style={{ padding: "80px 24px", background: navy }}>
      <div style={{ maxWidth: 1060, margin: "0 auto" }}>
        <p className="section-label" style={{ textAlign: "center" }}>What's Inside the Vault</p>
        <h2 className="syne" style={{ fontSize: "clamp(1.6rem, 4vw, 2.4rem)", fontWeight: 800, textAlign: "center", margin: "12px 0 12px", color: "#E2E8F0" }}>
          5 Weapons for Your Export Business
        </h2>
        <p style={{ textAlign: "center", color: "#64748B", marginBottom: 48, fontSize: "0.95rem" }}>Hover each card to explore what you get.</p>
        <div style={{ display: "grid", gridTemplateColumns: "repeat(auto-fit, minmax(280px, 1fr))", gap: 20 }}>
          {CONFIG.features.map((f, i) => (
            <div
              key={i}
              className="card"
              onMouseEnter={() => setHovered(i)}
              onMouseLeave={() => setHovered(null)}
              style={{ padding: "28px 24px", cursor: "default", position: "relative", overflow: "hidden" }}
            >
              {hovered === i && (
                <div style={{ position: "absolute", inset: 0, background: `radial-gradient(ellipse at top left, ${gold}10, transparent 70%)`, pointerEvents: "none" }} />
              )}
              <div style={{ width: 44, height: 44, borderRadius: 10, background: hovered === i ? `${gold}22` : `${navyBorder}`, display: "flex", alignItems: "center", justifyContent: "center", marginBottom: 16, transition: "background 0.2s" }}>
                <f.icon size={22} color={hovered === i ? gold : "#6B7E9E"} style={{ transition: "color 0.2s" }} />
              </div>
              <div className="syne" style={{ fontSize: "1.05rem", fontWeight: 700, color: "#E2E8F0", marginBottom: 4 }}>{f.title}</div>
              <div style={{ fontSize: "0.78rem", color: gold, fontWeight: 600, marginBottom: 10, textTransform: "uppercase", letterSpacing: "0.08em" }}>{f.subtitle}</div>
              <p style={{ color: "#64748B", fontSize: "0.88rem", lineHeight: 1.65, transition: "color 0.2s", ...(hovered === i ? { color: "#94A3B8" } : {}) }}>{f.desc}</p>
            </div>
          ))}
        </div>
      </div>
    </section>
  );
}

function Pricing() {
  return (
    <section style={{ padding: "80px 24px", background: navyMid }}>
      <div style={{ maxWidth: 520, margin: "0 auto", textAlign: "center" }}>
        <p className="section-label">Pricing</p>
        <h2 className="syne" style={{ fontSize: "clamp(1.6rem, 4vw, 2.2rem)", fontWeight: 800, margin: "12px 0 32px", color: "#E2E8F0" }}>
          Everything for One Honest Price
        </h2>
        <div style={{ background: navyCard, border: `1px solid ${gold}55`, borderRadius: 20, padding: "36px 32px", boxShadow: `0 0 60px ${gold}15` }}>
          <div style={{ display: "flex", justifyContent: "center", alignItems: "baseline", gap: 12, marginBottom: 8 }}>
            <span className="syne gold-grad" style={{ fontSize: "3.5rem", fontWeight: 800 }}>{CONFIG.hero.price}</span>
            <span style={{ color: "#4A5568", textDecoration: "line-through", fontSize: "1.2rem" }}>{CONFIG.hero.originalPrice}</span>
          </div>
          <p style={{ color: "#4ADE80", fontWeight: 600, marginBottom: 28, fontSize: "0.9rem" }}>One-time payment · No subscription</p>
          <div style={{ textAlign: "left", marginBottom: 28, display: "flex", flexDirection: "column", gap: 12 }}>
            {CONFIG.features.map((f, i) => (
              <div key={i} style={{ display: "flex", alignItems: "center", gap: 10 }}>
                <span style={{ color: gold, fontSize: "1rem" }}>✓</span>
                <span style={{ color: "#CBD5E1", fontSize: "0.92rem" }}>{f.title} <span style={{ color: "#475569", fontSize: "0.82rem" }}>({f.subtitle})</span></span>
              </div>
            ))}
          </div>
          <a href={CONFIG.buyUrl} className="btn-primary" style={{ width: "100%", justifyContent: "center", fontSize: "1.05rem" }}>
            Get Instant Access <ArrowRight size={18} />
          </a>
          <p style={{ marginTop: 14, color: "#475569", fontSize: "0.8rem" }}>GST Invoice · Instant Download · Razorpay Secure</p>
        </div>
      </div>
    </section>
  );
}

function Trust() {
  return (
    <section style={{ padding: "60px 24px", background: navy }}>
      <div style={{ maxWidth: 900, margin: "0 auto" }}>
        <div style={{ display: "grid", gridTemplateColumns: "repeat(auto-fit, minmax(180px, 1fr))", gap: 20 }}>
          {CONFIG.trust.map((t, i) => (
            <div key={i} style={{ textAlign: "center", padding: "24px 16px" }}>
              <div style={{ width: 48, height: 48, borderRadius: 12, background: `${gold}15`, border: `1px solid ${gold}33`, display: "flex", alignItems: "center", justifyContent: "center", margin: "0 auto 14px" }}>
                <t.icon size={22} color={gold} />
              </div>
              <div className="syne" style={{ fontWeight: 700, color: "#E2E8F0", marginBottom: 4 }}>{t.label}</div>
              <div style={{ color: "#64748B", fontSize: "0.85rem" }}>{t.sub}</div>
            </div>
          ))}
        </div>
      </div>
    </section>
  );
}

function FAQ() {
  const [open, setOpen] = useState(null);
  return (
    <section id="faq" style={{ padding: "80px 24px", background: navyMid }}>
      <div style={{ maxWidth: 700, margin: "0 auto" }}>
        <p className="section-label" style={{ textAlign: "center" }}>FAQ</p>
        <h2 className="syne" style={{ fontSize: "clamp(1.5rem, 3.5vw, 2rem)", fontWeight: 800, textAlign: "center", margin: "12px 0 40px", color: "#E2E8F0" }}>
          Common Questions
        </h2>
        <div style={{ display: "flex", flexDirection: "column", gap: 12 }}>
          {CONFIG.faqs.map((faq, i) => (
            <div key={i} style={{ background: navyCard, border: `1px solid ${open === i ? gold + "44" : navyBorder}`, borderRadius: 12, overflow: "hidden", transition: "border-color 0.2s" }}>
              <button
                onClick={() => setOpen(open === i ? null : i)}
                style={{ width: "100%", display: "flex", justifyContent: "space-between", alignItems: "center", padding: "18px 22px", background: "none", border: "none", cursor: "pointer", color: "#CBD5E1", fontFamily: "'DM Sans', sans-serif", fontSize: "0.95rem", fontWeight: 600, textAlign: "left", gap: 12 }}
              >
                <span>{faq.q}</span>
                {open === i ? <ChevronUp size={18} color={gold} /> : <ChevronDown size={18} color="#4A5568" />}
              </button>
              {open === i && (
                <div style={{ padding: "0 22px 18px", color: "#64748B", fontSize: "0.9rem", lineHeight: 1.7 }}>{faq.a}</div>
              )}
            </div>
          ))}
        </div>
      </div>
    </section>
  );
}

function Footer() {
  return (
    <footer style={{ background: "#070D18", borderTop: `1px solid ${navyBorder}`, padding: "40px 24px" }}>
      <div style={{ maxWidth: 1060, margin: "0 auto", display: "flex", flexWrap: "wrap", justifyContent: "space-between", alignItems: "center", gap: 16 }}>
        <div>
          <div className="syne" style={{ fontSize: "1.1rem", fontWeight: 800, color: "#fff", marginBottom: 4 }}>
            Export<span style={{ color: gold }}>Vault</span><span style={{ color: "#4A5568" }}>.in</span>
          </div>
          <p style={{ color: "#475569", fontSize: "0.8rem" }}>{CONFIG.brand.gst}</p>
        </div>
        <div style={{ display: "flex", gap: 24, flexWrap: "wrap" }}>
          <a href="#features" style={{ color: "#475569", fontSize: "0.85rem", textDecoration: "none" }}>What's Inside</a>
          <a href="#faq" style={{ color: "#475569", fontSize: "0.85rem", textDecoration: "none" }}>FAQ</a>
          <a href={`mailto:${CONFIG.brand.contact}`} style={{ color: "#475569", fontSize: "0.85rem", textDecoration: "none" }}>{CONFIG.brand.contact}</a>
        </div>
        <p style={{ color: "#2D3748", fontSize: "0.78rem" }}>© {new Date().getFullYear()} ExportVault.in · All rights reserved</p>
      </div>
    </footer>
  );
}

function StickyBar() {
  return (
    <div className="sticky-bar">
      <div>
        <div className="syne" style={{ fontWeight: 700, color: "#E2E8F0", fontSize: "0.95rem" }}>Exporter's Toolkit</div>
        <div style={{ color: "#64748B", fontSize: "0.78rem" }}>Instant Download · GST Invoice</div>
      </div>
      <a href={CONFIG.buyUrl} className="btn-primary" style={{ padding: "10px 20px", fontSize: "0.9rem", whiteSpace: "nowrap" }}>
        Buy Now · {CONFIG.hero.price}
      </a>
    </div>
  );
}

export default function ExportVault() {
  return (
    <>
      <style>{styles}</style>
      <Nav />
      <main>
        <Hero />
        <hr className="divider" />
        <Problem />
        <hr className="divider" />
        <Features />
        <hr className="divider" />
        <Trust />
        <hr className="divider" />
        <Pricing />
        <hr className="divider" />
        <FAQ />
      </main>
      <Footer />
      <StickyBar />
    </>
  );
}
