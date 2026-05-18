# Daily Update Log

Last updated: 2026-05-18

## 2026-05-18

- Scope: Initial operational data folder created and expanded for persistent user taste modeling.
- Files updated:
  - `official-guides.md`
  - `creator-registry.md`
  - `creator-lifecycle.md`
  - `restaurant-ledger.md`
  - `taste-profile.md`
  - `recommendation-queue.md`
  - `category-analysis.md`
  - `source-watchlist.md`
  - `trust-rubric.md`
  - `daily-update-log.md`
- Official guide changes: Not populated.
- Creator registry changes: Seed audit targets only.
- Creator lifecycle changes: Lifecycle file added; seed creators set to watch status, not trusted status.
- Restaurant ledger changes: Empty ledger initialized.
- User feedback added: None.
- Trust score changes: None.
- Sources checked: None.
- Next checks: Choose region scope, audit official guide sources, audit creator official channels, and begin populating not-yet-visited recommendation queue.

## 2026-05-18 - 재슐랭 3만원 이하 큐 업데이트

- Scope: 재슐랭가이드 최근 1개월 중 공식 YouTube RSS에서 확인된 2026-04-29~2026-05-16 업로드 기준, 3만원 이하 후보 추림.
- Files updated:
  - `recommendation-queue.md`
  - `creator-registry.md`
  - `source-watchlist.md`
  - `daily-update-log.md`
- Official guide changes: None.
- Creator registry changes: 재슐랭가이드 공식 YouTube 채널/Instagram 링크 추가, 조건부 신뢰 B로 임시 설정.
- Restaurant ledger changes: Not fully populated yet; queue-first update.
- Operational status changes: 개별 매장 운영 상태는 아직 지도/예약 페이지로 검증 전.
- User feedback added: None.
- Trust score changes: 재슐랭가이드 최근 저가 추천 후보는 `B`로 시작. 직접 방문 피드백 전까지 `A` 이상 금지.
- Sources checked:
  - YouTube RSS `https://www.youtube.com/feeds/videos.xml?channel_id=UCzgpOnor-MzT-1iflZil2GQ`
  - 재슐랭가이드 공식 채널 `https://www.youtube.com/channel/UCzgpOnor-MzT-1iflZil2GQ`
- Conflicts/unresolved:
  - RSS는 최신 15개만 안정적으로 제공되어 2026-04-18~2026-04-28 구간은 보강 필요.
  - Instagram 공식 최근 포스트 상세는 공개 검색에서 확인 부족.
  - 매장별 휴무/예약/폐업 여부는 별도 운영 확인 필요.
- Next checks: 각 매장 Naver/Kakao/CatchTable/Instagram 운영 상태 확인 후 restaurant-ledger.md 정식 등재.

## 2026-05-18 - 재슐랭 최근 3개월 Top 10 작성

- Scope: 재슐랭가이드 official YouTube/Shorts, 2026-02-18 to 2026-05-18.
- Files updated:
  - `jaesullang-3mo-top10-2026-05-18.md`
  - `daily-update-log.md`
- Official guide changes: None.
- Creator registry changes: None.
- Restaurant ledger changes: Not fully populated; analysis file created first.
- Operational status changes: Not checked.
- User feedback added: None.
- Trust score changes: None.
- Sources checked:
  - 재슐랭가이드 official YouTube channel
  - 재슐랭가이드 official YouTube Shorts
  - Video/Shorts descriptions for restaurant names and prices
- Conflicts/unresolved:
  - Instagram recent posts not included.
  - Naver/Kakao/CatchTable operational checks pending.
  - Roundup videos can include shared dishes; price ceiling is based on listed representative menu, not guaranteed full meal total.
- Next checks: Promote selected Top 10 entries into `restaurant-ledger.md` after operational verification.

## 2026-05-18 - 재슐랭 Top 10 상세 정보 보강

- Scope: Add recommendation reason, main menu, price band, location, and source links to each Top 10 table.
- Files updated:
  - `jaesullang-3mo-top10-2026-05-18.md`
  - `daily-update-log.md`
- Sources checked: Existing YouTube/Shorts description extraction from the previous audit.
- Conflicts/unresolved:
  - Operational status remains unchecked.
  - Menus/prices remain description-based and may differ from current store menus.
- Next checks: Verify top candidates against Naver/Kakao/CatchTable/Instagram before final visit plan.

## 2026-05-18 - 1군 맛집러 최근 3개월 정리

- Scope: 재슐랭가이드, 잡식맨, 김사원세끼, 빅페이스, 서울 사는 남자, 정육왕 recent 3-month YouTube audit.
- Files updated:
  - `first-tier-creators-3mo-2026-05-18.md`
  - `creator-registry.md`
  - `taste-profile.md`
  - `source-watchlist.md`
  - `daily-update-log.md`
- Creator registry changes: 1군 creators promoted to `active`; 재슐랭/잡식맨/김사원세끼/빅페이스/서울 사는 남자/정육왕 treated as core sources.
- Taste profile changes: User's first-tier creator preference and 정육왕 trust signal added.
- Sources checked:
  - Official YouTube channels through yt-dlp metadata and video descriptions.
  - Public channel/search results for channel identity.
- Conflicts/unresolved:
  - 서울 사는 남자 videos often expose map links rather than full restaurant names in descriptions; needs map/list extraction.
  - 빅페이스 recent 3 months had limited direct restaurant queue candidates.
  - 정육왕 sponsored/production-supported videos must remain labeled even though creator trust is high.
- Next checks: Extract 서울 사는 남자 map entries and verify P1/P2 candidates operationally.

## 2026-05-18 - 재슐랭 추천이유 재작성

- Scope: Improve recommendation reasons in `jaesullang-3mo-top10-2026-05-18.md`.
- Files updated:
  - `jaesullang-3mo-top10-2026-05-18.md`
  - `daily-update-log.md`
- Change summary: Replaced shallow monthly-rank reasons with practical queue reasons: repeated mention, monthly rank context, price efficiency, category fit, user taste fit, and visit caveats.
- Next checks: Apply the same reason-quality standard to the 10만원/5만원/3만원 tables if needed.
## 2026-05-18 - Creator source pool separated

- Scope: Move the Top 30 / supporting-layer creator classification into its own first-pass influencer source document.
- Files updated:
  - `creator-source-pool.md`
  - `source-watchlist.md`
  - `daily-update-log.md`
- Change summary: Created a dedicated source-pool document for first-tier creators, secondary category layers, fine-dining/watch-only channels, chef support channels, removed channels, and future candidate creators.
- Operating decision: Do not force a full Top 30 if quality or taste fit is weak. Keep the source pool as a living list for add/update/delete decisions.
- Next checks: Use `creator-source-pool.md` as the first document to update when adding or removing food creators.

## 2026-05-18 - Course and omakase detail requirement

- Scope: Add a baseline requirement for course meals, tasting menus, kappo, chef's counter, sushi omakase, and other omakase formats.
- Files updated:
  - `restaurant-ledger.md`
  - `taste-profile.md`
  - `.codex/skills/restaurant-trust-intelligence/SKILL.md`
  - `.codex/skills/restaurant-trust-intelligence/references/restaurant-ledger.md`
  - `daily-update-log.md`
- Change summary: Course/omakase recommendations must include major course items and dish-level characteristics when available, not just a category label and price.
- Next checks: Backfill existing omakase/fine-dining candidates with representative course menus before ranking them highly.

## 2026-05-18 - User feedback: 잡식맨 pizza signal

- Scope: Add explicit user taste feedback for 잡식맨's domestic No.1 pizza recommendation.
- Files updated:
  - `taste-profile.md`
  - `first-tier-creators-3mo-2026-05-18.md`
  - `creator-source-pool.md`
  - `daily-update-log.md`
- Change summary: Pizza/pizzeria is now a high-confidence positive taste category when sourced from 잡식맨 ranking/comparison-style recommendations. `포폴로 피자` moved from P2 to P1 in the first-tier creator queue.
- Unresolved: The Gangnam-area pizza restaurant referenced by the user is not yet identified in the local notes and should be mapped to the exact restaurant/source video later.

## 2026-05-18 - 재슐랭 Top 10 상세 판단 보강

- Scope: Make the 재슐랭 recent 3-month Top 10 usable for actual visit decisions, not just a shallow ranking table.
- Files updated:
  - `jaesullang-3mo-top10-2026-05-18.md`
  - `daily-update-log.md`
- Sources checked:
  - 재슐랭 2026 월간재슐랭 2월/3월/4월 official YouTube descriptions.
  - 재슐랭 단독 Shorts descriptions for 타키타테 카마바, 카키코우죠, 카나데, 타파코파, 서보, 스시지현, 소바하우스 멘야준, 캐비스트리, 무스, 우주돈, 스시 스이신, 부산 고옥, 코우짱라멘, 수저가.
- Change summary: Added a restaurant-by-restaurant detailed judgment section with at least three practical recommendation lines for each Top 10 restaurant and menu-by-menu notes. Added additional price-tier candidate notes, especially marking course/omakase items as incomplete when detailed course composition is unavailable.
- Unresolved: Operational status and current menus still need Naver/Kakao/CatchTable/Instagram verification before a final visit plan.

## 2026-05-18 - Core taste signal: category peak and personal canon

- Scope: Add user's explicit preference for category-best, extreme-value, craft-quality, and personal-canon recommendations.
- Files updated:
  - `taste-profile.md`
  - `trust-rubric.md`
  - `creator-source-pool.md`
  - `.codex/skills/restaurant-trust-intelligence/SKILL.md`
  - `daily-update-log.md`
- Change summary: The system now prioritizes trusted creators' "domestic No.1", "category best", "life-best", "regular haunt", "must-experience", "extreme value with quality", and "master craft" signals. Generic promotion, marketing-heavy, viral hot-place, or sponsorship-heavy creators are downgrade/removal candidates.
- Example anchor: 잡식맨's domestic No.1 pizza recommendation worked well for the user, so similar comparison/ranking finalist signals should score highly across categories, not just pizza.

## 2026-05-18 - Creator selection baseline clarified

- Scope: Make creator inclusion criteria explicit.
- Files updated:
  - `creator-source-pool.md`
  - `taste-profile.md`
  - `.codex/skills/restaurant-trust-intelligence/SKILL.md`
  - `daily-update-log.md`
- Change summary: New creators should pass one of two primary filters: their taste is similar to the user, or their taste is clearly more advanced/high-end than the user. Creators that are famous but neither taste-aligned nor high-skill/high-end are held or removed, especially if promotional.

## 2026-05-18 - Standard recommendation format adopted

- Scope: Adopt the user's preferred recommendation format as the default skill output.
- Files updated:
  - `.codex/skills/restaurant-trust-intelligence/SKILL.md`
  - `daily-update-log.md`
- Change summary: Ranked recommendations now default to `식당별 3줄 추천 + 메뉴별 추천 사유`, including price-tier tables. Shallow one-line reasons are no longer sufficient.

## 2026-05-18 - 재슐랭/잡식맨 3개월 가격대별 MD 저장

- Scope: Save the standard price-tier recommendation format into the existing 재슐랭 3-month file and create the same-style 잡식맨 3-month file.
- Files updated:
  - `jaesullang-3mo-top10-2026-05-18.md`
  - `jobxicman-3mo-top10-2026-05-18.md`
  - `daily-update-log.md`
- Sources checked:
  - 재슐랭 existing extracted YouTube/Shorts data.
  - 잡식맨 official YouTube videos from 2026-02-18 to 2026-05-18.
  - 잡식맨 selected video descriptions and auto-subtitles for videos with sparse descriptions.
- Change summary:
  - Added a `표준 가격대별 추천표` section to the 재슐랭 file.
  - Created a 잡식맨 file with content audit, price-agnostic ranking, 10만원/5만원/3만원 이하 tables, exclusions, and next checks.
- Caveats:
  - 잡식맨 descriptions often omit menu prices and addresses, so several price-tier placements are provisional and marked `가격 확인 필요`.
  - `도량` has product/milkit linkage and remains hold/ad-risk.
  - 부산 해운대 분식/빙수 entry is subtitle-based and needs exact store verification.
## 2026-05-18 - 거대곰탕 cross-creator miss noted

- Scope: Respond to user correction that 거대곰탕 also appeared in 재슐랭.
- Files updated:
  - `jobxicman-3mo-top10-2026-05-18.md`
  - `jaesullang-3mo-top10-2026-05-18.md`
  - `.codex/skills/restaurant-trust-intelligence/SKILL.md`
  - `daily-update-log.md`
- Change summary:
  - Added mandatory cross-creator reconciliation rule to the skill.
  - Marked 거대곰탕 as a high-priority cross-check candidate in 잡식맨 file.
  - Added a 재슐랭 cross-check pending note to the 재슐랭 file.
- Verification status:
  - Current local notes and YouTube title/description searches did not verify 재슐랭 거대곰탕 evidence.
  - User-reported evidence is recorded separately and must be checked against 재슐랭 Instagram/map/list/in-video sources.

## 2026-05-18 - 거대곰탕 재슐랭 Shorts 누락 원인 확정

- Scope: User supplied the direct 재슐랭 Shorts URL for 거대곰탕 서초 and asked for a miss review plus improvement plan.
- Confirmed source:
  - 재슐랭가이드 Shorts, 2026-02-21, `진짜 비싼 곰탕집, 이거 괜찮은가요?`
  - URL: https://www.youtube.com/watch?v=lLi_T0eknP0
  - Description includes `거대곰탕 서초`, `#거대곰탕`, `#거대곰탕서초`, menu prices, and location.
- Root cause:
  - The Shorts title does not include the restaurant name.
  - Previous extraction relied too much on YouTube title/search results and did not guarantee full Shorts description/hashtag indexing for every upload.
  - Cross-creator reconciliation found 잡식맨 부산 거대곰탕 but did not immediately reverse-search aliases across 재슐랭 Shorts descriptions.
- Files changed:
  - `jaesullang-3mo-top10-2026-05-18.md`: moved 거대곰탕 서초 from pending to confirmed correction and added menu-level notes.
- Improvement:
  - For each first-tier creator update, collect Shorts as first-class content and parse title, description, hashtags, upload date, auto captions, and aliases.
  - For each candidate restaurant found from one first-tier creator, run reverse lookup across all first-tier creators using canonical name plus aliases and location variants.
  - Store `confirmed`, `user-reported pending`, and `searched/no-hit` states separately; never collapse a no-hit into absence when Shorts/OCR/captions have not been checked.
