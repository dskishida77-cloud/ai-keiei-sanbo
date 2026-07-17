# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## プロジェクト概要

このプロジェクトは現在初期段階です。コードが追加され次第、このファイルにビルド・Lint・テストコマンドやアーキテクチャの概要を追記してください。

## Git運用ルール

- **コードを変更するたびに、コミットしてGitHubにプッシュすること。** 変更を未プッシュのままローカルに留め置かない。
- コミットは意味のある単位に分け、変更内容が分かるコミットメッセージを付けること。
- プッシュ前に `git status` / `git diff` で変更内容を確認すること。
- force push（`push --force` 等)や履歴を破壊する操作は、ユーザーの明示的な許可なく行わないこと。
- 機密情報（APIキー、トークン等）を含むファイルはコミット・プッシュしないこと。
