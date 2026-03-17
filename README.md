# erebyss
<h1>Erebyss AI — Product Feedback Aggregator</h1>

<p>
  Erebyss is an AI-powered product intelligence platform that transforms scattered customer feedback into clear product decisions.
</p>

<p>
  Most teams collect feedback across tools like Zendesk, Slack, email, support tickets, surveys, and community forums.
  The problem is not collecting feedback. The problem is making sense of it.
</p>

<p>
  Erebyss solves that problem by turning raw customer signals into structured outputs that product and business teams can act on immediately.
</p>

<hr />

<h2>What It Does</h2>

<p>Erebyss takes in customer feedback and automatically generates:</p>

<ul>
  <li><strong>Themes</strong> — grouped patterns across feedback</li>
  <li><strong>Insights</strong> — clear summaries of customer pain points</li>
  <li><strong>Recommendations</strong> — suggested actions tied to each insight</li>
  <li><strong>Impact Scoring</strong> — priority, effort, revenue risk, and customer segment</li>
  <li><strong>Roadmap</strong> — ranked product initiatives</li>
  <li><strong>Revenue Impact Summary</strong> — highlights what is actually costing the business</li>
</ul>

<p>
  Instead of reading hundreds of comments, teams get:
</p>

<blockquote>
  “Here are your biggest problems, here is what to fix, and here is what it’s costing you.”
</blockquote>

<hr />

<h2>Why It Matters</h2>

<p>Product teams often struggle with:</p>

<ul>
  <li>Too much feedback and not enough clarity</li>
  <li>Sales and product misalignment</li>
  <li>Unclear prioritization</li>
  <li>Guessing what actually impacts revenue</li>
</ul>

<p>
  Erebyss bridges that gap by connecting:
</p>

<pre><code>Customer Feedback → Product Decisions → Business Impact</code></pre>

<hr />

<h2>How It Works</h2>

<ol>
  <li>
    <strong>Preprocess</strong><br />
    Cleans and structures raw feedback.
  </li>
  <li>
    <strong>Theme Extraction</strong><br />
    Groups feedback into meaningful clusters.
  </li>
  <li>
    <strong>Insight Generation</strong><br />
    Summarizes key problems and recommendations.
  </li>
  <li>
    <strong>Scoring Layer</strong><br />
    Adds:
    <ul>
      <li><code>impact_score</code></li>
      <li><code>effort_estimate</code></li>
      <li><code>customer_segment</code></li>
      <li><code>revenue_risk</code></li>
    </ul>
  </li>
  <li>
    <strong>Roadmap Agent</strong><br />
    Converts insights into prioritized initiatives.
  </li>
  <li>
    <strong>Revenue Impact Layer</strong><br />
    Surfaces high-risk issues and top blockers.
  </li>
</ol>

<hr />

<h2>Example Output</h2>

<p><strong>Insight</strong><br />
Users are experiencing delays due to slow dashboard updates and unreliable API refresh.
</p>

<p><strong>Roadmap Item</strong><br />
Improve dashboard performance and API reliability.
</p>

<p><strong>Revenue Impact</strong><br />
High risk — impacting onboarding and enterprise adoption.
</p>

<hr />

<h2>Tech Stack</h2>

<ul>
  <li><strong>FastAPI</strong> — backend API</li>
  <li><strong>Supabase</strong> — database and storage</li>
  <li><strong>Next.js</strong> — frontend</li>
  <li><strong>Python</strong> — LLM and processing pipeline</li>
</ul>

<hr />

<h2>Vision</h2>

<p>
  Erebyss is building toward becoming the system of record for:
</p>

<ul>
  <li>Product prioritization</li>
  <li>Sales blocker detection</li>
  <li>Customer-driven roadmap generation</li>
</ul>

<p>
  The long-term goal is simple:
</p>

<blockquote>
  Help companies understand what to build next, based on real customer signals and real business impact.
</blockquote>

<hr />

<h2>Current MVP Capabilities</h2>

<ul>
  <li>One-click analysis pipeline</li>
  <li>Automated preprocess, themes, insights, and roadmap generation</li>
  <li>Impact and revenue-risk scoring</li>
  <li>Evidence-backed recommendations</li>
  <li>Roadmap ranking based on customer signals</li>
</ul>

<hr />

<h2>Future Direction</h2>

<ul>
  <li>Sales blocker intelligence engine</li>
  <li>Competitive intelligence analysis</li>
  <li>Trend detection across runs</li>
  <li>Slack, Notion, and Jira integrations</li>
  <li>Executive-level product health dashboards</li>
</ul>
