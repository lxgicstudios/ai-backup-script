# ai-backup-script

[![npm version](https://img.shields.io/npm/v/ai-backup-script.svg)](https://www.npmjs.com/package/ai-backup-script)
[![npm downloads](https://img.shields.io/npm/dm/ai-backup-script.svg)](https://www.npmjs.com/package/ai-backup-script)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-backup-script)](https://github.com/lxgic-studios/ai-backup-script/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Generate database backup scripts with AI

## Install

```bash
npm install -g ai-backup-script
```

## Usage

```bash
npx ai-backup-script "PostgreSQL daily to S3"
npx ai-backup-script "MongoDB hourly to GCS"
npx ai-backup-script "MySQL weekly to local with rotation"
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```
