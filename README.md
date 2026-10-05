# TakezawaKouki

栃木県を拠点に、Webアプリケーションを個人開発しています。
業務で使える実用的なアプリ(注文管理・家計管理など)から、Three.js を使った3Dウェブアプリまで、企画・設計・実装・公開までを一人で進めています。

## 技術スタック

| 分野 | 使用技術 |
| :-- | :-- |
| フロントエンド | TypeScript / React / Next.js (App Router) / Vite / Tailwind CSS |
| バックエンド・DB | Next.js Route Handlers・Server Actions / Prisma / PostgreSQL / Supabase / Cloudflare Pages Functions |
| 認証 | NextAuth (Auth.js) / Supabase Auth |
| 3D・可視化 | Three.js / react-three-fiber / Recharts / Leaflet |
| テスト・運用 | Playwright (E2E) / GitHub Actions / Vercel / Cloudflare |
| その他 | Python / Blender(3Dモデルの手続き生成) |

## 代表的な作品

| 作品 | 概要 | 技術 | デモ |
| :-- | :-- | :-- | :-- |
| [hotsand-order](https://github.com/kouki-takezawa/hotsand-order) | ホットサンド店向けQRコード注文システム。客のスマホ注文、受け取り/配達、注文管理、売上分析、Web Push通知 | Next.js / Prisma / PostgreSQL / Playwright | [開く](https://hotsand-order.vercel.app) |
| [enoden-walk](https://github.com/kouki-takezawa/enoden-walk) | 江ノ電・鎌倉高校前を人物を操作して歩き回れる3Dウェブアプリ。国土交通省 PLATEAU / OpenStreetMap のデータから生成 | Three.js / Vite / Blender | [開く](https://enoden-walk.vercel.app) |
| [michinoeki-stamp-rally](https://github.com/kouki-takezawa/michinoeki-stamp-rally) | 全国1,231駅の道の駅スタンプラリーPWA。地図・チェックイン・制覇率・フレンド機能 | React / Supabase / Leaflet | [開く](https://michinoeki-stamp-rally.vercel.app) |
| [tochigi-farm-market](https://github.com/kouki-takezawa/tochigi-farm-market) | 全国の農家と買い手をつなぐ直売マルシェ。サーバーレス構成で運用コストをほぼ0円に | Cloudflare Pages / Supabase / R2 | [開く](https://tochigi-farm-market.pages.dev) |
| [income-management-web](https://github.com/kouki-takezawa/income-management-web) | 給与・残業・賞与・有給・家計簿・資産推移をまとめて管理。手取り概算、CSV/PDF出力 | Next.js / Prisma / PostgreSQL | [開く](https://nenshu-kanri-web.vercel.app) |
| [solar-system-explorer](https://github.com/kouki-takezawa/solar-system-explorer) | 太陽系タイムトラベル・ビジュアライザー。ケプラー軌道要素から天体位置をリアルタイム計算 | React / react-three-fiber / zustand | [開く](https://solar-system-explorer-inky.vercel.app) |

## 開発で大事にしていること

- **動くものを公開する**: すべての作品を Vercel / Cloudflare にデプロイし、実際に触れる状態にしています。
- **設計判断を言葉にする**: 各リポジトリの README に、機能だけでなく「なぜその構成にしたか」「既知の制約」を書いています。
- **AIを活用した開発**: Claude Code などの AI ツールを使って開発しています。生成されたコードは設計意図を理解したうえで取り込み、動作確認とテストで検証します。

## 連絡先

GitHub のプロフィールからご連絡ください。
