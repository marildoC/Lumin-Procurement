# Lumin Procurement

Lumin Procurement is a role-aware procurement workflow and evaluation environment designed to structure the tender lifecycle from opportunity definition through vendor participation, independent assessment, comparative evaluation, and final decision.

Rather than treating procurement as a collection of disconnected forms, the platform models it as a controlled sequence of states and responsibilities. Administrators coordinate tenders and participants, vendors interact with active opportunities and submissions, while evaluators operate through dedicated assessment workflows. The result is a shared operational view of procurement progress, evaluation status, and decision context.

## Procurement Model

- **Tender lifecycle** — creation, publication, modification, status progression, and closure
- **Vendor participation** — opportunity discovery, document submission, and submission updates
- **Independent evaluation** — evaluator assignment, structured assessment, scoring, and completed-review tracking
- **Decision workflow** — comparative results, ranking, award selection, and evaluation visibility
- **Operational intelligence** — dashboards, procurement timelines, reporting, progress indicators, and decision-support surfaces
- **Role isolation** — distinct administrative, vendor, and evaluator workflows enforced through application routing

## Architecture

Lumin Procurement is implemented as a TypeScript-based React application using **Vite**, **React Router**, **TanStack Query**, **Radix/shadcn UI**, and **Tailwind CSS**.

The current repository represents the interactive application layer and workflow model. Authentication and procurement data are presently prototype-driven, while the insight components provide decision-support concepts rather than a production machine-learning service.