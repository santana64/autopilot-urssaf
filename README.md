# Autopilot URSSAF - Automatisation des Declarations pour Freelances

SaaS pour auto-entrepreneurs et freelances. Automatisez vos declarations URSSAF, suivez vos cotisations et ne ratez plus jamais une echeance.

## Stack

- Next.js 14 (App Router)
- PostgreSQL + Prisma
- Stripe (abonnement premium)
- Resend + Nodemailer (alertes echeances)
- React Hook Form + Zod
- Tailwind CSS

## Fonctionnalites

- Calendrier des echeances URSSAF personnalise par regime
- Calcul automatique des cotisations selon le CA declare
- Rappels email avant chaque echeance (J-30, J-7, J-1)
- Historique des declarations et paiements
- Simulation de charges selon differents niveaux de CA
- Support micro-entrepreneur, EIRL, SASU

## Demarrage

bash
npm install
npx prisma migrate dev
npm run dev


Variables requises : DATABASE_URL, STRIPE_SECRET_KEY, RESEND_API_KEY