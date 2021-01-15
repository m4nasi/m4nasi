👩‍💻 Manasi | 💻 Web Developer | 🇬🇧 England 

[Instagram](https://www.instagram.com/m4nasi/) • [Twitter](https://twitter.com/m4nasi) 

Hi 👋
- 🔭 I’m currently working from home
- 🌱 I’m currently learning **C# and XAML**
- 💬 Languages: Python, HTML, CSS, C#, XAML
- 😄 Pronouns: she/her
- 👯 I’m looking to collaborate on a potential project
- 📫 How to reach me: [@m4nasi](https://twitter.com/m4nasi) on Twitter
<hr>
<!--<img align="center" src="https://github-readme-stats.vercel.app/api?username=m4nasi&theme=dark&show_icons=true" /> -->
<img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=m4nasi&layout=compact" />
<hr>
Skip to content
Search or jump to…

Pulls
Issues
Marketplace
Explore
 
@m4nasi 
lowlighter
/
lowlighter
1
9
28
Code
Pull requests
Actions
Security
Insights
lowlighter/metrics.classic.svg
@github-actions
github-actions Update metrics.classic.svg - [Skip GitHub Action]
Latest commit ca5ef05 20 minutes ago
 History
 3 contributors
@github-actions@botlighter@lowlighter
749 lines (620 sloc)  66 KB
  
<svg xmlns="http://www.w3.org/2000/svg" width="480" height="214" class="">

  <defs><style/></defs>
  <style>/* SVG global context */
  svg {
    font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji;
    font-size: 14px;
    color: #777777;
  }
/* Headers */
  h1, h2, h3 {
    margin: 8px 0 2px;
    padding: 0;
    color: #0366d6;
    font-weight: normal;
  }
  h1 svg, h2 svg, h3 svg {
    fill: currentColor;
  }
  h1 {
    font-size: 20px;
    font-weight: bold;
  }
  h2 {
    font-size: 16px;
  }
  h3 {
    font-size: 14px;
  }
/* Fields */
  section &gt; .field {
    margin-left: 5px;
    margin-right: 5px;
  }
  .field {
    display: flex;
    align-items: center;
    margin-bottom: 2px;
    white-space: nowrap;
  }
  .field svg {
    margin: 0 8px;
    fill: #959da5;
    flex-shrink: 0;
  }
  .field.error {
    color: #cb2431;
  }
  .field.error svg {
    fill: #cb2431;
  }
/* Displays */
  .row {
    display: flex;
  }
  .row section {
    flex: 1 1 0;
  }
  .column {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .center {
    justify-content: center;
  }
  .horizontal {
    justify-content: space-around;
  }
  .horizontal-wrap {
    flex-wrap: wrap;
  }
  .horizontal .field {
    flex: 1 1 0;
  }
  .no-wrap {
    white-space: nowrap;
  }
  .fill-width {
    width: 100%;
  }
  .margin-bottom {
    margin-bottom: 16px;
  }
/* User avatar */
  .avatar {
    border-radius: 50%;
    margin: 0 6px;
  }
/* Commit calendar */
  .calendar.field {
    margin: 4px 0;
    margin-left: 7px;
  }
  .calendar .day {
    outline: 1px solid rgba(27,31,35,.04);
    outline-offset: -1px;
  }
/* Progress bars */
  svg.bar {
    margin: 4px 0;
  }
/* Language */
  .field.language {
    margin: 0 8px;
    flex-grow: 0;
  }
  .field.language small {
    margin-left: 4px;
    color: #666666;
  }
/* Labels */
  .label {
    background-color: #F1F8FF;
    color: #0366D6;
    padding: 0 10px;
    font-weight: 500;
    line-height: 22px;
    margin: 2px 5px;
    white-space: nowrap;
    border-radius: 32px;
    font-size: 12px;
  }
  .label:hover {
    background-color: #DDEEFF;
    cursor: pointer;
  }
/* Habits */
  .habits {
    margin: 0;
    list-style-type: none;
    padding-left: 37px;
  }
/* Footer */
  footer {
    margin-top: 8px;
    font-size: 10px;
    font-style: italic;
    color: #666666;
    text-align: right;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
  }
/* Speed test categories */
  .categories {
    display: flex;
    align-items: center;
    justify-content: space-around;
    margin-top: 4px;
  }
  .categorie {
    display: flex;
    flex-direction: column;
    align-items: center;
    flex: 1 1 0;
  }
/* Gauges */
  .gauge {
    stroke-linecap: round;
    fill: none;
  }
  .gauge.high {
    color: #18b663;
  }
  .gauge.average {
    color: #fb8c00;
  }
  .gauge.low {
    color: #e53935;
  }
  .gauge-base, .gauge-arc {
    stroke: currentColor;
    stroke-width: 10;
  }
  .gauge-base {
    stroke-opacity: .2;
  }
  .gauge-arc {
    fill: none;
    stroke-dashoffset: 0;
    animation-delay: 250ms;
    animation: animation-gauge 1s ease forwards
  }
  .gauge text {
    fill: currentColor;
    font-size: 40px;
    font-family: monospace;
    text-anchor: middle;
    font-weight: 600;
  }
  .gauge .title {
    font-size: 18px;
    color: #777777;
  }
  @keyframes animation-gauge {
    from {
      stroke-dasharray: 0 329;
    }
  }
  .audits {
    margin-top: 8px;
  }
  .audit.text {
    min-width: 42px;
  }
  .audit svg {
    margin: 0;
  }
  .audit.high {
    fill: #18b663;
  }
  .audit.average {
    fill: #fb8c00;
  }
  .audit.low {
    fill: #e53935;
  }
  .screenshot {
    width: 452px;
    height: 315px;
    margin: 8px 14px 4px;
    border-radius: 5px;
  }
/* Music plugin */
  .tracklist {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin-left: 28px;
    margin-top: 4px;
    width: 100%;
  }
  .track {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 4px;
  }
  .track img {
    margin: 0 10px;
    border-radius: 7px;
  }
  .track .name {
    font-size: 14px;
    line-height: 14px;
  }
  .track .artist {
    font-size: 12px;
    color: #666666;
  }
/* Posts plugin */
  .post {
    align-items: flex-start;
  }
  .post .infos {
    display: flex;
    margin-bottom: 4px;
  }
  .post .infos .title {
    font-size: 14px;
    width: 380px;
    white-space: normal;
    overflow: hidden;
    text-overflow: ellipsis;
    max-height: 40px;;
  }
  .post .infos .date {
    flex-shrink: 0;
    font-size: 12px;
    color: #666666;
    width: 60px;
    padding-top: 1px;
  }
/* Topics */
  .topics {
    display: flex;
    flex-wrap: wrap;
  }
  .topics img {
    border-radius: 5px;
    margin: 4px;
  }
/* Tweets */
  .tweet {
    font-size: 13px;
    margin-top: 6px;
    margin-bottom: 16px;
    margin-left: 18px;
    border-left: 3px solid #777777B2;
    padding-left: 6px;
  }
  .tweet .mention, .tweet .link, .tweet .hashtag {
    color: #0366d6;
    margin: 0 4px;
  }
  .tweet .date {
    margin: 6px 0;
    font-size: 12px;
    color: #666666;
  }
/* Charts and graphs */
  .chart {
    padding: 0 8px;
  }
  .chart-bars {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    width: 100%;
    margin: 8px 0 4px;
    flex-grow: 1;
  }
  .chart-bars .entry {
    flex: 1 1 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    font-size: 10px;
    color: #666666;
  }
  .chart-bars .entry .value {
    font-size: 7px;
  }
  .chart-bars .bar {
    width: 7px;
    background-color: var(--color-calendar-graph-day-bg);
    border: 1px solid var(--color-calendar-graph-day-border);
    border-radius: 5px;
  }
  .chart-bars.horizontal {
    flex-direction: column;
    align-items: space-between;
    height: 100%;
  }
  .chart-bars.horizontal .entry {
    align-items: center;
    flex-direction: row;
    width: 100%;
  }
  .chart-bars.horizontal .entry .name {
    flex-shrink: 0;
    text-align: right;
    min-width: 30%;
  }
  .chart-bars .entry .bottom {
    margin-bottom: -1rem;
    line-height: 1rem;
  }
  .chart-bars.horizontal .bar {
    height: 7px;
    width: auto;
    margin: 0 6px;
  }
/* Repository */
  .repository {
    display: flex;
    flex-direction: column;
    width: 100%;
    margin: 6px 0;
  }
  .repository .name {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 440px;
  }
  .repository .name span:first-child {
    color: #58a6ff;
  }
  .repository .name span:last-child {
    color: #666666;
    font-size: 13px;
  }
  .repository .description {
    display: block;
    width: 440px;
    white-space: normal;
  }
  .repository .description, .repository .infos {
    color: #666666;
    margin-left: 38px;
    font-size: 13px;
  }
  .repository .infos &gt; div {
    display: flex;
    align-items: center;
    margin-right: 16px;
  }
  .repository .infos svg {
    margin: 0;
    margin-right: 4px;
  }
/* Activity */
  .activity {
    margin-bottom: 12px;
  }
  .activity .field {
    width: 100%;
    overflow: hidden;
    text-overflow: ellipsis;
    max-width: 450px;
    white-space: nowrap;
    margin-bottom: 0;
  }
  .activity .repo, .activity .issue, .activity .commit .sha {
    color: #58a6ff;
    margin: 0 4px;
  }
  .activity .code {
    background-color: #7777771F;
    padding: 1px 5px;
    font-size: 80%;
    border-radius: 6px;
    color: #777777;
    font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,monospace;
    margin: 0 4px -3px;
  }
  .activity .bold {
    font-weight: 600;
    margin: 0 4px;
  }
  .activity .details {
    padding-left: 42px;
    display: flex;
    flex-direction: column;
    font-size: 13px;
    color: #666666;
  }
  .activity .details &gt; div {
    display: flex;
    align-items: center;
  }
  .activity .commit .sha {
    font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,monospace;
  }
  .activity .commit .message {
    overflow: hidden;
    text-overflow: ellipsis;
    width: 360px;
    white-space: nowrap;
  }
  .activity .details .comment {
    overflow: hidden;
    text-overflow: ellipsis;
    display: block;
    width: 420px;
    margin-top: 6px;
    border-left: 3px solid #777777B2;
    padding-left: 6px;
    max-height: 38px;
    /* May not work in all browsers */
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }
/* People */
  .people {
    padding: 0 10px;
  }
  .people .avatar {
    margin: 0 2px;
  }
/* Fade animation */
  .af {
    opacity: 0;
    animation: animation-fade 1s ease forwards;
  }
  @keyframes animation-fade {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }
/* Cake day */
  .cakeday, .cakeday svg {
    animation: animation-rainbow 1.2s;
    animation-iteration-count: infinite;
    animation-timing-function: steps(1);
  }
/* Rainbow animation */
  @keyframes animation-rainbow {
    0%, 100%{ color: #7F00FF; fill: #7F00FF; }
    14% { color: #A933FF; fill: #A933FF; }
    29%{ color: #007FFF; fill: #007FFF; }
    43%{ color: #00FF7F; fill: #00FF7F; }
		57%{ color: #FFFF00; fill: #FFFF00; }
		71%{ color: #FF7F00; fill: #FF7F00; }
		86%{ color: #FF0000; fill: #FF0000; }
  }
/* Calendar */
  :root {
    --color-calendar-graph-day-bg: #ebedf0;
    --color-calendar-graph-day-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L1-bg: #9be9a8;
    --color-calendar-graph-day-L2-bg: #40c463;
    --color-calendar-graph-day-L3-bg: #30a14e;
    --color-calendar-graph-day-L4-bg: #216e39;
    --color-calendar-halloween-graph-day-L1-bg: #ffee4a;
    --color-calendar-halloween-graph-day-L2-bg: #ffc501;
    --color-calendar-halloween-graph-day-L3-bg: #fe9600;
    --color-calendar-halloween-graph-day-L4-bg: #03001c;
    --color-calendar-graph-day-L4-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L3-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L2-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L1-border: rgba(27,31,35,0.06);
  }
/* End delimiter */
  #metrics-end {
    width: 100%;
  }
  .no-animations * {
    transition-delay: 0s !important;
    transition-duration: 0s !important;
    animation-delay: -0.0001s !important;
    animation-duration: 0s !important;
    animation-play-state: paused !important;
    caret-color: transparent !important;
  }</style>

  <foreignObject x="0" y="0" width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml" xmlns:xlink="http://www.w3.org/1999/xlink">
      
        
  <section>
    <h1 class="field">
      <img class="avatar" src="data:image/png;base64,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" width="20" height="20" />
      <span>Simon Lecoq</span>
    </h1>
    <div class="row">
      <section>
        <div class="field ">
          
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0zM8 0a8 8 0 100 16A8 8 0 008 0zm.5 4.75a.75.75 0 00-1.5 0v3.5a.75.75 0 00.471.696l2.5 1a.75.75 0 00.557-1.392L8.5 7.742V4.75z"/></svg>
            Joined GitHub 4 years ago
          
        </div>
        <div class="field">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M5.5 3.5a2 2 0 100 4 2 2 0 000-4zM2 5.5a3.5 3.5 0 115.898 2.549 5.507 5.507 0 013.034 4.084.75.75 0 11-1.482.235 4.001 4.001 0 00-7.9 0 .75.75 0 01-1.482-.236A5.507 5.507 0 013.102 8.05 3.49 3.49 0 012 5.5zM11 4a.75.75 0 100 1.5 1.5 1.5 0 01.666 2.844.75.75 0 00-.416.672v.352a.75.75 0 00.574.73c1.2.289 2.162 1.2 2.522 2.372a.75.75 0 101.434-.44 5.01 5.01 0 00-2.56-3.012A3 3 0 0011 4z"/></svg>
          Followed by 81 users
        </div>
        
      </section>
      <section>
        <div class="field calendar">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 210 11" width="210" height="16">
            <g>
              
                <rect class="day" x="0" y="0" width="11" height="11" fill="#40c463" rx="2" ry="2"/>
              
                <rect class="day" x="15" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
              
                <rect class="day" x="30" y="0" width="11" height="11" fill="#40c463" rx="2" ry="2"/>
              
                <rect class="day" x="45" y="0" width="11" height="11" fill="#30a14e" rx="2" ry="2"/>
              
                <rect class="day" x="60" y="0" width="11" height="11" fill="#9be9a8" rx="2" ry="2"/>
              
                <rect class="day" x="75" y="0" width="11" height="11" fill="#30a14e" rx="2" ry="2"/>
              
                <rect class="day" x="90" y="0" width="11" height="11" fill="#9be9a8" rx="2" ry="2"/>
              
                <rect class="day" x="105" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
              
                <rect class="day" x="120" y="0" width="11" height="11" fill="#9be9a8" rx="2" ry="2"/>
              
                <rect class="day" x="135" y="0" width="11" height="11" fill="#30a14e" rx="2" ry="2"/>
              
                <rect class="day" x="150" y="0" width="11" height="11" fill="#9be9a8" rx="2" ry="2"/>
              
                <rect class="day" x="165" y="0" width="11" height="11" fill="#40c463" rx="2" ry="2"/>
              
                <rect class="day" x="180" y="0" width="11" height="11" fill="#216e39" rx="2" ry="2"/>
              
                <rect class="day" x="195" y="0" width="11" height="11" fill="#9be9a8" rx="2" ry="2"/>
              
            </g>
          </svg>
        </div>
        <div class="field">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1 2.5A2.5 2.5 0 013.5 0h8.75a.75.75 0 01.75.75v3.5a.75.75 0 01-1.5 0V1.5h-8a1 1 0 00-1 1v6.708A2.492 2.492 0 013.5 9h3.25a.75.75 0 010 1.5H3.5a1 1 0 100 2h5.75a.75.75 0 010 1.5H3.5A2.5 2.5 0 011 11.5v-9zm13.23 7.79a.75.75 0 001.06-1.06l-2.505-2.505a.75.75 0 00-1.06 0L9.22 9.229a.75.75 0 001.06 1.061l1.225-1.224v6.184a.75.75 0 001.5 0V9.066l1.224 1.224z"/></svg>
          Contributed to 6 repositories
        </div>
      </section>
    </div>
  </section>

      
        <div class="row">
  
  
</div>
      
        
  <section>
    <h2 class="field">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h8.75a.75.75 0 01.75.75v12.5a.75.75 0 01-.75.75h-2.5a.75.75 0 110-1.5h1.75v-2h-8a1 1 0 00-.714 1.7.75.75 0 01-1.072 1.05A2.495 2.495 0 012 11.5v-9zm10.5-1V9h-8c-.356 0-.694.074-1 .208V2.5a1 1 0 011-1h8zM5 12.25v3.25a.25.25 0 00.4.2l1.45-1.087a.25.25 0 01.3 0L8.6 15.7a.25.25 0 00.4-.2v-3.25a.25.25 0 00-.25-.25h-3.5a.25.25 0 00-.25.25z"/></svg>
      23 Repositories 
    </h2>
    <div class="row">
      <section>
        <div class="field">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M8.75.75a.75.75 0 00-1.5 0V2h-.984c-.305 0-.604.08-.869.23l-1.288.737A.25.25 0 013.984 3H1.75a.75.75 0 000 1.5h.428L.066 9.192a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.514 3.514 0 00.686.45A4.492 4.492 0 003 11c.88 0 1.556-.22 2.023-.454a3.515 3.515 0 00.686-.45l.045-.04.016-.015.006-.006.002-.002.001-.002L5.25 9.5l.53.53a.75.75 0 00.154-.838L3.822 4.5h.162c.305 0 .604-.08.869-.23l1.289-.737a.25.25 0 01.124-.033h.984V13h-2.5a.75.75 0 000 1.5h6.5a.75.75 0 000-1.5h-2.5V3.5h.984a.25.25 0 01.124.033l1.29.736c.264.152.563.231.868.231h.162l-2.112 4.692a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.517 3.517 0 00.686.45A4.492 4.492 0 0013 11c.88 0 1.556-.22 2.023-.454a3.512 3.512 0 00.686-.45l.045-.04.01-.01.006-.005.006-.006.002-.002.001-.002-.529-.531.53.53a.75.75 0 00.154-.838L13.823 4.5h.427a.75.75 0 000-1.5h-2.234a.25.25 0 01-.124-.033l-1.29-.736A1.75 1.75 0 009.735 2H8.75V.75zM1.695 9.227c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L3 6.327l-1.305 2.9zm10 0c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L13 6.327l-1.305 2.9z"/></svg>
          
            Prefers MIT license
          
        </div>
        <div class="field">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"/></svg>
          35 Releases
        </div>
        <div class="field">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M8.878.392a1.75 1.75 0 00-1.756 0l-5.25 3.045A1.75 1.75 0 001 4.951v6.098c0 .624.332 1.2.872 1.514l5.25 3.045a1.75 1.75 0 001.756 0l5.25-3.045c.54-.313.872-.89.872-1.514V4.951c0-.624-.332-1.2-.872-1.514L8.878.392zM7.875 1.69a.25.25 0 01.25 0l4.63 2.685L8 7.133 3.245 4.375l4.63-2.685zM2.5 5.677v5.372c0 .09.047.171.125.216l4.625 2.683V8.432L2.5 5.677zm6.25 8.271l4.625-2.683a.25.25 0 00.125-.216V5.677L8.75 8.432v5.516z"/></svg>
          2 Packages
        </div>
        <div class="field">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" d="M2.5 3.5c0-.133.058-.318.282-.55.227-.237.592-.484 1.1-.708C4.899 1.795 6.354 1.5 8 1.5c1.647 0 3.102.295 4.117.742.51.224.874.47 1.101.707.224.233.282.418.282.551 0 .133-.058.318-.282.55-.227.237-.592.484-1.1.708C11.101 5.205 9.646 5.5 8 5.5c-1.647 0-3.102-.295-4.117-.742-.51-.224-.874-.47-1.101-.707-.224-.233-.282-.418-.282-.551zM1 3.5c0-.626.292-1.165.7-1.59.406-.422.956-.767 1.579-1.041C4.525.32 6.195 0 8 0c1.805 0 3.475.32 4.722.869.622.274 1.172.62 1.578 1.04.408.426.7.965.7 1.591v9c0 .626-.292 1.165-.7 1.59-.406.422-.956.767-1.579 1.041C11.476 15.68 9.806 16 8 16c-1.805 0-3.475-.32-4.721-.869-.623-.274-1.173-.62-1.579-1.04-.408-.426-.7-.965-.7-1.591v-9zM2.5 8V5.724c.241.15.503.286.779.407C4.525 6.68 6.195 7 8 7c1.805 0 3.475-.32 4.722-.869.275-.121.537-.257.778-.407V8c0 .133-.058.318-.282.55-.227.237-.592.484-1.1.708C11.101 9.705 9.646 10 8 10c-1.647 0-3.102-.295-4.117-.742-.51-.224-.874-.47-1.101-.707C2.558 8.318 2.5 8.133 2.5 8zm0 2.225V12.5c0 .133.058.318.282.55.227.237.592.484 1.1.708 1.016.447 2.471.742 4.118.742 1.647 0 3.102-.295 4.117-.742.51-.224.874-.47 1.101-.707.224-.233.282-.418.282-.551v-2.275c-.241.15-.503.285-.778.406-1.247.549-2.917.869-4.722.869-1.805 0-3.475-.32-4.721-.869a6.236 6.236 0 01-.779-.406z"/></svg>
          3.63 GB used
        </div>
        
            <div class="field ">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M2.75 1.5a.25.25 0 00-.25.25v12.5c0 .138.112.25.25.25h10.5a.25.25 0 00.25-.25V4.664a.25.25 0 00-.073-.177l-2.914-2.914a.25.25 0 00-.177-.073H2.75zM1 1.75C1 .784 1.784 0 2.75 0h7.586c.464 0 .909.184 1.237.513l2.914 2.914c.329.328.513.773.513 1.237v9.586A1.75 1.75 0 0113.25 16H2.75A1.75 1.75 0 011 14.25V1.75zm7 1.5a.75.75 0 01.75.75v1.5h1.5a.75.75 0 010 1.5h-1.5v1.5a.75.75 0 01-1.5 0V7h-1.5a.75.75 0 010-1.5h1.5V4A.75.75 0 018 3.25zm-3 8a.75.75 0 01.75-.75h4.5a.75.75 0 010 1.5h-4.5a.75.75 0 01-.75-.75z"/></svg>
              
                1.79m added, 624k removed
              
            </div>
        
      </section>
      <section>
        <div class="field">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M4.25 2.5c-1.336 0-2.75 1.164-2.75 3 0 2.15 1.58 4.144 3.365 5.682A20.565 20.565 0 008 13.393a20.561 20.561 0 003.135-2.211C12.92 9.644 14.5 7.65 14.5 5.5c0-1.836-1.414-3-2.75-3-1.373 0-2.609.986-3.029 2.456a.75.75 0 01-1.442 0C6.859 3.486 5.623 2.5 4.25 2.5zM8 14.25l-.345.666-.002-.001-.006-.003-.018-.01a7.643 7.643 0 01-.31-.17 22.075 22.075 0 01-3.434-2.414C2.045 10.731 0 8.35 0 5.5 0 2.836 2.086 1 4.25 1 5.797 1 7.153 1.802 8 3.02 8.847 1.802 10.203 1 11.75 1 13.914 1 16 2.836 16 5.5c0 2.85-2.045 5.231-3.885 6.818a22.08 22.08 0 01-3.744 2.584l-.018.01-.006.003h-.002L8 14.25zm0 0l.345.666a.752.752 0 01-.69 0L8 14.25z"/></svg>
          0 Sponsors
        </div>
        <div class="field">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"/></svg>
          1978 Stargazers
        </div>
        <div class="field">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"/></svg>
          108 Forks
        </div>
        <div class="field">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"/></svg>
          85 Watchers
        </div>
        
      </section>
    </div>
  </section>

      
        
      
        
      
        
      
        
      
        
      
        
      
        
      
        
      
        
      
        
      
        
      
        
      
        
      
        
      
        
      

      
      <div id="metrics-end"></div>

    </div>
  </foreignObject>

</svg>
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About


<!--
**m4nasi/m4nasi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.




