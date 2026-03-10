# Hi there, I'm Jacob 👋 

> **"Turning p-values into profit"**
> *| Aspiring Quantitative Analyst*
> *| Financial Markets Passionate*

---

```python
while market_is_open:
    try:
        data  = fetch_market_data()
        alpha = calculate_edge(data)
        
        if is_significant(alpha, p_threshold=0.01):
            optimize_portfolio(objective="MaxSharpe")
            execute_trade()
            
    except MarketVolatility:
        buy_the_dip_and_sip_coffee()
