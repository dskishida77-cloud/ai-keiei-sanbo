# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## プロジェクト概要

「AI経営参謀」プロジェクト。AI議事録SaaS「MeetMemo」の事業検討ドキュメント（事業検証レポート、PEST/SWOT/3Cによる戦略設計、事業計画書草案）をMarkdownで管理している。

- ドキュメントのファイル名は `<種別>_<対象>_<YYYYMMDD>.md` 形式（例: `事業計画書_MeetMemo_草案_20260717.md`）。
- 現時点ではコードはなく、ビルド・Lint・テストコマンドもない。コードが追加されたら、ここにコマンドとアーキテクチャの概要を追記すること。

## Git運用ルール

- **コードやドキュメントを変更するたびに、コミットしてGitHub（`origin`: https://github.com/dskishida77-cloud/ai-keiei-sanbo）にプッシュすること。** 変更を未プッシュのままローカルに残さない。
- 作業ブランチは `main`。プッシュは `git push origin main`。
- コミットは意味のある単位に分け、変更内容が分かるメッセージを付けること（既存の履歴に合わせ、英語の命令形で簡潔に。例: `Add MeetMemo business plan draft`）。
- コミット前に `git status` / `git diff` で変更内容を確認し、意図しないファイル（`.DS_Store` など）を含めないこと。
- force push（`git push --force` 等）や履歴を書き換える操作は、ユーザーの明示的な許可なく行わないこと。
- APIキーやトークンなどの機密情報を含むファイルはコミット・プッシュしないこと。
