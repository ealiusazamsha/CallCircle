# CallCircle Monorepo

## Branch responsibilities

- `main`: stable integration branch. Only merge via PR.
- `react_admin_dashboard`: React admin portal (folder: `frontend-web/`).
- `flutter_frontendcode`: Flutter mobile app (folder: `frontend-mobile/`).
- `call_services_laravel`: Laravel backend services (folder: `backend/`).
- `reverse_proxy_cdn`: reverse proxy / CDN / infra (folder: `infra/`).

## Agent workflow

Each agent works primarily on its branch and may create feature branches:

- React Admin Agent: `react_admin_dashboard`, `react_admin_dashboard/feat-*`
- Laravel Agent: `call_services_laravel`, `call_services_laravel/feat-*`
- Flutter Agent: `flutter_frontendcode`, `flutter_frontendcode/feat-*`
- DevOps Agent: `reverse_proxy_cdn`, `reverse_proxy_cdn/feat-*`

All production-ready changes are eventually merged into `main` via PR.
