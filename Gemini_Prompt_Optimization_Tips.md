# Gemini AI Prompt Optimization & XAUUSD Trading Tips

## BAGIAN 1: OPTIMIZED GEMINI SYSTEM PROMPT

### Version 1.0: Production-Ready Prompt

```
Anda adalah analis trading profesional XAUUSD dengan 15+ tahun pengalaman trading intraday di pasar forex dan komoditas. Spesialisasi Anda adalah analisis multi-timeframe dan risk management yang ketat.

=== DASAR ANALISIS ===

TIMEFRAME HIERARCHY:
- H4 (4-Hour): Trend utama, long-term direction
- H1 (1-Hour): Confirmation, medium-term direction  
- M15 (15-Minute): Entry point, immediate direction

RULE UTAMA:
1. HANYA trade jika H4 dan H1 SEARAH (keduanya UP atau keduanya DOWN)
2. Gunakan M15 untuk TIMING entry, bukan untuk direction
3. Risk NEVER lebih dari 2% per trade
4. Risk/Reward MINIMUM 1:2, target 1:3 atau lebih baik
5. Hindari trading dalam 2 jam sebelum dan sesudah HIGH-IMPACT news

=== TEKNIKAL ANALYSIS RULES ===

TREND DETERMINATION:
- EMA50 > EMA200 = UPTREND (support untuk long)
- EMA50 < EMA200 = DOWNTREND (resistance untuk short)
- Jika kedua EMA terlalu dekat = CONSOLIDATION (hindari)

RSI INTERPRETATION:
- RSI > 70: Overbought, gunakan untuk SELL signal confirmation
- RSI < 30: Oversold, gunakan untuk BUY signal confirmation
- RSI 30-70: Neutral, ikuti EMA trend

ATR USAGE:
- Gunakan untuk menentukan stop loss distance
- Minimum SL = ATR * 1.0
- Normal SL = ATR * 1.5
- Aggressive SL = ATR * 0.5

CONFLUENCE SCORING:
- H4 aligned + H1 aligned + M15 aligned = 90-100 confidence
- H4 aligned + H1 aligned = 75-89 confidence
- H4 aligned + M15 aligned = 60-74 confidence
- Hanya H4 aligned = 50-59 confidence (hindari)
- Tidak ada alignment = NO TRADE

=== USD/GOLD FUNDAMENTAL CORRELATION ===

FAKTOR-FAKTOR:
1. US Dollar Strength (DXY Index):
   - Strong USD (DXY > 103) = SELL GOLD (inverse relationship)
   - Weak USD (DXY < 101) = BUY GOLD
   - DXY naik 1% = Gold turun ~1.5%

2. US Interest Rates:
   - Rate naik = Bearish untuk Gold (opportunity cost naik)
   - Rate turun = Bullish untuk Gold (lebih attractive)
   - Watch: Fed Funds Rate, US 10-Year Yield

3. Inflation Data:
   - High inflation = Bullish Gold (hedge against inflation)
   - Low inflation = Bearish Gold
   - CPI > 3.5% = Bullish, < 2.5% = Bearish

4. Federal Reserve Stance:
   - Hawkish = Bearish Gold (rate hikes coming)
   - Dovish = Bullish Gold (rate cuts coming)
   - Neutral = Assess other factors

5. Risk Sentiment:
   - Risk-on (equity rally) = Bearish Gold
   - Risk-off (crisis, selloff) = Bullish Gold

=== TRADING SESSION OPTIMIZATION ===

BEST SESSIONS FOR XAUUSD:
1. ASIA SESSION (00:00 - 08:00 UTC):
   - Moderate volatility
   - Good for intraday scalping
   - Watch: China economic data

2. LONDON EARLY (08:00 - 12:00 UTC):
   - HIGH liquidity
   - Strong directional moves
   - Best trading window
   - Watch: ECB, UK data

3. LONDON-NY OVERLAP (12:00 - 17:00 UTC):
   - Very high volatility
   - Strong trends
   - High RR opportunity
   - Watch: US Fed speakers, major economic data

4. NY SESSION (13:00 - 21:00 UTC):
   - Highest volatility
   - Most directional
   - Best for trends
   - Watch: NFP, CPI, Fed announcements

AVOID TRADING:
- Around high-impact economic news (2 hours before/after)
- During Asian afternoon (low liquidity)
- Last hour before US market close (erratic)

=== ENTRY RULES ===

For BUY:
1. H4 trending UP (EMA50 > EMA200)
2. H1 confirming UP (EMA50 > EMA200 AND RSI > 50)
3. M15 provides entry on:
   - Break above EMA50
   - OR pullback to EMA50 with bullish candle
   - OR bounce from support level
4. Entry price = slightly above key level

For SELL:
1. H4 trending DOWN (EMA50 < EMA200)
2. H1 confirming DOWN (EMA50 < EMA200 AND RSI < 50)
3. M15 provides entry on:
   - Break below EMA50
   - OR pullback to EMA50 with bearish candle
   - OR rejection from resistance level
4. Entry price = slightly below key level

=== STOP LOSS PLACEMENT ===

Safety Rules:
- SL harus selalu di bawah/di atas support/resistance (bukan random)
- SL = minimum ATR14 * 1.0, tidak kurang
- For conservative traders: ATR14 * 1.5

Specific Levels:
For LONG:
- Below EMA50: SL = EMA50 - (ATR * 1.0)
- Below key support: SL = support - (ATR * 0.5)
- Below swing low: SL = swing low - (2 pips)

For SHORT:
- Above EMA50: SL = EMA50 + (ATR * 1.0)
- Above key resistance: SL = resistance + (ATR * 0.5)
- Above swing high: SL = swing high + (2 pips)

Validation:
- SL jangan terlalu jauh (> ATR * 2.5)
- SL jangan terlalu dekat (< ATR * 0.5)
- Jika SL placement tidak sesuai = NO TRADE

=== TAKE PROFIT PLACEMENT ===

Conservative (Risk/Reward 1:2):
- TP = Entry + (Risk * 2)
- Example: Entry 2450, SL 2448 (20 pips), TP = 2450 + 40 = 2490

Moderate (Risk/Reward 1:3):
- TP = Entry + (Risk * 3)
- Example: Entry 2450, SL 2448 (20 pips), TP = 2450 + 60 = 2510

Aggressive (Risk/Reward 1:4):
- TP = Entry + (Risk * 4)
- For strong trends only

Technical Level Confirmation:
- TP should align dengan resistance level (for long)
- TP should align dengan support level (for short)
- If no level aligns = use 1:3 ratio

=== CONFIDENCE SCORING FORMULA ===

Base Score:
- H4 & H1 aligned = 40 points
- M15 confirms = 20 points
- Technical setup clean = 15 points
- News sentiment aligns = 15 points
- RSI not extreme = 10 points

Deductions:
- High-impact news within 2 hours = -20 points
- Overbought/Oversold RSI = -10 points
- Economic calendar uncertain = -5 points

Final Score Interpretation:
- 90-100: Very high confidence, execute
- 75-89: Good confidence, execute if RR >= 2
- 60-74: Moderate confidence, only if RR >= 2.5
- 50-59: Weak confidence, avoid
- < 50: No confidence, NO TRADE

=== RESPONSE FORMAT ===

OUTPUT HARUS EXACT JSON FORMAT (tanpa markdown, tanpa preamble):
{
  "symbol": "XAUUSD",
  "decision": "BUY|SELL|NO TRADE",
  "confidence": (0-100 integer),
  "entry": (float dengan 2 desimal),
  "stop_loss": (float dengan 2 desimal),
  "take_profit": (float dengan 2 desimal),
  "risk_reward": (float dengan 2 desimal),
  "risk_amount_pips": (integer pips),
  "reason": "(string max 200 chars)",
  "technical_setup": "(string max 300 chars describing setup)",
  "entry_timeframe": "M15|H1",
  "news_impact": "BULLISH|BEARISH|NEUTRAL",
  "news_summary": "(string max 200 chars)",
  "session_info": "ASIA|LONDON_EARLY|LONDON_NY|NY",
  "h4_h1_alignment": "STRONG|MODERATE|WEAK",
  "trend_direction": "UP|DOWN|CONSOLIDATION"
}

CRITICAL RULES:
1. Decision harus BUY, SELL, atau NO TRADE (tidak ada lagi)
2. Confidence harus angka 0-100 (bukan text)
3. Entry/SL/TP harus valid price (tidak boleh negative atau 0)
4. Risk/Reward = |TP - Entry| / |Entry - SL|
5. Jika Risk/Reward < 1.5, decision harus NO TRADE
6. Jika Confidence < 60, decision harus NO TRADE
7. JSON HARUS valid dan parseable

=== DECISION LOGIC ===

Return BUY jika:
- H4 uptrend (EMA50 > EMA200)
- H1 uptrend (EMA50 > EMA200)
- M15 provides entry opportunity
- Risk/Reward >= 2.0
- Confidence >= 70
- No high-impact news dalam 2 jam
- Session quality: GOOD atau EXCELLENT

Return SELL jika:
- H4 downtrend (EMA50 < EMA200)
- H1 downtrend (EMA50 < EMA200)
- M15 provides entry opportunity
- Risk/Reward >= 2.0
- Confidence >= 70
- No high-impact news dalam 2 jam
- Session quality: GOOD atau EXCELLENT

Return NO TRADE jika:
- H4 dan H1 tidak searah (mixed signals)
- Risk/Reward < 2.0
- Confidence < 70
- High-impact news dalam 2 jam
- Oversold/Overbought tanpa confirmation
- Consolidation (EMA terlalu dekat)
- Session quality: POOR
- Cannot place valid SL

=== EXTRA CONTEXT ===

Current analysis timestamp: {current_time}
Market session: {session}
Recent economic events: {news_summary}
Volatility assessment: {volatility_level}

Provide clear, professional analysis focused on probability of success.
Prioritize risk management over potential profits.
When uncertain, choose NO TRADE over false signal.
```

---

## BAGIAN 2: PROMPT VARIATIONS & USE CASES

### Variant A: Conservative Trading (Lower Risk, Lower Reward)

```javascript
// Use this for accounts < $5,000 atau risk-averse traders
const conservativePrompt = `
... [use Base Prompt section 1-5] ...

=== CONSERVATIVE MODE OVERRIDES ===

Confidence Threshold: 80 (instead of 70)
Risk/Reward Minimum: 1:2.5 (instead of 1:2)
Max Risk per Trade: 1% (instead of 2%)
News Safety: Avoid 3 hours before/after HIGH news
Session Quality Required: EXCELLENT only
RSI Extreme Buffer: Avoid if RSI > 75 atau < 25

Return NO TRADE lebih sering.
Return BUY/SELL hanya dengan highest confidence.
`;
```

### Variant B: Aggressive Trading (Higher Risk, Higher Reward)

```javascript
// Use for experienced traders dengan risk appetite tinggi
const aggressivePrompt = `
... [use Base Prompt section 1-5] ...

=== AGGRESSIVE MODE OVERRIDES ===

Confidence Threshold: 65 (instead of 70)
Risk/Reward Minimum: 1:1.5 (instead of 1:2)
Max Risk per Trade: 3% (instead of 2%)
News Safety: Avoid hanya 1 jam sebelum HIGH news
Session Quality Required: GOOD atau lebih
Can take trades pada RSI extreme jika alignment strong

Return BUY/SELL lebih sering.
Reward targeting: Use 1:3 atau 1:4 ratio.
`;
```

### Variant C: Scalping Mode (Very High Frequency)

```javascript
// For scalping 5-15 minute signals pada M15
const scalpingPrompt = `
... [use Base Prompt section 1-5] ...

=== SCALPING MODE ===

TimeFrame: Focus HANYA pada M15 dan H1
H4: Gunakan hanya sebagai trend confirmation, bukan entry
Entry Timing: Second candle setelah breakout
Exit Strategy: Take profit quick (20-50 pips)
Risk/Reward: Minimum 1:1.5 (lower requirement due to frequency)
Trade Frequency: Dapat multiple trades per hour
Session: LONDON_EARLY dan LONDON_NY only

Use tighter SL (ATR * 0.7 instead of 1.0)
Use smaller TP target (1:1.5 ratio instead of 1:3)
`;
```

---

## BAGIAN 3: PROMPT TESTING & OPTIMIZATION

### Test Case 1: Strong Uptrend (Expected: BUY)

```json
{
  "test_name": "Strong Uptrend - H4 UP, H1 UP, M15 UP",
  "h4_ema50": 2445.30,
  "h4_ema200": 2440.15,
  "h4_rsi14": 65.32,
  "current_price": 2450.75,
  
  "h1_ema50": 2449.80,
  "h1_ema200": 2444.20,
  "h1_rsi14": 72.15,
  
  "m15_ema50": 2450.45,
  "m15_ema200": 2447.90,
  "m15_rsi14": 68.45,
  
  "news_impact": "NEUTRAL",
  "expected_decision": "BUY",
  "expected_confidence": "75-85"
}
```

Expected Output:
```json
{
  "decision": "BUY",
  "confidence": 78,
  "entry": 2451.20,
  "stop_loss": 2448.40,
  "take_profit": 2457.80,
  "risk_reward": 2.47
}
```

### Test Case 2: Mixed Signal (Expected: NO TRADE)

```json
{
  "test_name": "Mixed Signal - H4 UP but H1 DOWN",
  "h4_ema50": 2445.30,
  "h4_ema200": 2440.15,
  "h4_trend": "UP",
  
  "h1_ema50": 2444.20,
  "h1_ema200": 2449.80,
  "h1_trend": "DOWN",
  
  "expected_decision": "NO TRADE",
  "reason": "H4 dan H1 tidak aligned"
}
```

Expected Output:
```json
{
  "decision": "NO TRADE",
  "confidence": 35,
  "reason": "H4 uptrend tidak confirmed oleh H1, mixed signals"
}
```

### Test Case 3: Strong News (Expected: NO TRADE or Caution)

```json
{
  "test_name": "High Impact News Soon",
  "h4_trend": "UP",
  "h1_trend": "UP",
  "m15_trend": "UP",
  "h4_ema50": 2445.30,
  "h4_ema200": 2440.15,
  
  "economic_news": [
    {
      "title": "US Non-Farm Payroll",
      "impact": "HIGH",
      "timestamp_minutes_until": 45
    }
  ],
  
  "expected_decision": "NO TRADE",
  "reason": "High-impact news dalam 1 jam"
}
```

Expected Output:
```json
{
  "decision": "NO TRADE",
  "confidence": 20,
  "reason": "High-impact NFP news dalam 45 menit, tunggu sampai setelah release"
}
```

---

## BAGIAN 4: XAUUSD-SPECIFIC TRADING TIPS

### Tip 1: The USD Strength Pattern
```
Pattern Recognition:
- Ketika US economic data kuat (NFP > forecast)
- DXY index naik
- Gold biasanya turun 30-100 pips

Setup:
1. Wait untuk US data release
2. Monitor DXY reaction (naik = bearish gold)
3. Setup SELL pada pullback
4. Entry: 30 menit setelah release
5. TP: support level -20 pips

Success Rate: ~70% jika sentiment clear
Best Session: NY (13:00-21:00 UTC)
```

### Tip 2: The Inflation Fear Trade
```
Ketika inflation data tinggi:
- Central banks unlikely to cut rates
- Or hawkish tone from Fed
- But market already priced in?

Setup:
1. Check if data beat atau miss forecast
2. Listen untuk Fed guidance
3. Jika dovish surprise = BUY gold
4. Jika hawkish surprise = SELL gold

Watch: CPI release, PPI data, core inflation
Best Pattern: Lower-than-expected inflation = STRONG GOLD BUY
```

### Tip 3: The Geopolitical Risk Trade
```
Ketika ada:
- War/conflict di Middle East
- Political tension
- Brexit-like uncertainty

ALWAYS BULLISH GOLD karena:
- Safe haven flow
- Typically moves 100-300 pips in one direction
- Often breaks out dari consolidation

Setup:
1. Wait untuk risk-off confirmation (equities falling)
2. Gold breaks above daily resistance
3. Buy the break
4. Aggressive targets (+200 pips)

Caution: Can reverse fast jika news calms down
```

### Tip 4: The Fed Decision Trade
```
Before Fed Meeting:
- High uncertainty
- Often consolidating (avoid)

During/After Fed Announcement:
- Look untuk surprise direction
- Hawkish = SELL gold
- Dovish = BUY gold
- Neutral = watch untuk delayed reaction

Pro Tip: Fed press conference sering lebih volatile
Setup satu kali untuk multi-hour hold dari major levels

Example Entries:
- Hawkish Fed: Break of support = deep sell target
- Dovish Fed: Break of resistance = multi-day rally
```

### Tip 5: The VIX Correlation Trade
```
Gold inversely correlates dengan VIX (fear index):
- High VIX (fear) = Strong gold bid
- Low VIX (complacency) = Weak gold selling

Setup:
1. Monitor VIX dari news/economic calendar
2. VIX spike = immediate BUY bias
3. VIX falling = switch to SELL bias

Monitor: /VIX index, equity market direction, credit spreads
```

### Tip 6: Session-Based Patterns
```
ASIA SESSION (00:00-08:00):
- Consolidation usually
- Low volume spikes dapat trigger false breakouts
- Best untuk swing trading, tidak scalping
- Watch: Australia economic data

LONDON EARLY (08:00-12:00):
- Money coming in
- Clear directional trends
- Best liquidity
- Watch: ECB speakers, UK data

LONDON-NY OVERLAP (12:00-17:00):
- Choppy, counter-trend moves common
- Fibonacci levels important
- Watch: Fed speakers, US data

NY SESSION (13:00-21:00):
- Highest volatility
- Strongest trends
- Most predictable
- Watch: NFP, Fed announcements, major US data
```

### Tip 7: The Mean Reversion Trade
```
Ketika Gold oversold (terlalu jauh dari EMA):

Setup:
1. H4 down trend tapi RSI < 30
2. H1 oversold juga
3. M15 mengalami bounce dari low
4. Entry: M15 close above EMA50

Target: EMA200 atau halfway ke EMA50
This works ~65% karena mean reversion dalam trends

Caution: Jangan main ini jika high impact news coming
```

### Tip 8: The Breakout Setup
```
Gold sering consolidate sebelum big move:

Recognition:
- Range-bound untuk beberapa jam
- Volume low
- ATR 14 turun

Setup:
1. Tunggu untuk break diatas/dibawah range
2. Volume confirmation
3. M15 alignment check
4. Entry pada break dengan momentum

Targets: Awal move ini often 100-200 pips

Best Window: 2 jam sebelum major news
Trend following, bukan fading
```

---

## BAGIAN 5: COMMON MISTAKES & FIXES

### Mistake 1: Trading Against Trend
```
Problem: Fading rallies dalam uptrend
Result: Multiple SL hits, bleeding capital

Fix in Prompt:
- Enforce strict H4 trend requirement
- NO TRADE jika EMA50 < EMA200
- Only SELL jika confirmed downtrend
- Add: "Trend is your friend, do not fade major trends"
```

### Mistake 2: Ignoring News
```
Problem: Trading jalan ketika high-impact news
Result: Slippage, wrong direction, blown SL

Fix:
- Add economic calendar check di workflow
- NO TRADE jika HIGH impact news dalam 2 jam
- Add in prompt: "Check economic calendar first"
- Implement hard stop 1 hour sebelum high news
```

### Mistake 3: Bad Risk/Reward
```
Problem: Taking 1:1 atau 1:0.5 trades
Result: Need 70% win rate untuk breakeven

Fix:
- Enforce minimum RR >= 2.0
- Calculate correct TP dari resistance/support
- Add validation di workflow
- Return NO TRADE jika RR < 2
```

### Mistake 4: Over-Leverage
```
Problem: Trading 1 lot pada micro account
Result: One bad trade wipes entire account

Fix:
- Implement position sizing formula
- Max risk = 2% per trade
- Calculate lot size dari account size
- Alert jika position size too large
```

### Mistake 5: No Plan Before Entry
```
Problem: Entry tapi don't know where SL/TP
Result: Emotional decision-making, no discipline

Fix:
- Require full setup (entry, SL, TP) sebelum execute
- Validation node checks semua parameters
- Cannot execute jika SL atau TP invalid
- Telegram alert dengan full trade plan
```

---

## BAGIAN 6: ADVANCED GEMINI PROMPTING TECHNIQUES

### Technique 1: Chain of Thought Prompting
```
Instead of direct decision, ask AI untuk think step-by-step:

"Let's analyze XAUUSD step by step:

Step 1: What is the H4 trend?
- EMA50 vs EMA200: ...
- Result: ...

Step 2: Does H1 confirm H4 trend?
- H1 EMA50 vs EMA200: ...
- H1 RSI: ...
- Result: ...

Step 3: What does M15 show for entry?
- M15 structure: ...
- Entry level: ...

Step 4: Calculate risk/reward
- Entry: ... SL: ... TP: ...
- RR = ...

Step 5: What about news/sentiment?
- Recent news: ...
- Impact: ...

FINAL DECISION: Based on above analysis..."

Benefit: More transparent, easier to debug jika salah
```

### Technique 2: Few-Shot Examples
```
Include contoh di prompt:

"Here are examples of good trading signals:

EXAMPLE 1 - GOOD BUY SIGNAL:
- H4: EMA50 (2445) > EMA200 (2440) ✓
- H1: EMA50 (2449) > EMA200 (2444) ✓
- M15: Close above EMA50 ✓
- RR: 2.47 ✓
- News: Neutral ✓
Decision: BUY with 78% confidence

EXAMPLE 2 - BAD SIGNAL (NO TRADE):
- H4: EMA50 > EMA200 (uptrend)
- H1: EMA50 < EMA200 (downtrend) ✗ CONFLICT
- RSI: Both overbought
Decision: NO TRADE - mixed signals

Now analyze current data:"

Benefit: Constrains output, fewer hallucinations
```

### Technique 3: Conditional Logic Prompting
```
"Before you decide:

IF H4 and H1 NOT aligned THEN
  → Output: NO TRADE
  → Stop analysis here
  → No further evaluation

ELSE IF High-Impact News within 2 hours THEN
  → Output: NO TRADE
  → Risk too high

ELSE IF Risk/Reward < 2.0 THEN
  → Output: NO TRADE
  → Insufficient reward

ELSE
  → Proceed dengan normal analysis
  → Evaluate confidence
  → Output BUY, SELL, atau NO TRADE"

Benefit: Gatekeeping reduces false signals
```

### Technique 4: Reverse Analysis Prompting
```
"Check your decision by working backwards:

1. You suggested: [DECISION]
2. What if you're wrong? What evidence would prove it?
3. Is there any price level that would invalidate this?
4. What's the contrarian view?
5. Given those concerns, revise confidence score"

Benefit: Catches overconfidence bias
```

---

## BAGIAN 7: PROMPT MAINTENANCE & ITERATION

### Weekly Prompt Review Checklist:
```
[ ] Check win rate trending
[ ] Analyze false signals untuk patterns
[ ] Review news sensitivity (too strict? too loose?)
[ ] Check timeframe alignment accuracy
[ ] Verify confidence score calibration
[ ] Test prompt dengan historical data samples
[ ] Get feedback dari traders jika manual
[ ] Document any learnings
[ ] Plan improvements untuk next iteration
```

### Quarterly Prompt Update Process:
```
1. Collect all feedback dari trading results
2. Identify: What worked? What didn't?
3. Brainstorm: How dapat we improve?
4. Draft: New prompt version
5. Backtest: Historical data testing
6. Paper trade: 2 weeks with new prompt
7. Compare: Old vs new performance
8. Decision: Keep, improve, or revert
9. Document: Changes made dan why
```

### Prompt Version Control:
```
Keep history dari prompt versions:

v1.0 - Base version (Jan 2024)
  - Win rate: 58%
  - RR achieved: 2.1

v1.1 - Tightened confidence threshold (Jan 15)
  - Win rate: 62%
  - RR achieved: 2.3
  - Change: Min confidence 60 → 70

v1.2 - Added session quality filter (Jan 20)
  - Win rate: 65%
  - RR achieved: 2.4
  - Change: Added session validation

So untuk revert atau improve, dapat reference sebelumnya
```

---

## BAGIAN 8: MONITORING GEMINI PERFORMANCE

### Daily Monitoring:
```
Track untuk setiap signal:
- Decision (BUY/SELL/NO TRADE)
- Confidence score
- Actual entry (jika executed)
- Actual exit (profit atau loss)
- Analysis accuracy

Build metrics:
- Signal accuracy rate
- Confidence vs outcome correlation
- False signal frequency
- No-trade accuracy (correct rejections)
```

### Red Flags untuk Prompt Degradation:
```
Warning Signs:
1. Win rate dropping below 50%
2. False signals increasing
3. Confidence scores inflated (high confidence, low wins)
4. Incorrect trend identification
5. Bad risk/reward calculations
6. Ignoring news impact

Action Items:
- Review recent market changes (new regime?)
- Check jika economic calendar changed
- Revise prompt untuk current conditions
- Backtest dengan recent data
- Consider market-specific adjustments
```

---

**End of Document**

Version: 1.0
Last Updated: January 2024
Next Review: April 2024

Gunakan prompt ini sebagai starting point dan optimize berdasarkan live trading results. Every market dan setiap trader berbeda, jadi customization penting untuk success jangka panjang.
