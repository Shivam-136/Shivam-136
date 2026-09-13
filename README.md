<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Shivam-136 · GitHub Card</title>
<style>
  :root{
    --bg:#0b0f17;
    --panel:#0f141d;
    --border:#1c2430;
    --text:#c7d1de;
    --dim:#5b6675;
    --cyan:#63d4ff;
    --green:#5ee672;
    --yellow:#e6c15e;
    --white:#eef2f7;
  }
  *{box-sizing:border-box;}
  body{
    margin:0;
    background:var(--bg);
    font-family:"SFMono-Regular",Consolas,"Liberation Mono",Menlo,monospace;
    display:flex;
    align-items:center;
    justify-content:center;
    min-height:100vh;
    padding:24px;
  }
  .card{
    width:100%;
    max-width:920px;
    background:var(--panel);
    border:1px solid var(--border);
    border-radius:10px;
    padding:36px 40px;
    display:grid;
    grid-template-columns:220px 1fr;
    gap:40px;
    color:var(--text);
    font-size:14px;
  }
  @media (max-width:640px){
    .card{grid-template-columns:1fr; text-align:center;}
    .avatar-wrap{justify-self:center;}
  }
  .avatar-wrap{
    width:200px;
    height:200px;
    border-radius:6px;
    overflow:hidden;
    border:1px solid var(--border);
    align-self:start;
  }
  .avatar-wrap img{
    width:100%;
    height:100%;
    object-fit:cover;
    filter:grayscale(1) contrast(1.15) brightness(0.9) sepia(0.3) hue-rotate(150deg) saturate(2.2);
    mix-blend-mode:screen;
    display:block;
  }
  .avatar-wrap{
    background:linear-gradient(180deg,#0d1420,#080b11);
  }
  h1{
    font-size:17px;
    color:var(--cyan);
    margin:0 0 18px 0;
    font-weight:600;
  }
  h1 span{color:var(--dim); font-weight:400;}
  .section{margin-bottom:20px;}
  .section-title{
    color:var(--cyan);
    margin-bottom:8px;
  }
  .row{
    display:flex;
    justify-content:space-between;
    gap:12px;
    padding:2px 0;
  }
  .label{color:var(--dim);}
  .value{color:var(--white);}
  .grid2{
    display:grid;
    grid-template-columns:1fr 1fr;
    column-gap:24px;
  }
  .accent-green{color:var(--green);}
  .accent-yellow{color:var(--yellow);}
  a{color:var(--cyan); text-decoration:none;}
  .note{
    margin-top:24px;
    padding-top:14px;
    border-top:1px solid var(--border);
    color:var(--dim);
    font-size:12px;
    line-height:1.6;
  }
</style>
</head>
<body>
  <div class="card">
    <div class="avatar-wrap">
      <img src="https://avatars.githubusercontent.com/u/273769041?v=4" alt="Shivam-136 avatar">
    </div>
    <div>
      <h1>shivam-136<span>@github</span></h1>

      <div class="section">
        <div class="row"><span class="label">Account age:</span><span class="value">~5 months, 8 days</span></div>
        <div class="row"><span class="label">Focus:</span><span class="value">Full-Stack Web Dev — React, Node, Express, MongoDB, Java</span></div>
      </div>

      <div class="section">
        <div class="section-title">Contact</div>
        <div class="row"><span class="label">GitHub:</span><span class="value"><a href="https://github.com/Shivam-136">github.com/Shivam-136</a></span></div>
        <div class="row"><span class="label">Site:</span><span class="value"><a href="https://dev-by-shivam.vercel.app">dev-by-shivam.vercel.app</a></span></div>
      </div>

      <div class="section">
        <div class="section-title">GitHub Stats</div>
        <div class="grid2">
          <div class="row"><span class="label">Repos:</span><span class="value accent-green">15</span></div>
          <div class="row"><span class="label">Followers:</span><span class="value accent-green">2</span></div>
          <div class="row"><span class="label">Following:</span><span class="value accent-green">0</span></div>
          <div class="row"><span class="label">Stars given:</span><span class="value accent-green">1</span></div>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Pinned repos</div>
        <div class="row"><span class="value">Nexa.VoiceAssistant-V1-Frontend</span><span class="accent-yellow">JS</span></div>
        <div class="row"><span class="value">BACKEND</span><span class="accent-yellow">JS</span></div>
        <div class="row"><span class="value">JAVA</span><span class="accent-yellow">Java</span></div>
        <div class="row"><span class="value">CINEVIEW-Frontend</span><span class="accent-yellow">JS</span></div>
      </div>

      <div class="note">
        Note: GitHub's public API is rate-limited right now, so per-repo stats like total stars received, forks, commits, PRs and language %-split couldn't be pulled live — this card shows only what was verifiable (profile + pinned repos). Ask me to refresh later and I'll fill those in.
      </div>
    </div>
  </div>
</body>
</html>
