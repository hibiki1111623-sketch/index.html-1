
<html lang="ja">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>更新・運用・保守ポートフォリオ｜西村</title>
  <style>
    :root { --bg:#0b0c10; --card:#12141a; --text:#e7e7ea; --muted:#a9acb3; --line:#232633; }
    body { margin:0; font-family: system-ui, -apple-system, "Segoe UI", sans-serif; background:var(--bg); color:var(--text); }
    a { color:#8ab4ff; text-decoration:none; }
    .wrap { max-width: 920px; margin: 0 auto; padding: 28px 16px 64px; }
    header { padding: 18px 0 10px; border-bottom: 1px solid var(--line); }
    h1 { margin: 0 0 8px; font-size: 26px; }
    .sub { margin: 0; color: var(--muted); }
    .grid { display: grid; gap: 14px; margin-top: 18px; }
    @media (min-width: 860px){ .grid { grid-template-columns: 1fr 1fr; } }
    section { background: var(--card); border: 1px solid var(--line); border-radius: 14px; padding: 16px; }
    h2 { margin: 0 0 10px; font-size: 18px; }
    ul { margin: 0; padding-left: 18px; color: var(--text); }
    li { margin: 6px 0; color: var(--text); }
    .muted { color: var(--muted); font-size: 13px; line-height: 1.6; }
    .badge { display:inline-block; padding: 4px 8px; border: 1px solid var(--line); border-radius: 999px; font-size: 12px; color: var(--muted); margin-right: 6px; }
    .mono { font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace; font-size: 12px; }
    .callout { border-left: 3px solid #8ab4ff; padding-left: 10px; }
    footer { margin-top: 18px; color: var(--muted); font-size: 13px; }
    .kpi { display:flex; gap:8px; flex-wrap:wrap; margin-top: 8px; }
    .imgbox { border:1px dashed var(--line); border-radius: 12px; padding: 12px; }
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <h1>更新・運用・保守ポートフォリオ</h1>
      <p class="sub">「月次更新」「軽微修正」「WP更新・バックアップ」を、安全に回すための手順と報告例です（デモ）。</p>
      <div class="kpi">
        <span class="badge">返信：原則24時間以内</span>
        <span class="badge">方針：壊さない運用</span>
        <span class="badge">報告：変更点メモ＋スクショ</span>
      </div>
    </header>

    <div class="grid">
      <section>
        <h2>対応できる作業</h2>
        <ul>
          <li>テキスト追記・文言差し替え・リンク修正</li>
          <li>画像差し替え／サイズ調整（素材ご支給前提）</li>
          <li>ページ追加・既存ページの追記（WordPress / 静的HTMLどちらも）</li>
          <li>CSS軽微調整（余白・文字サイズ・配置）</li>
          <li>スマホ表示の軽微調整（はみ出し・余白・縦並び調整）</li>
          <li>お問い合わせフォームの軽微調整（項目・通知・文言）</li>
          <li>WordPress／プラグイン更新、更新後の表示・動作確認</li>
          <li>簡易バックアップ（可能な範囲で）</li>
        </ul>
        <p class="muted">※大規模開発・フルスクラッチ制作は対応外。影響が大きい変更は事前にリスクと方針を共有します。</p>
      </section>

      <section>
        <h2>運用の進め方（安全手順）</h2>
        <ol class="muted">
          <li><b>依頼内容の確認</b>（対象URL／修正点／素材／期限）</li>
          <li><b>バックアップ</b>（可能な範囲で：DB/ファイル or プラグイン）</li>
          <li><b>影響範囲チェック</b>（更新対象ページ、関連箇所を確認）</li>
          <li><b>反映作業</b>（小さく反映→都度確認）</li>
          <li><b>表示・動作確認</b>（PC/スマホ、フォーム/リンク）</li>
          <li><b>報告</b>（変更点メモ＋スクショ、再現/確認手順）</li>
        </ol>
        <p class="muted callout">「壊さない」「再現できる」「戻せる」を優先して進めます。</p>
      </section>

      <section>
        <h2>報告例（変更点メモのサンプル）</h2>
        <div class="mono">
          <p>【対応日】2026-02-18</p>
          <p>【対象】/service/（サービス紹介）</p>
          <p>【変更】(1) 見出し文言をA→Bに差し替え</p>
          <p>　　　(2) 画像を差し替え（幅を100%に調整）</p>
          <p>　　　(3) SP表示でボタンがはみ出していたため、@media(768px)で縦並びに変更</p>
          <p>【確認】PC/375pxで表示確認、リンク遷移OK</p>
        </div>
        <p class="muted">この「短いメモ＋スクショ2枚」で、発注者が安心して確認できる形にします。</p>
      </section>

      <section>
        <h2>Before / After（スクショ枠）</h2>
        <div class="imgbox muted">
          <p><b>ここにスクショを貼る（おすすめ）</b></p>
          <p>・Before：SPでボタンが横にはみ出す</p>
          <p>・After：縦並びで収まる</p>
          <p>※スクショ画像は <span class="mono">/assets/</span> に入れて、このページに <span class="mono">&lt;img&gt;</span> で表示すると説得力が跳ねます。</p>
        </div>
      </section>
    </div>

    <footer>
      <p>連絡：CrowdWorksメッセージ中心（必要に応じてWeb会議可）／着手：仮払い確認後</p>
      <p><a href="./index.html">← ポートフォリオTOPへ戻る</a></p>
    </footer>
  </div>
</body>
</html>
