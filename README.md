mollii-web-platform/
│
├── apps/
│   ├── web/                         # Public website
│   │   ├── app/
│   │   │   ├── page.tsx
│   │   │   ├── about/
│   │   │   ├── monocle-optical/
│   │   │   ├── innovations/
│   │   │   ├── research/
│   │   │   ├── investors/
│   │   │   └── contact/
│   │   ├── components/
│   │   ├── layouts/
│   │   └── public/
│   │
│   ├── portal/                      # Secure stakeholder portal
│   │   ├── dashboard/
│   │   ├── projects/
│   │   ├── documents/
│   │   ├── investors/
│   │   └── analytics/
│   │
│   └── admin/                       # Administrative control centre
│       ├── users/
│       ├── permissions/
│       ├── uploads/
│       ├── budgets/
│       ├── audit/
│       └── settings/
│
├── packages/
│   ├── ui/                          # Shared design system
│   ├── branding/                    # MOLLii / Monocle identity switching
│   ├── auth/                        # MFA + RBAC
│   ├── database/                    # PostgreSQL schema/client
│   ├── audit/                       # Immutable audit events
│   ├── storage/                     # Secure document/media storage
│   ├── webgl/                       # Three.js/WebGL components
│   └── security/                    # Security utilities
│
├── services/
│   ├── api/
│   ├── authentication/
│   ├── document-service/
│   ├── notification-service/
│   └── audit-service/
│
├── infrastructure/
│   ├── terraform/
│   ├── kubernetes/
│   ├── networking/
│   ├── databases/
│   ├── storage/
│   └── monitoring/
│
├── database/
│   ├── migrations/
│   ├── schema/
│   └── seed/
│
├── security/
│   ├── policies/
│   ├── threat-model/
│   ├── access-control/
│   └── incident-response/
│
├── docs/
│   ├── architecture/
│   ├── api/
│   ├── governance/
│   ├── deployment/
│   └── user-guides/
│
├── tests/
│   ├── unit/
│   ├── integration/
│   ├── e2e/
│   └── security/
│
├── .github/
│   └── workflows/
│       ├── ci.yml
│       ├── security.yml
│       └── deploy.yml
│
├── .env.example
├── docker-compose.yml
├── package.json
├── turbo.json
├── README.md
└── LICENSE

# L0_07
Build 
