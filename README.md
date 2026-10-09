<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Teen Mental Health: Screens vs. Real Life</title>
<style>
:root{--bg:#f6f7fb;--card:#fff;--ink:#1f2937;--mut:#6b7280;--line:#e5e7eb;--soft:#eef2ff;--p:#7c3aed;--c:#06b6d4;--k:#ec4899;--a:#f59e0b;--g:#10b981;--i:#6366f1;--navy:#0b1026;--f:system-ui,-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;--m:ui-monospace,SFMono-Regular,Menlo,Consolas,monospace}
@media(prefers-color-scheme:dark){:root{--bg:#0a0f1e;--card:#121a30;--ink:#e5e7eb;--mut:#9ca3af;--line:#25304f;--soft:#1a2342}}
*{box-sizing:border-box}html{scroll-behavior:smooth;scroll-padding-top:70px}
body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.65 var(--f)}
a{color:var(--p)}
nav{position:sticky;top:0;z-index:9;display:flex;gap:4px;overflow-x:auto;padding:10px 20px;background:rgba(11,16,38,.92);backdrop-filter:blur(8px)}
nav b{color:#fff;margin-right:12px;white-space:nowrap;align-self:center}
nav a{color:#cbd5e1;text-decoration:none;font-size:13px;padding:5px 11px;border-radius:99px;white-space:nowrap}
nav a:hover{background:var(--p);color:#fff}
.hero{background:radial-gradient(circle at 20% 20%,#3b1d8f55,transparent 55%),radial-gradient(circle at 85% 70%,#0891b255,transparent 50%),var(--navy);color:#fff;overflow:hidden}
.hero .in{max-width:1100px;margin:auto;padding:56px 24px 40px;display:grid;grid-template-columns:1.1fr 1fr;gap:20px;align-items:center}
.eyebrow{color:var(--c);font-weight:700;letter-spacing:.14em;font-size:12px}
h1{font-size:clamp(38px,6vw,64px);line-height:1.04;margin:10px 0}
h1 span{background:linear-gradient(90deg,var(--k),var(--a));-webkit-background-clip:text;background-clip:text;color:transparent}
.lead{color:#cbd5e1;max-width:520px}
.tags{display:flex;flex-wrap:wrap;gap:8px;margin-top:18px}
.tags i{font-style:normal;font-size:12px;font-weight:600;padding:4px 12px;border-radius:99px;border:1px solid #ffffff33;background:#ffffff14}
.scene{perspective:1000px;height:380px;display:grid;place-items:center}
.tower{position:relative;width:200px;height:200px;transform-style:preserve-3d;transform:rotateX(62deg) rotateZ(-35deg);animation:spin 22s linear infinite}
@keyframes spin{to{transform:rotateX(62deg) rotateZ(325deg)}}
.slab{position:absolute;inset:0;border-radius:14px;border:1px solid #ffffff80;background:var(--col);opacity:.9;box-shadow:0 0 34px var(--col);transform:translateZ(calc(var(--n)*46px - 92px));animation:fl 4s ease-in-out infinite;animation-delay:calc(var(--n)*-.7s);transition:filter .3s}
@keyframes fl{50%{transform:translateZ(calc(var(--n)*46px - 78px))}}
.slab.on{filter:brightness(1.5)}
.legend{list-style:none;margin:0;padding:0;position:absolute;right:0;font-size:13px}
.hero .wrap{position:relative}
.layers{display:flex;flex-direction:column;gap:6px;margin-top:14px}
.layers button{all:unset;cursor:pointer;display:flex;align-items:center;gap:10px;font-size:13px;color:#e2e8f0;padding:5px 10px;border-radius:8px;border:1px solid transparent}
.layers button:hover,.layers button.on{background:#ffffff14;border-color:#ffffff30}
.layers s{width:12px;height:12px;border-radius:3px;background:var(--col)}
main{max-width:1000px;margin:auto;padding:10px 24px 60px}
section{margin-top:56px}
.rv{opacity:0;transform:translateY(24px);transition:.7s}.rv.in{opacity:1;transform:none}
h2{font-size:28px;margin:0 0 6px;display:flex;align-items:center;gap:12px}
h2 em{font-style:normal;font-size:13px;color:#fff;background:linear-gradient(135deg,var(--p),var(--k));padding:3px 10px;border-radius:8px}
h3{font-size:17px;color:var(--p);margin:22px 0 6px}
.card{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:22px;box-shadow:0 6px 24px #0000000d}
.note{border-left:4px solid var(--a);background:#f59e0b1c;padding:12px 16px;border-radius:0 10px 10px 0;margin:16px 0}
.help{border-color:var(--g);background:#10b9811c}
.grid{display:grid;gap:16px}.g3{grid-template-columns:repeat(auto-fit,minmax(250px,1fr))}.g2{grid-template-columns:repeat(auto-fit,minmax(300px,1fr))}
.path{display:block;text-decoration:none;color:inherit;transition:.25s}.path:hover{transform:translateY(-4px) rotateX(6deg);border-color:var(--p)}
.path b{display:block;color:var(--p)}
.flow{counter-reset:s;display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:18px;perspective:900px}
.step{position:relative;color:#fff;border-radius:14px;padding:18px;background:var(--col);box-shadow:6px 7px 0 #00000040;transition:.3s}
.step:hover{transform:rotateX(8deg) rotateY(-6deg) translateY(-4px)}
.step:before{counter-increment:s;content:counter(s);display:inline-grid;place-items:center;width:28px;height:28px;border-radius:50%;background:#fff;color:#111;font-weight:800;margin-right:8px}
.step b{font-size:17px}.step p{margin:8px 0 0;font-size:14px;opacity:.95}
.tw{overflow-x:auto;margin:14px 0;border:1px solid var(--line);border-radius:12px}
table{border-collapse:collapse;width:100%;font-size:14px;background:var(--card)}
th{background:var(--p);color:#fff;text-align:left;padding:10px 14px}td{padding:10px 14px;border-top:1px solid var(--line);vertical-align:top}
tr:nth-child(even) td{background:var(--soft)}td:first-child{font-weight:600}
.bars{display:flex;align-items:flex-end;justify-content:space-around;gap:10px;height:260px;padding:30px 10px 0;background:var(--navy);border-radius:16px;color:#fff;position:relative}
.bw{display:flex;flex-direction:column;align-items:center;justify-content:flex-end;height:100%;font-size:12px;text-align:center;flex:1}
.bar{position:relative;width:52px;height:0;border-radius:4px 4px 0 0;background:linear-gradient(var(--col),#0006);box-shadow:9px 0 0 #00000055;transition:height 1.3s cubic-bezier(.2,.8,.2,1)}
.bar:before{content:"";position:absolute;left:0;top:-9px;width:100%;height:9px;background:var(--col);filter:brightness(1.4);transform:skewX(-45deg);transform-origin:bottom left}
.bw b{font-size:14px;margin-bottom:12px}.bw span{margin-top:8px;color:#cbd5e1;min-height:32px}
.cap{position:absolute;top:10px;left:16px;font-size:11px;color:var(--c);font-weight:700;letter-spacing:.08em}
svg text{font:600 13px var(--f);fill:#fff}
.ring{stroke-dasharray:6 8;animation:dash 2s linear infinite}@keyframes dash{to{stroke-dashoffset:-28}}
ul.ck{padding-left:20px}ul.ck li{margin:4px 0}
pre{position:relative;background:#0f172a;color:#e2e8f0;padding:18px 18px 18px 20px;border-radius:12px;border-left:4px solid var(--p);overflow-x:auto;font:13px/1.55 var(--m);margin:12px 0}
pre button{position:absolute;top:8px;right:8px;font-size:11px;background:#ffffff1f;color:#fff;border:0;border-radius:6px;padding:3px 9px;cursor:pointer}
.q{display:block;padding:7px 10px;border-radius:8px;cursor:pointer}.q:hover{background:var(--soft)}.q input{accent-color:var(--p);margin-right:10px}
.pb{height:12px;background:var(--line);border-radius:9px;overflow:hidden;margin:10px 0}.pb i{display:block;height:100%;width:0;background:linear-gradient(90deg,var(--c),var(--g));transition:width .5s}
footer{text-align:center;color:var(--mut);padding:30px;border-top:1px solid var(--line)}
@media(max-width:800px){.hero .in{grid-template-columns:1fr}.scene{height:300px}}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}.rv{opacity:1;transform:none}}
@media print{nav,.scene{display:none}.rv{opacity:1;transform:none}}
</style>
</head>
<body>
<nav id="top"><b>Teen Mental Health</b><a href="#over">Overview</a><a href="#why">Why</a><a href="#arch">Architecture</a><a href="#model">3D Model</a><a href="#day">Day</a><a href="#loop">Loop</a><a href="#habits">Habits</a><a href="#signs">Signs</a><a href="#code">Analysis</a><a href="#quest">Quests</a><a href="#help">Help</a></nav>

<header class="hero"><div class="in">
 <div>
  <div class="eyebrow">README &nbsp;|&nbsp; DATA + AWARENESS PROJECT</div>
  <h1>Teen Mental Health<br><span>Screens vs. Real Life</span></h1>
  <p class="lead">How today's teens spend their time, which habits quietly hurt them, and how to bring balance back, explored through data and design.</p>
  <div class="tags"><i>Python</i><i>Pandas</i><i>EDA</i><i>Visualization</i><i>Awareness</i></div>
  <div class="layers" id="layers"></div>
 </div>
 <div class="scene" aria-label="Animated 3D model of five wellbeing layers"><div class="tower" id="tower"></div></div>
</div></header>

<main>
<section id="over" class="rv"><h2><em>01</em>Overview</h2>
 <p>This project asks one question: <b>where does a teenager's time actually go, and what happens when screen life grows bigger than real life?</b> It combines exploratory data analysis with clear visual storytelling so a teen, a parent and a teacher can all read the results.</p>
 <div class="grid g3">
  <div class="card"><b>Goal</b><br>Understand daily time use, screen habits, sleep and mood in teens.</div>
  <div class="card"><b>Method</b><br>Clean the data, explore it with plots, build features, look for patterns.</div>
  <div class="card"><b>Output</b><br>Insights, a habit toolkit and this visual guide.</div>
 </div>
 <h3>Choose your path</h3>
 <div class="grid g3">
  <a class="card path" href="#quest"><b>I am a teen</b>Real-life quests: small, doable habit challenges.</a>
  <a class="card path" href="#signs"><b>I am a parent / teacher</b>Warning signs and how to open a talk.</a>
  <a class="card path" href="#code"><b>I am a data learner</b>Questions, code and plots to build.</a>
 </div>
</section>

<section id="why" class="rv"><h2><em>02</em>Why It Matters</h2>
 <p>Social media brings connection, creativity and community. It also puts comparison, pressure and endless content in a teen's pocket, day and night. Research links heavy, late-night or purely passive use with poorer sleep, lower mood and more anxiety in <i>some</i> teens; effects differ from person to person. Screens are not the enemy, imbalance is the risk.</p>
 <ul class="ck"><li>Online time often <b>replaces</b> sleep, movement, homework and face-to-face talk.</li><li>Likes, streaks and follower counts can quietly become a measure of self-worth.</li><li>Cyberbullying and FOMO follow teens home; there is no off switch.</li><li>Real-life skills, like handling boredom or conflict, get less practice.</li></ul>
 <div class="note"><b>Note:</b> this project describes patterns and builds awareness. It does not diagnose anyone. If a teen seems to be struggling, a real conversation and a professional matter more than any chart.</div>
</section>

<section id="arch" class="rv"><h2><em>03</em>Project Architecture</h2>
 <p>One pipeline, from raw answers to awareness. Hover a card to tilt it.</p>
 <div class="flow">
  <div class="step" style="--col:#7c3aed"><b>Data Collection</b><p>Surveys, screen-time logs, sleep and mood self-reports. <small>CSV, forms</small></p></div>
  <div class="step" style="--col:#0891b2"><b>Cleaning</b><p>Missing values, duplicates, impossible hours (&gt;24 h), wrong types. <small>Pandas, NumPy</small></p></div>
  <div class="step" style="--col:#059669"><b>EDA</b><p>Histograms, count plots, boxplots, correlation heatmap. <small>Matplotlib, Seaborn</small></p></div>
  <div class="step" style="--col:#d97706"><b>Feature Engineering</b><p>Digital-to-real ratio, night-use flag, sleep debt. <small>Pandas</small></p></div>
  <div class="step" style="--col:#db2777"><b>Modeling &amp; Insight</b><p>Risk groups, patterns, what predicts low mood. <small>SciPy, scikit-learn</small></p></div>
  <div class="step" style="--col:#4f46e5"><b>Awareness &amp; Action</b><p>Dashboards, guidance and a healthy-habit toolkit. <small>Docs, dashboards</small></p></div>
 </div>
</section>

<section id="model" class="rv"><h2><em>04</em>3D Conceptual Model</h2>
 <p>Wellbeing is a <b>tower of five floating layers</b>. Sleep and real bonds are the foundation; social media and comparison sit on top. When the top grows heavy, the tower wobbles, and sleep and connection slip first. Hover the layers in the header to light up the model.</p>
 <div class="tw"><table><tr><th>Layer</th><th>Healthy state</th><th>Under strain</th></tr>
 <tr><td>Sleep &amp; Body</td><td>8 to 10 hours, regular meals, some movement</td><td>Late nights, skipped meals, tired all day</td></tr>
 <tr><td>Real-Life Bonds</td><td>Talks with family, time with friends in person</td><td>Meals with phones, fewer plans made</td></tr>
 <tr><td>Mood &amp; Emotions</td><td>Can name feelings, bounces back from bad days</td><td>Irritable, flat, anxious, withdrawn</td></tr>
 <tr><td>Social Media Life</td><td>Creating, chatting, learning, in moderation</td><td>Doomscrolling, passive checking for hours</td></tr>
 <tr><td>Pressure &amp; Comparison</td><td>Aware that feeds are highlight reels</td><td>Self-worth tied to likes and filters</td></tr></table></div>
</section>

<section id="day" class="rv"><h2><em>05</em>Where the Day Goes</h2>
 <p>A day has 24 hours. Every hour given to the feed is taken from something else, usually sleep first. Pink and purple bars are digital life; green is time with real people.</p>
 <div class="bars" id="bars"><div class="cap">A DAY IN 24 HOURS | ILLUSTRATIVE SAMPLE</div></div>
 <div class="note"><b>Read it like this:</b> in this sample, social media plus games and OTT (6 h) is four times the time with friends in person (1.5 h). That ratio is the <code>digital_real_ratio</code> feature. Replace the sample values with your dataset.</div>
</section>

<section id="loop" class="rv"><h2><em>06</em>The Scroll Loop</h2>
 <p>Harm rarely comes from one big moment. It builds as a loop that feeds itself: a tired, low teen reaches for the phone for comfort, and the phone deepens the tiredness.</p>
 <div class="card" style="background:var(--navy)"><svg viewBox="0 0 560 300" width="100%" role="img" aria-label="Loop: late-night scrolling, less sleep, low mood, scroll to feel better">
  <defs><marker id="ar" viewBox="0 0 10 10" refX="9" refY="5" markerWidth="7" markerHeight="7" orient="auto"><path d="M0 0L10 5L0 10z" fill="#cbd5e1"/></marker></defs>
  <circle cx="280" cy="150" r="52" fill="#3b1d8f"/><text x="280" y="147" text-anchor="middle">THE SCROLL</text><text x="280" y="165" text-anchor="middle">LOOP</text>
  <g stroke="#cbd5e1" stroke-width="2" fill="none" marker-end="url(#ar)" class="ring"><path d="M350 48 L452 108"/><path d="M452 192 L350 252"/><path d="M210 252 L108 192"/><path d="M108 108 L210 48"/></g>
  <rect x="190" y="14" width="180" height="40" rx="10" fill="#ec4899"/><text x="280" y="39" text-anchor="middle">1. Late-night scrolling</text>
  <rect x="380" y="130" width="170" height="40" rx="10" fill="#6366f1"/><text x="465" y="155" text-anchor="middle">2. Less, lighter sleep</text>
  <rect x="190" y="246" width="180" height="40" rx="10" fill="#7c3aed"/><text x="280" y="271" text-anchor="middle">3. Low mood, irritability</text>
  <rect x="10" y="130" width="170" height="40" rx="10" fill="#f59e0b"/><text x="95" y="155" text-anchor="middle" style="fill:#111">4. Scroll to feel better</text></svg></div>
 <h3>Where to break the loop</h3>
 <ul class="ck"><li><b>Charging spot outside the bedroom</b> removes the late-night trigger.</li><li><b>A fixed wake-up time</b> protects sleep even after a late night.</li><li><b>A real-life comfort</b> (walk, music, call a friend) replaces the scroll.</li><li><b>Talk to someone</b> when the loop runs for weeks. It is not a willpower problem.</li></ul>
</section>

<section id="habits" class="rv"><h2><em>07</em>Habits and Swaps</h2>
 <div class="tw"><table><tr><th>Harmful habit</th><th>What it does</th><th>Healthier swap</th></tr>
 <tr><td>Scrolling in bed</td><td>Delays sleep, fragments rest</td><td>Phone charges across the room; use an alarm clock</td></tr>
 <tr><td>Doomscrolling</td><td>Raises worry, drains energy</td><td>Set a timer; pick a feed with a clear end</td></tr>
 <tr><td>Comparing with filtered lives</td><td>Lowers self-image, fuels envy</td><td>Follow people who teach or inspire; mute the rest</td></tr>
 <tr><td>Replacing meals and movement</td><td>Low energy, low mood</td><td>Phone-free meals; 20 minutes outside daily</td></tr>
 <tr><td>Chasing likes and streaks</td><td>Approval becomes the goal</td><td>Post for fun, hide counts, track real wins</td></tr>
 <tr><td>Hiding cyberbullying</td><td>Isolation, fear, shame</td><td>Screenshot, block, tell a trusted adult</td></tr>
 <tr><td>Gaming through the night</td><td>Sleep debt, falling grades</td><td>Agreed stop time; weekends get more room</td></tr></table></div>
</section>

<section id="signs" class="rv"><h2><em>08</em>Warning Signs</h2>
 <p>No single sign means something is wrong. Look for <b>changes lasting two weeks or more</b>, or several together.</p>
 <div class="grid g2">
  <div class="card"><h3 style="margin-top:0">What to notice</h3><ul class="ck"><li>Sleeping much more or much less; constant tiredness.</li><li>Pulling away from friends, family or loved hobbies.</li><li>Mood swings, anger, tears, or a flat, empty tone.</li><li>Falling grades, skipped school, trouble focusing.</li><li>Distress without the phone, or secrecy about online life.</li><li>Talk of feeling worthless, hopeless or like a burden.</li></ul></div>
  <div class="card"><h3 style="margin-top:0">How to start the talk</h3><ul class="ck"><li>Pick a calm moment, not an argument. Walks and car rides work well.</li><li>Say what you see, without blame: <i>"You seem more tired lately. I am here if you want to talk."</i></li><li>Listen first. Do not rush to fix, lecture or take the phone away.</li><li>Ask what their online life feels like, the good and the hard.</li><li>Offer to find support together, starting with a school counselor or doctor.</li></ul></div>
 </div>
</section>

<section id="code" class="rv"><h2><em>09</em>Analysis Plan</h2>
 <h3>Questions the data should answer</h3>
 <ul class="ck"><li>How many hours a day do teens spend on social media, and how does it vary by age and gender?</li><li>Is more screen time linked to less sleep and lower mood?</li><li>Does night-time use matter more than total hours?</li><li>Do teens with more in-person time report better mood?</li><li>Which groups look most at risk, and what do their habits share?</li></ul>
<pre>import pandas as pd, numpy as np
import seaborn as sns, matplotlib.pyplot as plt

df = pd.read_csv("data/teen_mental_health.csv")
df.info(); print(df.isnull().sum())

# --- clean
df = df.drop_duplicates()
df = df[df["social_media_hrs"].between(0, 24)]
df["sleep_hrs"] = df["sleep_hrs"].fillna(df["sleep_hrs"].median())

# --- features
df["digital_hrs"] = df["social_media_hrs"] + df["gaming_hrs"]
df["digital_real_ratio"] = df["digital_hrs"] / (df["in_person_hrs"] + 1)
df["sleep_debt"] = (8 - df["sleep_hrs"]).clip(lower=0)
df["night_user"] = (df["last_screen_hour"] >= 23).astype(int)

# --- explore
sns.histplot(df["social_media_hrs"], kde=True)
sns.boxplot(x="night_user", y="mood_score", data=df)
sns.heatmap(df.corr(numeric_only=True), annot=True, cmap="coolwarm")
plt.show()</pre>
 <h3>Repo and setup</h3>
<pre>teen-mental-health/
 |-- data/        teen_mental_health.csv, cleaned_data.csv
 |-- notebooks/   01_eda_cleaning_analysis.ipynb
 |-- assets/      charts and README exports
 |-- requirements.txt
 '-- README.md

git clone https://github.com/&lt;you&gt;/teen-mental-health.git
cd teen-mental-health
python -m venv venv &amp;&amp; source venv/bin/activate
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook</pre>
</section>

<section id="quest" class="rv"><h2><em>10</em>Real-Life Quests</h2>
 <p>Tick a quest when you finish it. Small wins build the bottom layers of the tower.</p>
 <div class="card" id="quests">
  <b>Level 1: Sleep</b><label class="q"><input type="checkbox">Charge the phone outside the bedroom tonight</label><label class="q"><input type="checkbox">No screens for the last 30 minutes before sleep</label><label class="q"><input type="checkbox">Wake up at the same time for 5 days</label>
  <b>Level 2: Connection</b><label class="q"><input type="checkbox">One phone-free meal with family</label><label class="q"><input type="checkbox">Meet or call a friend instead of texting</label><label class="q"><input type="checkbox">Ask someone how they really are, and listen</label>
  <b>Level 3: Body and mind</b><label class="q"><input type="checkbox">20 minutes outside, no phone in hand</label><label class="q"><input type="checkbox">Try a hobby with no screen (draw, play, cook, build)</label><label class="q"><input type="checkbox">Write down 3 good things from the day</label>
  <b>Level 4: Feed cleanup</b><label class="q"><input type="checkbox">Mute or unfollow 5 accounts that make you feel worse</label><label class="q"><input type="checkbox">Turn off non-essential notifications</label><label class="q"><input type="checkbox">Set a daily limit and keep it for a week</label>
  <b>Boss level</b><label class="q"><input type="checkbox">Tell a trusted person one thing that has been weighing on you</label>
  <div class="pb"><i id="pbar"></i></div><div id="score"><b>0 / 13</b>: just starting. The goal is progress, not perfection.</div>
 </div>
</section>

<section id="help" class="rv"><h2><em>11</em>Getting Help</h2>
 <div class="note help"><b>You are not alone, and asking for help is a sign of strength.</b> If you or a teen you know feels hopeless, unsafe or thinks about self-harm, talk to a trusted adult today, such as a parent, school counselor or doctor. In India, <b>Tele-MANAS (14416)</b> offers free mental health support, and <b>112</b> is the emergency number if someone is in immediate danger. Elsewhere, please use your local helpline or emergency number.</div>
 <div class="grid g2"><div class="card"><h3 style="margin-top:0">Ethics checklist for the data work</h3><ul class="ck"><li>Collect data only with consent, from teens and guardians where required.</li><li>Anonymize everything: no names, schools or contact details.</li><li>Report patterns; never label or diagnose individuals.</li><li>Show uncertainty: correlation is not causation.</li></ul></div>
 <div class="card"><h3 style="margin-top:0">Roadmap</h3><ul class="ck" style="list-style:none;padding:0"><li>&#9745; Define the questions and architecture</li><li>&#9745; Design the 3D model and visual guide</li><li>&#9744; Collect a dataset and run the EDA notebook</li><li>&#9744; Add a Streamlit or Plotly dashboard</li><li>&#9744; Share a one-page parent and teacher guide</li></ul></div></div>
</section>
</main>
<footer>Built with Python, curiosity and care. Real life is the main feed. &nbsp;<a href="#top">Back to top</a></footer>

<script>
const L=[["Sleep & Body","#6366f1"],["Real-Life Bonds","#10b981"],["Mood & Emotions","#7c3aed"],["Social Media Life","#ec4899"],["Pressure & Comparison","#f59e0b"]];
const tower=document.getElementById("tower"),lay=document.getElementById("layers");
L.forEach(([n,c],i)=>{const s=document.createElement("div");s.className="slab";s.style.cssText=`--n:${i};--col:${c}`;tower.appendChild(s);
 const b=document.createElement("button");b.innerHTML=`<s style="--col:${c}"></s>${n}`;
 const on=v=>{s.classList.toggle("on",v);b.classList.toggle("on",v)};
 b.onmouseenter=b.onfocus=()=>on(1);b.onmouseleave=b.onblur=()=>on(0);lay.appendChild(b)});
const D=[["Sleep",7,"#6366f1"],["School",6,"#06b6d4"],["Social media",3.5,"#ec4899"],["Games / OTT",2.5,"#a855f7"],["In-person friends",1.5,"#10b981"],["Study, play, other",3.5,"#f59e0b"]];
const bars=document.getElementById("bars");
D.forEach(([n,h,c])=>{bars.insertAdjacentHTML("beforeend",`<div class="bw"><b>${h} h</b><div class="bar" data-h="${h*22}" style="--col:${c}"></div><span>${n}</span></div>`)});
const io=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting){e.target.classList.add("in");
 e.target.querySelectorAll(".bar").forEach(b=>b.style.height=b.dataset.h+"px")}}),{threshold:.15});
document.querySelectorAll(".rv").forEach(r=>io.observe(r));
const cb=[...document.querySelectorAll("#quests input")],pb=document.getElementById("pbar"),sc=document.getElementById("score");
cb.forEach(c=>c.onchange=()=>{const n=cb.filter(x=>x.checked).length;pb.style.width=n/13*100+"%";
 sc.innerHTML=`<b>${n} / 13</b>: `+(n<5?"just starting.":n<10?"building momentum.":"balanced and strong.")+" The goal is progress, not perfection."});
document.querySelectorAll("pre").forEach(p=>{const b=document.createElement("button");b.textContent="Copy";
 b.onclick=()=>{navigator.clipboard&&navigator.clipboard.writeText(p.innerText.replace(/Copy$/,"").trim()).then(()=>{b.textContent="Copied";setTimeout(()=>b.textContent="Copy",1400)})};p.appendChild(b)});
</script>
</body>
</html>
