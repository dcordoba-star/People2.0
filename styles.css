/* Variables: paleta y espaciado */
:root {
  --color-white: #FFFFFF;
  --color-gray: #676767;
  --color-yellow: #FFD540;
  --color-bg: #f5f5f5;
  --color-bg-alt: #ebebeb;
  --color-text: #676767;
  --color-text-strong: #3d3d3d;
  --font-title: "Outfit", sans-serif;
  --font-body: "Work Sans", sans-serif;
  --radius: 10px;
  --space-sm: 0.75rem;
  --space: 1.5rem;
  --space-lg: 2rem;
  --space-xl: 3rem;
  --max-width: 1000px;
}

/* Reset y base */
*,
*::before,
*::after {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: var(--font-body);
  font-size: 1rem;
  line-height: 1.6;
  color: var(--color-text);
  background: var(--color-bg);
}

/* Contenedor */
.container {
  max-width: var(--max-width);
  margin: 0 auto;
  padding: 0 var(--space);
}

/* 1. Hero */
.hero {
  background: var(--color-gray);
  color: var(--color-white);
  text-align: center;
  padding: var(--space-xl) var(--space) var(--space-xl);
}

.hero-inner {
  max-width: var(--max-width);
  margin: 0 auto;
}

.hero-title {
  font-family: var(--font-title);
  font-weight: 700;
  font-size: clamp(2rem, 5vw, 3rem);
  letter-spacing: -0.02em;
  margin: 0 0 var(--space-sm);
  line-height: 1.2;
}

.hero-desc {
  font-family: var(--font-body);
  font-size: 1.125rem;
  margin: 0 0 var(--space-lg);
  max-width: 480px;
  margin-left: auto;
  margin-right: auto;
  opacity: 0.95;
}

.btn {
  display: inline-block;
  padding: 0.875rem 1.75rem;
  font-family: var(--font-title);
  font-weight: 600;
  font-size: 1rem;
  text-decoration: none;
  border-radius: var(--radius);
  border: none;
  cursor: pointer;
  transition: transform 0.2s, box-shadow 0.2s;
}

.btn--primary {
  background: var(--color-yellow);
  color: var(--color-text-strong);
}

.btn--primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(255, 213, 64, 0.35);
}

/* Secciones */
.section {
  padding: var(--space-xl) 0;
  background: var(--color-bg);
}

.section--alt {
  background: var(--color-bg-alt);
}

.section-title {
  font-family: var(--font-title);
  font-weight: 700;
  font-size: clamp(1.5rem, 4vw, 1.75rem);
  color: var(--color-text-strong);
  text-align: center;
  margin: 0 0 var(--space-lg);
}

.subsection-title {
  font-family: var(--font-title);
  font-weight: 600;
  font-size: 1.2rem;
  color: var(--color-text-strong);
  margin: var(--space-xl) 0 var(--space);
  text-align: center;
}

.subsection-title:first-of-type {
  margin-top: var(--space-lg);
}

.intro-text {
  font-family: var(--font-body);
  max-width: 640px;
  margin: 0 auto;
  text-align: center;
  font-size: 1.1rem;
  line-height: 1.65;
  color: var(--color-text);
}

/* Tarjetas: fondo blanco 12% opacidad, borde #676767 */
.cards {
  display: grid;
  gap: var(--space);
  margin: 0;
}

.cards--two {
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
}

.cards--three {
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
}

.cards--virtues {
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
}

.card {
  background: rgba(255, 255, 255, 0.12);
  border: 1px solid var(--color-gray);
  border-radius: var(--radius);
  padding: var(--space-lg);
  transition: box-shadow 0.2s, transform 0.2s;
}

.card:hover {
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.06);
  transform: translateY(-2px);
}

.card-title {
  font-family: var(--font-title);
  font-weight: 600;
  font-size: 1.1rem;
  color: var(--color-text-strong);
  margin: 0 0 var(--space-sm);
}

.card p {
  margin: 0 0 var(--space-sm);
  font-size: 0.95rem;
  color: var(--color-text);
}

.card-subtitle {
  font-family: var(--font-title);
  font-weight: 600;
  font-size: 0.9rem;
  color: var(--color-text-strong);
  margin: var(--space) 0 var(--space-sm);
}

.card ul {
  margin: 0 0 var(--space-sm);
  padding-left: 1.25rem;
  font-size: 0.9rem;
  color: var(--color-text);
}

.card li {
  margin-bottom: 0.4rem;
}

.card-link {
  font-family: var(--font-title);
  font-weight: 600;
  font-size: 0.9rem;
  color: var(--color-gray);
  text-decoration: none;
  display: inline-block;
  margin-top: var(--space-sm);
  border-bottom: 1px solid var(--color-gray);
  transition: color 0.2s;
}

.card-link:hover {
  color: var(--color-text-strong);
}

/* Footer */
.footer {
  background: var(--color-gray);
  color: var(--color-white);
  text-align: center;
  padding: var(--space-lg) var(--space);
  font-size: 0.9rem;
}

.footer p {
  margin: 0;
}

/* Responsive: móvil */
@media (max-width: 640px) {
  .hero {
    padding: var(--space-lg) var(--space);
  }

  .section {
    padding: var(--space-lg) 0;
  }

  .container {
    padding: 0 var(--space);
  }

  .cards--two,
  .cards--three,
  .cards--virtues {
    grid-template-columns: 1fr;
  }

  .card {
    padding: var(--space);
  }

  .subsection-title {
    margin-top: var(--space-lg);
    font-size: 1.1rem;
  }
}
