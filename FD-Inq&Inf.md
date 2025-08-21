```mermaid
flowchart LR
    F["Inflation"]

    %% Channels
    A["Inflation Tax / Flight from Cash"]
    B["Portfolio Composition"]
    C["Wage & Income Rigidity"]

    %% Financial Development Effects (multiline, single line per item)
    A_sub["FD Effects:<b></br> Burden on Cash Holders<b></br> Flight from Cash"]
    B_sub["FD Effects:<b></br> Access to Hedging Assets<b></br> Financial Literacy Gap<b></br> Wealth Concentration"]
    C_sub["FD Effects:<b></br> Wage Lag / Sticky Wages<b></br> Access to Credit & Income Smoothing<b></br> Bargaining Power via Inclusion"]

    %% Flow connections
    F --> A --> A_sub --> G["Income Inequality"]
    F --> B --> B_sub --> G
    F --> C --> C_sub --> G

```
