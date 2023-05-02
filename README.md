Historical DEX data for visualizations

# General notation
`mm` = Market maker. For now, market makers are defined to be addresses that have traded more than 100M USD notional volume over past 30 days.
`px` = price
`sz` = size in units of the coin (base currency)
`ntl` = notional value, `px * sz`
`crossed` = whether the order removed liquidity
`ntl_pos` = notional position

# Files
`non_mm_trades.csv` lists trades where at least one side was not a market maker
`liquidations.csv` lists all liquidations
`non_mm_ledger_updates.csv` lists deposits and withdrawals excluding market makers
