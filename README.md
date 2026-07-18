# Local Alert Radar

開店閉店・地域アラート

## Repository

Recommended repository name: `local-alert-radar`

## Domain candidates

First candidate: `localalert.jp`

Other candidates:

- `localalert.jp`
- `machialert.jp`
- `openclosealert.jp`
- `tenpoalert.jp`

## Concept

開店、閉店、移転、休業、再開、求人、災害や遅延時の周辺スポット通知をLINEとXへ展開する地域アラートメディア。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static seed records in `src/App.jsx`
- UGC: localStorage for MVP posts and saved leads
- Deployment target: GitHub Pages or static hosting
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 新店掲載課金
- LINE有料アラート
- 求人送客
- クーポン配信
- 地域PR記事

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
