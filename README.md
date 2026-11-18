# MoneyFlow Expense Tracker

A responsive personal-finance dashboard built with React, TypeScript, and Vite. Add and remove income or expense transactions, review totals in PKR, track a monthly budget, and search transaction history. Transactions are saved in the browser's local storage.

## Project structure

```text
src/
  assets/
    images/                 # Local dashboard illustrations and backgrounds
  components/
    dashboard/              # Header, summary, transaction form, budget, tips, table
    layout/                 # App navigation and shell components
  constants/                # Budget, storage key, and category options
  hooks/                    # Transaction state and derived finance summary
  styles/                   # Global dashboard styles
  types/                    # Shared TypeScript domain types
  utils/                    # Currency formatting and transaction persistence
  App.tsx                   # Dashboard composition
```

UI components receive data and callbacks through props. The transaction hook owns state and persistence; the summary hook derives totals; shared types, constants, and utilities keep those concerns reusable.

## Run locally

```sh
npm install
npm run dev
```

## Validate

```sh
npm run build
npm run lint
```
