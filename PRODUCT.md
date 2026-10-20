# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Two audiences, equal weight (confirmed):

- **Prospective families** — parents in and around Ferraz de Vasconcelos (SP) comparing schools for a child from Early Childhood to High School. They decide whether to visit, enroll, or apply for a need-based scholarship. Mostly on phones, often arriving from WhatsApp, Facebook or search.
- **Current families** — parents who return for practical answers: supply lists, class times, the yearly enrollment notice, scholarship documents, and a school-transport driver for their neighborhood.

Secondary audience: Spanish-speaking partners from the Brazil–Argentina exchange (IEA, José C. Paz, Buenos Aires), and occasional English-speaking visitors. The site is offered in PT (default), EN and ES.

## Product Purpose

The public website of the Instituto Educacional Luterano, a Lutheran faith-based school founded in 1981 as a social project and today run by OASE, part of the Synodal Education Network (Rede Sinodal). It exists to win new families and to spare current ones a phone call.

Success (all confirmed):

- a family schedules a visit;
- a family starts enrollment or a scholarship application (downloads the notice/forms);
- a conversation with the front office starts on WhatsApp;
- a family resolves a question alone (list, schedule, driver) without calling.

## Positioning

- Origin as a social project (Centro Social Talita Cumi, 1981) that still runs today; need-based scholarships (Bolsa Social) every year.
- Confessional Lutheran values (love, respect, responsibility, justice) inside the national Rede Sinodal network of 50+ schools.
- A full path in one place, from Maternal to Ensino Médio, in the center of Ferraz.
- An international exchange with an Argentine Lutheran school.

## Operating Context

- Front office (secretaria) Mon–Fri 8:00–17:30; treasury Mon–Fri 7:30–16:30 (São Paulo time). The site shows "open now" from these hours (holidays not handled).
- Contact runs through WhatsApp (11) 99173-3538 and phones (11) 4678-1461 / 4678-1564. The contact form has no backend: it opens WhatsApp with the message pre-filled.
- Enrollment cycle is yearly (currently 2027): enrollment notice (DOCX), scholarship notice, application and document list (PDF), and per-grade supply lists (JPEG/PDF) in `docs/`. These documents exist only in Portuguese.
- Partner school-transport drivers are listed per neighborhood (79 neighborhoods, 9 drivers), embedded in the page script.

## Capabilities and Constraints

- Single static page `index.html` (inline CSS/JS, no build step, no framework), plus `img/`, `video/hero.mp4`, `docs/`.
- Light/dark theme (follows the system, manual toggle remembered); PT/EN/ES switch with translations kept beside each element (`data-en`, `data-es`).
- News cards open native-dialog photo albums from `img/noticias/<album>-<n>.jpg`; the latest news shown dates from 2019, and recent news lives on Facebook.
- **Undecided:** who maintains the site and how it is published/hosted. Until decided, updates (news, yearly documents, drivers) mean editing the HTML by hand.

## Brand Commitments

- Name: Instituto Educacional Luterano ("o Luterano"); logos `img/logo-escura.png` (light backgrounds) and `img/logo.png` (dark backgrounds).
- Existing identity: school blue, lime yellow and red; Montserrat for headings, Nunito Sans for body.
- The owner wants the small red uppercase labels above section headings kept.
- Voice: warm, direct, addressed to parents ("seu filho"); faith values stated plainly, never preachy.

## Evidence on Hand

- Real photos of facilities, activities, the exchange and six 2018–2019 events (8 photos each) in `img/`; hero video `video/hero.mp4`.
- Real history timeline (1981, 1983, 1992, 1994, 2002), a quote from DIEGEP (Buenos Aires), named nutritionist and teachers.
- No testimonials from families, no rankings, exam results or enrollment numbers. None of these may be invented; tuition values exist only inside the enrollment notice.

## Product Principles

1. Every page answers the two jobs: help a new family decide, and help a current family resolve something fast.
2. WhatsApp is the main channel; every path should be able to end in a pre-filled message.
3. Practical information (hours, documents, lists, transport) is never more than a tap away and never hidden behind marketing.
4. Tell the true story (social origin, values, real photos); never fabricate proof.
5. Mobile first: most parents arrive on a phone.

## Accessibility & Inclusion

- WCAG AA contrast in both themes; keyboard navigation and visible focus; respects reduced motion, reduced transparency and increased contrast.
- Three languages; documents remain Portuguese-only and are labeled as such.
