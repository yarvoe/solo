# Kolo

A mobile-friendly personal finance tracker for Liberia, with manually entered LRD and USD transactions, monthly budgets, savings goals and JSON backup/restore. Serve this folder using `python3 -m http.server 8001 --bind 0.0.0.0` and open in a modern browser. Data stays in browser localStorage and can be lost if browser data is cleared. There is no bank/mobile-money integration, actual money transfer, currency conversion, account login, cloud sync, or payment/subscription functionality. Savings goal progress is a manual figure, not money held or automatically deducted. Budgets and goals are separate per currency.

Design inspiration: Starpay Finance App UI Kit by Paperpillar, https://www.figma.com/community/file/1407568466727577612/starpay-finance-app-ui-kit-paperpillar, CC BY 4.0 https://creativecommons.org/licenses/by/4.0/. This is an original adaptation of its finance UI idea, not a copied or imported Figma file. No third-party software libraries are used.
