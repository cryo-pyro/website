<!-- Drop this anywhere in your README.md or page HTML -->
<script>
  window.MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$','$$'], ['\\[','\\]']],
      processEscapes: true
    },
    options: {
      skipHtmlTags: ['script','noscript','style','textarea','pre','code']
    }
  };
</script>
<script id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>

- `ukb-dt`: January 28, 2026
- `cryo-pyro`: Februaru 16, 2026
- `ukb-pyro`: TBA
- `eplnm`
- `jhufena`
- `pairs-jh`
- `jhustata`
- `muzaale`
- `abikesa`
- `jhurepos`
- `ukubona-llc`

# G
This is a powerful conceptual framework. To make the website **coherent**, we need to bridge the gap between the abstract philosophy (SGD, ants, raindrops) and the concrete entities (Person, Ministry of Health).

The "Post-Metaphor" instruction is key here: we aren't saying society is *like* a neural network; we are saying it *is* an optimization process running on a biological substrate.

Here is a proposed content structure that threads the **SGD/Calculus mechanics** through the **hierarchy of agents** (Person → Government).

### Core Narrative Arc

**The Problem:** The Loss Landscape (Pain, Disease, Inefficiency).
**The Mechanism:** Stochastic Gradient Descent (How we find solutions).
**The Solution:** Ukubona (The tool that makes the gradient visible).

---

### Section 1: The Landscape (UNIV)

*Context: Defining the environment.*

**Headline:** The Terrain of Reality
**Content:**
We exist in a high-dimensional loss landscape. This is not a metaphor; it is the mathematical reality of survival.

* **The Territory:** The biological and social reality we navigate. It is rugged, filled with peaks of high energy cost (sickness, poverty) and basins of stability (health, prosperity).
* **The Loss Function:** The difference between where we are (Reality) and where we need to be (The Ideal/Survival).
* **The Blindness:** We cannot see the full terrain. We only know our current coordinate $(x, y)$ and the immediate pain or comfort we feel.

### Section 2: The Agent (UB - Person)

*Context: The individual as the stochastic explorer.*

**Headline:** The Scout (Person)
**Concept:** `Forage, stochastically`
**Content:**
The individual is the high-variance input .

* **The Action:** To live is to forage. We explore blindly, taking steps in the dark.
* **The Risk:** Most paths lead to higher loss. Sickness is a local maximum of suffering; death is the gradient instability.
* **The Need:** The person needs a signal. They need to know which direction lowers the loss function without having to die to find out.
* **Calculus Translation:** The individual is solving for $\theta_{t+1} = \theta_t - \eta \nabla L(\theta_t)$. Without Ukubona, the gradient $\nabla L$ is invisible. They are guessing.

### Section 3: The Aggregate (Household)

*Context: The first layer of collective optimization.*

**Headline:** The Cluster (Household)
**Concept:** `Rehearse, consequentially`
**Content:**
Small clusters reduce variance.

* **The Buffer:** The household pools resources to survive bad stochastic outcomes. If one scout falls, the cluster survives.
* **The Transmission:** Here, the "pheromone trail" is culture and habit. "Wash your hands," "Cook this way." These are heuristic gradients passed down to lower the collective loss.

### Section 4: The Interface (Firm - Clinic/Hospital/School)

*Context: Professionalizing the gradient descent.*

**Headline:** The Pheromone Infrastructure (Firm)
**Concept:** `See, blindly` (Making the invisible visible)
**Content:**
Clinics and Universities are the "UI" of civilization. They exist to linearize the chaotic path of the individual.

* **The Clinic:** It is a machine for gradient descent. A patient arrives stuck in a high-loss state (illness). The doctor provides the map (diagnosis/treatment) to a lower energy basin (health).
* **The School:** It accelerates the "training run" of the neural net. Instead of learning by dying (evolution), we learn by rehearsal (education).
* **Ukubona’s Role:** We turn the Clinic into a **Digital Twin**. We replace "seeing blindly" (guessing) with clear calculus. We calculate the derivative  $\frac{dy}{dt}$—the exact direction of health improvement—so the firm doesn't just treat; it optimizes.

### Section 5: The Optimizer (Government - Ministry of Health)

*Context: Managing the total loss function of the population.*

**Headline:** The Landscape Architect (Government)
**Concept:** `Calculus of the Whole`
**Content:**
The Ministry does not treat the patient; it treats the *distribution*.

* **The Aggregate Loss:** The sum of all individual suffering  $\sum L(x)$.
* **The Policy:** Policy is the hyperparameter tuning (learning rate , regularization). A policy change is an update to the global algorithm.
* **The Gap:** Governments currently govern using outdated maps. They optimize for a terrain that no longer exists.
* **Post-Metaphor:** Ukubona provides the Ministry with real-time telemetry of the loss landscape. Not a survey, but a dashboard of the collective gradient.

---

### Proposed Tagline Options

1. **"Civilization is an optimization problem. We provide the gradient."**
2. **"Stop foraging. Start descending."**
3. **"From Blind Striving to Calculated Descent."**

### Visual/UX Structure (Draft)

* **Hero Section:** A visualization of a rugged 3D landscape (Loss Landscape). A single dot (Person) moves erratically (Stochastic).
* **Scroll Trigger:** As the user scrolls, the "fog of war" lifts (Ukubona/Seeing). The path becomes clear (Gradient).
* **Cards/Tabs for Entities:**
* **For the Person:** "See your health."
* **For the Clinic:** "Map your patient's path."
* **For the Ministry:** "Optimize the population."



This structure moves the user from the **Philosophy** (the "Why") to the **Entity** (the "Who") using the **Mechanism** (the "How").

To implement the "Civilization as Optimization" narrative, we need to move your codebase from **Stochastic Foraging** (scattered files) to **Gradient Descent** (aligned vectors).

Your file tree shows a classic "organic growth" structure. To get the coherence you want without destroying the distributed nature you love, we will create a **Core System (The Kernel)** that the distributed parts inherit from.

Here is the execution plan to centralize your assets and build the narrative spine.

### Phase 1: The Apollonian Consolidation (Terminal)

We need to merge the scattered styles and scripts into a single "Truth" to ensure the Person, Firm, and Government sections feel like part of the same universe.

Run these commands in your terminal to create your centralized build targets without deleting your source files yet.

```bash
# 1. Create a "dist" (distribution) folder for the coherent build
mkdir -p assets/dist/css
mkdir -p assets/dist/js

# 2. Concatenate your core CSS into a single 'ukubona-core.css'
# Order matters: Variables/Reset -> Layout -> Components -> Specifics
cat assets/css/main.css \
    assets/css/index.css \
    assets/css/card.css \
    assets/css/team.css \
    assets/css/ukhona.css \
    > assets/dist/css/ukubona-core.css

# 3. Concatenate your core JS into 'ukubona-core.js'
cat assets/js/shared.js \
    assets/js/tooltips.js \
    assets/js/landing.js \
    assets/js/card.js \
    > assets/dist/js/ukubona-core.js

```

### Phase 2: The "Physics" (CSS Architecture)

Open `assets/dist/css/ukubona-core.css` and **prepend** this to the very top. This is the "Universal Field Theory" of your site—defining the constraints that make it coherent.

```css
:root {
    /* --- The Landscape (Colors) --- */
    /* Stark, mathematical contrast. No "friendly" corporate blues. */
    --c-void: #0a0a0a;       /* The Unknown / Loss Landscape */
    --c-matter: #f4f4f4;     /* The Visible / Structure */
    --c-gradient: #FF4D00;   /* The Scout / Action / Error Signal */
    --c-basin: #2A2A2A;      /* The Stable State */
    
    /* --- The Grid (Spacing) --- */
    /* Apollonian Integers */
    --space-unit: 8px;
    --space-xs: calc(var(--space-unit) * 1);
    --space-md: calc(var(--space-unit) * 3);
    --space-xl: calc(var(--space-unit) * 8);
    --space-geo: calc(var(--space-unit) * 16); /* Geological spacing between sections */

    /* --- The Voice (Typography) --- */
    --font-mono: "SF Mono", "Roboto Mono", monospace; /* For the Code/Math */
    --font-sans: "Inter", system-ui, sans-serif;      /* For the Narrative */
}

/* Base State */
body {
    background-color: var(--c-void);
    color: var(--c-matter);
    font-family: var(--font-sans);
    line-height: 1.6;
    margin: 0;
}

/* The Scout / Interaction Points */
a, .btn, .interactive {
    color: var(--c-gradient);
    text-decoration: none;
    border-bottom: 1px solid transparent;
    transition: all 0.2s ease;
}

a:hover {
    border-bottom: 1px solid var(--c-gradient);
}

```

### Phase 3: The Narrative Spine (New Index)

We are abandoning the old `index.html` that just links out to pages. We are building the **Scroll of Descent**.

Create a new file `index-coherent.html`. This structure maps exactly to the strategy we discussed:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ukubona | The Algorithm of Us</title>
    
    <link rel="stylesheet" href="assets/dist/css/ukubona-core.css">
    
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
</head>
<body>

    <nav class="ukb-nav">
        <div class="logo">UKUBONA (UKB)</div>
        <div class="status">Current Basin: 2026</div>
    </nav>

    <section class="layer univ" id="landscape">
        <div class="container">
            <h1 class="glitch-text">Civilization as Optimization.</h1>
            <p class="lead">
                No deity. No destiny. Only <span class="math-term">Stochastic Gradient Descent</span>.
            </p>
            <div class="visual-container">
                <div id="loss-landscape-canvas"></div> 
            </div>
        </div>
    </section>

    <section class="layer ub" id="scout">
        <div class="split-layout">
            <div class="text-block">
                <h2>I. The Scout</h2>
                <h3>Forage, Stochastically.</h3>
                <p>
                    The individual is the noise term ($+\epsilon$). You explore the terrain of health and survival blindly.
                    Without a map, exploration is just trauma.
                </p>
                <div class="math-block">
                    $$ \theta_{t+1} = \theta_t - \eta \nabla L(\theta_t) + \epsilon $$
                </div>
            </div>
            <div class="demo-block">
                <div class="card-ui">
                    <span class="label">Digital Twin: Person</span>
                    <div class="status-indicator bad">Gradient: Unknown</div>
                </div>
            </div>
        </div>
    </section>

    <section class="layer ui" id="firm">
        <div class="split-layout">
            <div class="demo-block">
                 <div class="card-ui">
                    <span class="label">Digital Twin: Clinic</span>
                    <div class="status-indicator good">Gradient: Visible</div>
                </div>
            </div>
            <div class="text-block">
                <h2>II. The Cartographer</h2>
                <h3>See, Blindly.</h3>
                <p>
                    Clinics and Schools are the infrastructure of descent. We provide the 
                    <span class="highlight">Calculus of Care</span>—turning random patient data into a directional vector.
                </p>
                <button class="btn-primary">View The Clinic Interface</button>
            </div>
        </div>
    </section>

    <section class="layer ux" id="gov">
        <div class="container centered">
            <h2>III. The Architect</h2>
            <h3>Rehearse, Consequentially.</h3>
            <p>
                Policy is hyperparameter tuning. The Ministry optimizes the sum of all loss functions.
            </p>
            <div class="dashboard-preview">
                [ Global Loss Function Dashboard ]
            </div>
        </div>
    </section>

    <footer class="ukb-footer">
        <p>UKUBONA LLC &copy; 2026</p>
        <p>Start Descending.</p>
    </footer>

    <script src="assets/dist/js/ukubona-core.js"></script>
</body>
</html>

```

### Next Steps for You

1. **Run the bash script** to create the `dist` files.
2. **Copy the HTML structure** above into a new file `index-coherent.html` to test it (don't overwrite your main index until it looks right).
3. **Check the CSS:** Open `index-coherent.html` in your browser. It will look broken initially because we just mashed all CSS together. You will likely need to go into `ukubona-core.css` and resolve conflicts (e.g., if `.hero` is defined twice).

This gives you a **Single Source of Truth** (`ukubona-core.css`) while keeping your folder structure ready for the distributed future.
# O

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ukubona LLC</title>

<style>
:root {
    --bg: #0d0f14;
    --text: #e6e9ef;
    --accent: #4cc9f0;
    --muted: #9aa3b2;
    --card: #151923;
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
}

body {
    background: var(--bg);
    color: var(--text);
    line-height: 1.6;
}

header {
    padding: 4rem 2rem;
    text-align: center;
    border-bottom: 1px solid #222;
}

header h1 {
    font-size: 2.8rem;
    letter-spacing: 1px;
}

header p {
    margin-top: 1rem;
    color: var(--muted);
    max-width: 700px;
    margin-left: auto;
    margin-right: auto;
}

nav {
    display: flex;
    justify-content: center;
    gap: 2rem;
    padding: 1rem;
    border-bottom: 1px solid #222;
}

nav a {
    color: var(--muted);
    text-decoration: none;
    font-size: 0.9rem;
    transition: 0.3s;
}

nav a:hover {
    color: var(--accent);
}

section {
    padding: 4rem 2rem;
    max-width: 1100px;
    margin: auto;
}

section h2 {
    margin-bottom: 1.5rem;
    font-size: 1.8rem;
    color: var(--accent);
}

.grid {
    display: grid;
    gap: 2rem;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
}

.card {
    background: var(--card);
    padding: 2rem;
    border-radius: 8px;
    border: 1px solid #222;
}

.card h3 {
    margin-bottom: 1rem;
}

footer {
    text-align: center;
    padding: 3rem 2rem;
    border-top: 1px solid #222;
    color: var(--muted);
    font-size: 0.9rem;
}
</style>
</head>

<body>

<header>
    <h1>Ukubona LLC</h1>
    <p>
        We build adaptive systems for health and human development.
        We operate in incomplete information environments.
        We reduce the gap between intention and outcome.
    </p>
</header>

<nav>
    <a href="#premise">Premise</a>
    <a href="#method">Method</a>
    <a href="#levels">Systems</a>
    <a href="#philosophy">Post-Metaphor</a>
</nav>

<section id="premise">
    <h2>Premise</h2>
    <p>
        The world is not fully visible. It arrives as signals, delays, and noise.
        Every person, household, firm, and ministry operates with incomplete maps of reality.
    </p>
    <p>
        The difference between the map and the territory is loss.
        Loss is measurable. Loss is improvable.
    </p>
    <p>
        Ukubona exists to reduce that gap.
    </p>
</section>

<section id="method">
    <h2>Method</h2>
    <div class="grid">
        <div class="card">
            <h3>See, Blindly</h3>
            <p>
                Measurement acknowledges uncertainty.
                Data is partial. Signals are noisy.
                Perception is iterative.
            </p>
        </div>

        <div class="card">
            <h3>Forage, Stochastically</h3>
            <p>
                We move through uncertainty using bounded steps.
                Pilot programs. Iterative updates.
                Each step produces feedback.
            </p>
        </div>

        <div class="card">
            <h3>Rehearse, Consequentially</h3>
            <p>
                Every intervention is a hypothesis.
                Outcomes are gradient signals.
                Systems improve through structured iteration.
            </p>
        </div>
    </div>

    <p style="margin-top:2rem;">
        Calculus describes change.
        A derivative is a rate of change.
        Health indicators, education metrics, and institutional performance
        are dynamic variables.
    </p>

    <p>
        Stochastic Gradient Descent is disciplined search under uncertainty.
        Sample. Measure loss. Adjust. Repeat.
    </p>
</section>

<section id="levels">
    <h2>System Levels</h2>
    <div class="grid">

        <div class="card">
            <h3>Person</h3>
            <p>
                Individuals operate within limited bandwidth.
                Feedback loops from diagnostics and behavior tracking
                improve personal models of health and decision-making.
            </p>
        </div>

        <div class="card">
            <h3>Household</h3>
            <p>
                Households allocate shared resources.
                Data coordination improves financial, nutritional,
                and educational optimization.
            </p>
        </div>

        <div class="card">
            <h3>Firm</h3>
            <p>
                Clinics, hospitals, schools, and universities are
                error-minimizing systems.
                Performance metrics define their loss functions.
            </p>
        </div>

        <div class="card">
            <h3>Government</h3>
            <p>
                Ministries operate with delayed and noisy feedback.
                Policy without measurement is blind descent.
                Structured experimentation enables adaptive governance.
            </p>
        </div>

    </div>
</section>

<section id="philosophy">
    <h2>Post-Metaphor</h2>
    <p>
        Metaphors help intuition.
        Operational systems require measurement.
    </p>
    <p>
        Post-metaphor means translating narrative into metrics.
        Turning intention into update rules.
        Converting story into signal.
    </p>
    <p>
        Every model is provisional.
        Landscapes shift.
        The only failure is refusing to update.
    </p>
</section>

<footer>
    Ukubona LLC · Adaptive Systems for Health & Human Development
</footer>

</body>
</html>

```

Good. Now we stop philosophizing and start refactoring.

You don’t need more files. You need a spine.

Right now your repo looks like an archaeological dig. Forty-one HTML files means entropy. Entropy is unoptimized loss.

Let’s reduce dimensionality.

Step 1: Decide the canonical architecture.

You need exactly this structure at the top level of meaning:

Home
Philosophy
Models
Systems (Person → Government)
Team
Contact

Everything else becomes either:
– archived experiments
– embedded components
– or deleted

Brutal pruning reduces cognitive loss.

---

Step 2: Treat `index.html` as the only gravitational center.

Open `index.html`.

Instead of letting it sprawl, make it a clean assembly file that loads modular sections:

Header
Hero
Premise
Method
Systems
Philosophy
Footer

You already have partials like:

assets/html/header.html
assets/html/hero.html
assets/html/mission.html
assets/html/models.html
assets/html/services-section.html
assets/html/metrics-section.html
assets/html/footer.html

That’s good. That’s a compositional system.

Now enforce hierarchy:

Hero → Premise → Method → Systems → Philosophy → CTA

Nothing else.

---

Step 3: Collapse conceptual redundancy.

You have:

philosophy.html
ukhona.html
ukhona-orig.html

Pick one. Merge content. Delete the rest.

Same with multiple dt-* files unless they are truly research artifacts.

Entropy in file naming signals unclear abstraction boundaries.

In software architecture, that’s a smell.

---

Step 4: Make SGD literal in the site behavior.

Right now your site talks about stochastic gradient descent. Make it visible.

Ideas:

• A simple visual gradient-descent simulation in `game.js` tied to real-world metrics.
• A slider that changes “policy step size” and shows overshoot vs convergence.
• A loss landscape animation using canvas.

You already have game.js and ant-colony imagery. That’s perfect. Ant colony optimization is literally stochastic search.

Make that your interactive anchor.

Not decorative. Didactic.

---

Step 5: Define operational modules.

Create three conceptual layers:

Layer 1: Sensing
Data ingestion, measurement, dashboards.

Layer 2: Modeling
Prediction, simulation, scenario rehearsal.

Layer 3: Acting
Deployment, pilot testing, iteration.

Now align existing HTML files to these layers.

If a page doesn’t map to Sensing, Modeling, or Acting, question why it exists.

You are building a cybernetic organism, not a brochure.

---

Step 6: Clean CSS entropy.

You have:

card.css
game.css
index-orig.css
index.css
main.css
team.css
ukhona.css

That is fragmentation.

Merge into:

main.css
components.css
pages.css

Or go further: a single main.css if manageable.

Every CSS file increases maintenance gradient.

---

Step 7: Define GitHub Pages as deployment pipeline.

Your site is static. That’s fine.

Your iteration loop becomes:

Edit → Commit → Push → Observe → Adjust

That is literal stochastic descent on messaging clarity.

Measure:
– Bounce rate
– Scroll depth
– Time on page

Even simple GitHub traffic analytics gives directional gradient.

---

Step 8: Kill ornamental ambiguity.

Your philosophy must be compressed to one governing equation:

Reality – Model = Loss
Loss → Feedback
Feedback → Update
Update → Reduced Loss

Put that somewhere central.

Let the rest elaborate.

---

Step 9: Align imagery with theory.

You have:

ant colony
raindrop erosion
terraforming
loss landscape images

These are gradient metaphors.

Use them intentionally:

Ant colony → stochastic exploration
Raindrop erosion → iterative change
Terraforming → large-scale system shaping
Loss landscape → optimization

Right now they’re probably aesthetic. They should be epistemic.

---

Step 10: Execution order.

Concrete next actions, today:

1. Backup branch: `pre-refactor`
2. Create branch: `architecture-v1`
3. Delete duplicate philosophy files.
4. Simplify index.html to clean vertical narrative.
5. Merge CSS.
6. Push.
7. Review live site.
8. Iterate.

Do not try to perfect. Iterate.

---

Zoom out.

You’re not just implementing a website.

You’re implementing a worldview:

Institutions are adaptive systems.
Health is dynamic optimization.
Policy is stochastic search.

The site must feel like a system that learns.

And here’s the quiet paradox: once you clean the structure, your ideas will sharpen automatically. Clarity of file tree improves clarity of thought. Software architecture and epistemology are not separate domains.

Now the interesting frontier is this: when your Ministry of Health pitch lands, does the site look like a think tank, a lab, or a living model?

Because those are three different attractors in the loss landscape.

# A
## I
Perfect. Let's implement strategically. You already have the infrastructure—we just need to reorganize and add key connecting pieces.

## IMPLEMENTATION PLAN

### **PHASE 1: Homepage Clarity (Priority 1)**
Your current `index.html` needs to immediately answer: "What problem does Ukubona solve?"

```bash
# Create new homepage structure
code assets/html/home-hero.html
code assets/html/home-problem.html
code assets/html/home-solution.html
code assets/html/home-proof.html
```

### **PHASE 2: Create Solutions Page (Priority 2)**
New page showing algorithm at different scales

```bash
code assets/html/solutions.html
code assets/css/solutions.css
```

### **PHASE 3: Simplify Navigation (Priority 3)**
```bash
# Update existing files
code assets/html/header.html  # Add Solutions link
code assets/html/footer.html  # Add quick links
```

---

## LET'S START: I'll create the content files

Should I:

**Option A: Create all files now** (you review, then integrate)
- `home-hero.html` - Opening hook
- `home-problem.html` - Loss landscape framing
- `home-solution.html` - Digital twins explained
- `home-proof.html` - NHANES/Uganda demos
- `solutions.html` - Person→Clinic→Government
- Updated `header.html` - New nav

**Option B: Build iteratively** (one section at a time, you test)
- Start with just `home-hero.html`
- You integrate into `index.html`
- We iterate until it's right
- Then move to next section

**Option C: Audit first** (I review your existing HTML structure)
- Look at current `index.html`, `hero.html`, `mission.html`
- Tell you exactly what to keep/modify/replace
- Minimize disruption to working code

Which approach fits your workflow?

Also: Do you want me to **preserve your existing aesthetic** (dark mode, minimalist, equation-forward) or **suggest evolution**?

## II
# LET'S FUCKING BUILD

## CREATING NEW CONTENT FILES (keeping old untouched)

```bash
# New homepage sections
cat > assets/html/home-v2-hero.html << 'EOF'
<section class="hero-v2">
    <div class="container">
        <div class="hero-content">
            <h1>Your Body Runs Stochastic Gradient Descent<br>10¹⁴ Times Per Second</h1>
            <p class="hero-subtitle">
                Healthcare still uses population averages.<br>
                We build <strong>digital twins</strong> that make <em>your</em> personal loss landscape rehearsable.
            </p>
            <div class="hero-cta">
                <a href="#problem" class="btn-primary">See the problem</a>
                <a href="assets/html/nhanes.html" class="btn-secondary">Try the demo</a>
            </div>
        </div>
        <div class="hero-visual">
            <img src="assets/img/ant-colony-simulation-game-prototype-pheromone-foraging.jpg" 
                 alt="Ant colony optimization - stochastic foraging to gradient descent">
            <p class="caption">Chaos → Gradient → Basin. The universal algorithm.</p>
        </div>
    </div>
</section>
EOF

# The Problem section
cat > assets/html/home-v2-problem.html << 'EOF'
<section id="problem" class="problem-section">
    <div class="container">
        <h2>The Map Is Not The Territory</h2>
        
        <div class="problem-grid">
            <div class="problem-card">
                <h3>What Your Doctor Says</h3>
                <p class="stat">"This treatment has a 60% success rate"</p>
                <p class="detail">Population average from clinical trials</p>
            </div>
            
            <div class="problem-card highlight">
                <h3>What You Need To Know</h3>
                <p class="stat">"Am I in the 60% or the 40%?"</p>
                <p class="detail">Your personal gradient, your terrain</p>
            </div>
            
            <div class="problem-card">
                <h3>Current Tools</h3>
                <p class="stat">Static risk calculators</p>
                <p class="detail">One number. No exploration. No rehearsal.</p>
            </div>
        </div>
        
        <div class="problem-statement">
            <p>
                Medicine uses <strong>incomplete information</strong> about your terrain.<br>
                Same treatment → wildly different outcomes.<br>
                <strong>You cannot rehearse before you commit.</strong>
            </p>
        </div>
    </div>
</section>
EOF

# The Solution section
cat > assets/html/home-v2-solution.html << 'EOF'
<section id="solution" class="solution-section">
    <div class="container">
        <h2>Interactive Survival Models</h2>
        <p class="section-intro">
            We turn validated equations into <strong>playable scenarios</strong>.<br>
            See your gradient. Explore the terrain. Rehearse outcomes.
        </p>
        
        <div class="solution-demo">
            <div class="demo-left">
                <h3>What You Can Do:</h3>
                <ul class="feature-list">
                    <li>
                        <strong>See your gradient</strong>
                        <p>Personalized risk trajectory based on YOUR biomarkers</p>
                    </li>
                    <li>
                        <strong>Explore the terrain</strong>
                        <p>Adjust variables in real-time: medication adherence, lifestyle changes, treatment paths</p>
                    </li>
                    <li>
                        <strong>Rehearse outcomes</strong>
                        <p>Watch survival curves shift as you change parameters</p>
                    </li>
                    <li>
                        <strong>Compare paths</strong>
                        <p>Treatment A vs B vs C, visualized for YOUR specific terrain</p>
                    </li>
                </ul>
            </div>
            
            <div class="demo-right">
                <div class="live-demo-box">
                    <h4>Live Demo: NHANES Survival Model</h4>
                    <p>Interactive Kaplan-Meier curves. Real biomarkers. Your parameters.</p>
                    <a href="assets/html/nhanes.html" class="btn-demo">Explore the model →</a>
                </div>
                
                <div class="tech-stack">
                    <h4>The Stack:</h4>
                    <ul>
                        <li><strong>UB:</strong> Clinical trials = humanity's stochastic search</li>
                        <li><strong>UKB:</strong> Cox models, competing risks (validated equations)</li>
                        <li><strong>UI:</strong> Interactive dashboards that make gradients visible</li>
                        <li><strong>UX:</strong> Decision support that's individualized, explainable, comparable</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</section>
EOF

# The Scale section (Person → Government)
cat > assets/html/home-v2-scale.html << 'EOF'
<section id="scale" class="scale-section">
    <div class="container">
        <h2>The Same Algorithm, Different Substrates</h2>
        <p class="section-intro">
            Forage stochastically → Detect gradients → Descend collectively → Rehearse consequentially
        </p>
        
        <div class="scale-grid">
            <div class="scale-card">
                <div class="scale-icon">🧬</div>
                <h3>Person</h3>
                <p class="scale-example">
                    Your immune system tries 10¹⁴ antibody variants per second.<br>
                    Successful binding = kept, amplified.<br>
                    Memory B-cells = "what worked."
                </p>
                <p class="scale-ukubona">
                    <strong>Ukubona for you:</strong> Digital twin shows your personal survival terrain
                </p>
            </div>
            
            <div class="scale-card">
                <div class="scale-icon">🏥</div>
                <h3>Clinic / Hospital</h3>
                <p class="scale-example">
                    Pilot protocols. Track which patients improved.<br>
                    Standardize effective approaches.<br>
                    Case conferences = rehearsal loops.
                </p>
                <p class="scale-ukubona">
                    <strong>Ukubona for clinics:</strong> Decision support that's explainable and comparable
                </p>
            </div>
            
            <div class="scale-card">
                <div class="scale-icon">🗺️</div>
                <h3>Government / Ministry</h3>
                <p class="scale-example">
                    District-level interventions across 127 regions.<br>
                    Track outcomes. Scale what works.<br>
                    Policy simulations before deployment.
                </p>
                <p class="scale-ukubona">
                    <strong>Ukubona for policy:</strong> <a href="assets/html/cartography-256.html">Uganda Depression Map</a> — making invisible gradients visible
                </p>
            </div>
        </div>
        
        <div class="scale-principle">
            <p>
                This isn't metaphor. It's systems biology.<br>
                <strong>Local design decisions propagate into system-level consequences.</strong>
            </p>
        </div>
    </div>
</section>
EOF

# Proof / Shipped section
cat > assets/html/home-v2-proof.html << 'EOF'
<section id="proof" class="proof-section">
    <div class="container">
        <h2>Not Hypothesis. Shipped.</h2>
        
        <div class="proof-grid">
            <div class="proof-card">
                <h3>NHANES Survival Model</h3>
                <p class="proof-status">✅ Live</p>
                <p>Interactive Kaplan-Meier curves. Real biomarkers from 40,000+ participants. Adjust parameters, watch curves shift.</p>
                <a href="assets/html/nhanes.html" class="proof-link">Explore model →</a>
            </div>
            
            <div class="proof-card">
                <h3>Uganda Depression Map</h3>
                <p class="proof-status">✅ April 2026 deployment</p>
                <p>30.2% prevalence across 127 districts. 123,859 participants. Real-time heatmaps for policy decisions. 50-year optimization timeline.</p>
                <a href="assets/html/cartography-256.html" class="proof-link">See the cartography →</a>
            </div>
            
            <div class="proof-card">
                <h3>Game of Care Engine</h3>
                <p class="proof-status">✅ Validated equations → playable scenarios</p>
                <p>Turn survival curves into rehearsable decisions. Validated Cox models. Competing risks. Real clinical data.</p>
                <a href="assets/html/game.html" class="proof-link">Play the game →</a>
            </div>
        </div>
        
        <div class="proof-timeline">
            <h3>The 50-Year Game</h3>
            <div class="timeline">
                <div class="timeline-item">
                    <strong>2026-2027</strong>
                    <p>Ship digital twin for chronic disease management. Deploy Uganda dashboard.</p>
                </div>
                <div class="timeline-item">
                    <strong>2027-2035</strong>
                    <p>Every clinic has real-time outcome prediction. Physicians rehearse before prescribing.</p>
                </div>
                <div class="timeline-item">
                    <strong>2035-2076</strong>
                    <p>Healthcare = continuous gradient descent. Ministry dashboards track population loss surfaces in real-time.</p>
                </div>
            </div>
        </div>
    </div>
</section>
EOF

# Energy / Cost section
cat > assets/html/home-v2-cost.html << 'EOF'
<section id="cost" class="cost-section">
    <div class="container">
        <h2>Clarity Costs Energy</h2>
        <p class="section-intro">
            We say the quiet part aloud: every simulation, every rehearsal loop,<br>
            every digital twin update has a <strong>measurable kWh price</strong>.
        </p>
        
        <div class="cost-stats">
            <div class="cost-stat">
                <p class="stat-number">0.0003 kWh</p>
                <p class="stat-label">per inference</p>
            </div>
            <div class="cost-stat">
                <p class="stat-number">× 10⁹ patients</p>
                <p class="stat-label">hyperscale projections</p>
            </div>
            <div class="cost-stat">
                <p class="stat-number">= infrastructure design</p>
                <p class="stat-label">not just functionality</p>
            </div>
        </div>
        
        <div class="cost-principle">
            <p>
                As intelligence scales, demand scales.<br>
                <strong>Local design choices propagate through energy use, latency, and reliability.</strong><br>
                We're building for sustainability, not just performance.
            </p>
            <p class="cost-attribution">
                — <a href="assets/html/team.html#edward">Edward Ssemambo</a>, Energy Systems & Computation
            </p>
        </div>
    </div>
</section>
EOF

# Updated header with new nav
cat > assets/html/header-v2.html << 'EOF'
<header>
    <nav class="navbar">
        <div class="nav-container">
            <a href="index.html" class="nav-logo">
                <img src="assets/img/ukb.png" alt="Ukubona" height="40">
            </a>
            
            <ul class="nav-menu">
                <li><a href="index.html#problem">Problem</a></li>
                <li><a href="index.html#solution">Solution</a></li>
                <li><a href="index.html#scale">Scale</a></li>
                <li><a href="assets/html/nhanes.html">Demo</a></li>
                <li><a href="assets/html/team.html">Team</a></li>
                <li><a href="assets/html/ukhona.html" class="nav-philosophy">Philosophy</a></li>
                <li><a href="assets/html/contact.html" class="nav-cta">Contact</a></li>
            </ul>
            
            <button class="nav-toggle">☰</button>
        </div>
    </nav>
</header>
EOF

# CSS for new homepage
cat > assets/css/home-v2.css << 'EOF'
/* ============================================
   HOME V2 - COHESIVE NARRATIVE STYLING
   ============================================ */

:root {
    --primary: #00ff88;
    --primary-dim: #00cc6a;
    --bg-dark: #0a0a0a;
    --bg-card: #111111;
    --text-primary: #e0e0e0;
    --text-secondary: #999999;
    --accent-orange: #ff6b35;
    --accent-blue: #4a9eff;
}

/* ============================================
   HERO V2
   ============================================ */
.hero-v2 {
    min-height: 90vh;
    display: flex;
    align-items: center;
    background: linear-gradient(135deg, var(--bg-dark) 0%, #0d0d1a 100%);
    padding: 4rem 2rem;
}

.hero-v2 .container {
    max-width: 1400px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: center;
}

.hero-content h1 {
    font-size: 3.5rem;
    line-height: 1.2;
    margin-bottom: 1.5rem;
    background: linear-gradient(135deg, var(--primary) 0%, var(--accent-blue) 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.hero-subtitle {
    font-size: 1.5rem;
    line-height: 1.6;
    color: var(--text-secondary);
    margin-bottom: 2rem;
}

.hero-subtitle strong {
    color: var(--primary);
}

.hero-subtitle em {
    color: var(--accent-orange);
    font-style: normal;
}

.hero-cta {
    display: flex;
    gap: 1rem;
}

.btn-primary, .btn-secondary {
    padding: 1rem 2rem;
    font-size: 1.1rem;
    border-radius: 8px;
    text-decoration: none;
    transition: all 0.3s ease;
    font-weight: 600;
}

.btn-primary {
    background: var(--primary);
    color: var(--bg-dark);
}

.btn-primary:hover {
    background: var(--primary-dim);
    transform: translateY(-2px);
    box-shadow: 0 8px 20px rgba(0, 255, 136, 0.3);
}

.btn-secondary {
    background: transparent;
    color: var(--primary);
    border: 2px solid var(--primary);
}

.btn-secondary:hover {
    background: var(--primary);
    color: var(--bg-dark);
}

.hero-visual img {
    width: 100%;
    border-radius: 12px;
    box-shadow: 0 10px 40px rgba(0, 0, 0, 0.5);
}

.hero-visual .caption {
    text-align: center;
    margin-top: 1rem;
    color: var(--text-secondary);
    font-size: 0.9rem;
}

/* ============================================
   PROBLEM SECTION
   ============================================ */
.problem-section {
    padding: 6rem 2rem;
    background: var(--bg-dark);
}

.problem-section h2 {
    font-size: 3rem;
    text-align: center;
    margin-bottom: 3rem;
    color: var(--text-primary);
}

.problem-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
    max-width: 1400px;
    margin: 0 auto 4rem;
}

.problem-card {
    background: var(--bg-card);
    padding: 2.5rem;
    border-radius: 12px;
    border: 1px solid #222;
    transition: all 0.3s ease;
}

.problem-card.highlight {
    border: 2px solid var(--primary);
    background: linear-gradient(135deg, #001a0f 0%, var(--bg-card) 100%);
}

.problem-card h3 {
    font-size: 1.3rem;
    margin-bottom: 1.5rem;
    color: var(--text-secondary);
}

.problem-card .stat {
    font-size: 1.8rem;
    font-weight: 700;
    color: var(--primary);
    margin-bottom: 1rem;
}

.problem-card .detail {
    color: var(--text-secondary);
    line-height: 1.6;
}

.problem-statement {
    max-width: 900px;
    margin: 4rem auto 0;
    text-align: center;
    font-size: 1.4rem;
    line-height: 1.8;
    color: var(--text-secondary);
}

.problem-statement strong {
    color: var(--accent-orange);
    font-weight: 700;
}

/* ============================================
   SOLUTION SECTION
   ============================================ */
.solution-section {
    padding: 6rem 2rem;
    background: linear-gradient(180deg, var(--bg-dark) 0%, #0d0d1a 100%);
}

.solution-section h2 {
    font-size: 3rem;
    text-align: center;
    margin-bottom: 1.5rem;
    color: var(--text-primary);
}

.section-intro {
    text-align: center;
    font-size: 1.3rem;
    line-height: 1.8;
    color: var(--text-secondary);
    max-width: 800px;
    margin: 0 auto 4rem;
}

.section-intro strong {
    color: var(--primary);
}

.solution-demo {
    max-width: 1400px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
}

.feature-list {
    list-style: none;
    padding: 0;
}

.feature-list li {
    margin-bottom: 2.5rem;
    padding-left: 2rem;
    position: relative;
}

.feature-list li::before {
    content: "→";
    position: absolute;
    left: 0;
    color: var(--primary);
    font-size: 1.5rem;
}

.feature-list strong {
    display: block;
    font-size: 1.4rem;
    color: var(--primary);
    margin-bottom: 0.5rem;
}

.feature-list p {
    color: var(--text-secondary);
    line-height: 1.6;
}

.live-demo-box {
    background: var(--bg-card);
    padding: 2.5rem;
    border-radius: 12px;
    border: 2px solid var(--primary);
    margin-bottom: 2rem;
}

.live-demo-box h4 {
    font-size: 1.5rem;
    color: var(--primary);
    margin-bottom: 1rem;
}

.btn-demo {
    display: inline-block;
    margin-top: 1rem;
    padding: 0.8rem 1.5rem;
    background: var(--primary);
    color: var(--bg-dark);
    text-decoration: none;
    border-radius: 6px;
    font-weight: 600;
    transition: all 0.3s ease;
}

.btn-demo:hover {
    background: var(--primary-dim);
    transform: translateX(5px);
}

.tech-stack {
    background: var(--bg-card);
    padding: 2rem;
    border-radius: 12px;
    border: 1px solid #222;
}

.tech-stack h4 {
    font-size: 1.3rem;
    margin-bottom: 1rem;
    color: var(--text-secondary);
}

.tech-stack ul {
    list-style: none;
    padding: 0;
}

.tech-stack li {
    margin-bottom: 1rem;
    color: var(--text-secondary);
    line-height: 1.6;
}

.tech-stack strong {
    color: var(--primary);
}

/* ============================================
   SCALE SECTION
   ============================================ */
.scale-section {
    padding: 6rem 2rem;
    background: var(--bg-dark);
}

.scale-section h2 {
    font-size: 3rem;
    text-align: center;
    margin-bottom: 1.5rem;
    color: var(--text-primary);
}

.scale-grid {
    max-width: 1400px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2.5rem;
}

.scale-card {
    background: var(--bg-card);
    padding: 2.5rem;
    border-radius: 12px;
    border: 1px solid #222;
    transition: all 0.3s ease;
}

.scale-card:hover {
    border-color: var(--primary);
    transform: translateY(-5px);
}

.scale-icon {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.scale-card h3 {
    font-size: 1.8rem;
    margin-bottom: 1.5rem;
    color: var(--primary);
}

.scale-example {
    color: var(--text-secondary);
    line-height: 1.8;
    margin-bottom: 1.5rem;
}

.scale-ukubona {
    padding-top: 1.5rem;
    border-top: 1px solid #222;
    font-size: 0.95rem;
    line-height: 1.6;
}

.scale-ukubona strong {
    color: var(--accent-blue);
}

.scale-ukubona a {
    color: var(--primary);
    text-decoration: none;
    border-bottom: 1px solid var(--primary);
}

.scale-principle {
    max-width: 900px;
    margin: 4rem auto 0;
    text-align: center;
    font-size: 1.4rem;
    line-height: 1.8;
    color: var(--text-secondary);
}

.scale-principle strong {
    color: var(--primary);
}

/* ============================================
   PROOF SECTION
   ============================================ */
.proof-section {
    padding: 6rem 2rem;
    background: linear-gradient(180deg, #0d0d1a 0%, var(--bg-dark) 100%);
}

.proof-section h2 {
    font-size: 3rem;
    text-align: center;
    margin-bottom: 4rem;
    color: var(--text-primary);
}

.proof-grid {
    max-width: 1400px;
    margin: 0 auto 4rem;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2.5rem;
}

.proof-card {
    background: var(--bg-card);
    padding: 2.5rem;
    border-radius: 12px;
    border: 1px solid #222;
}

.proof-card h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
    color: var(--primary);
}

.proof-status {
    display: inline-block;
    padding: 0.4rem 0.8rem;
    background: rgba(0, 255, 136, 0.1);
    color: var(--primary);
    border-radius: 4px;
    font-size: 0.9rem;
    margin-bottom: 1.5rem;
    font-weight: 600;
}

.proof-card p {
    color: var(--text-secondary);
    line-height: 1.6;
    margin-bottom: 1.5rem;
}

.proof-link {
    color: var(--primary);
    text-decoration: none;
    font-weight: 600;
    border-bottom: 2px solid var(--primary);
    transition: all 0.3s ease;
}

.proof-link:hover {
    color: var(--primary-dim);
}

.proof-timeline {
    max-width: 1000px;
    margin: 4rem auto 0;
    padding: 3rem;
    background: var(--bg-card);
    border-radius: 12px;
    border: 1px solid #222;
}

.proof-timeline h3 {
    font-size: 2rem;
    text-align: center;
    margin-bottom: 2rem;
    color: var(--accent-blue);
}

.timeline {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
}

.timeline-item {
    padding: 1.5rem;
    border-left: 3px solid var(--primary);
}

.timeline-item strong {
    display: block;
    font-size: 1.3rem;
    color: var(--primary);
    margin-bottom: 0.5rem;
}

.timeline-item p {
    color: var(--text-secondary);
    line-height: 1.6;
}

/* ============================================
   COST SECTION
   ============================================ */
.cost-section {
    padding: 6rem 2rem;
    background: var(--bg-dark);
}

.cost-section h2 {
    font-size: 3rem;
    text-align: center;
    margin-bottom: 1.5rem;
    color: var(--text-primary);
}

.cost-stats {
    max-width: 1000px;
    margin: 4rem auto;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
}

.cost-stat {
    text-align: center;
    padding: 2rem;
    background: var(--bg-card);
    border-radius: 12px;
    border: 1px solid #222;
}

.stat-number {
    font-size: 2.5rem;
    font-weight: 700;
    color: var(--accent-orange);
    margin-bottom: 0.5rem;
}

.stat-label {
    color: var(--text-secondary);
    font-size: 1.1rem;
}

.cost-principle {
    max-width: 900px;
    margin: 3rem auto 0;
    text-align: center;
    font-size: 1.3rem;
    line-height: 1.8;
    color: var(--text-secondary);
}

.cost-principle strong {
    color: var(--primary);
}

.cost-attribution {
    margin-top: 2rem;
    font-style: italic;
    font-size: 1rem;
}

.cost-attribution a {
    color: var(--primary);
    text-decoration: none;
    border-bottom: 1px solid var(--primary);
}

/* ============================================
   RESPONSIVE
   ============================================ */
@media (max-width: 1024px) {
    .hero-v2 .container,
    .solution-demo {
        grid-template-columns: 1fr;
    }
    
    .problem-grid,
    .scale-grid,
    .proof-grid,
    .timeline {
        grid-template-columns: 1fr;
    }
    
    .hero-content h1 {
        font-size: 2.5rem;
    }
}
EOF

echo "✅ All new content files created!"
echo ""
echo "📁 New files:"
echo "   assets/html/home-v2-hero.html"
echo "   assets/html/home-v2-problem.html"
echo "   assets/html/home-v2-solution.html"
echo "   assets/html/home-v2-scale.html"
echo "   assets/html/home-v2-proof.html"
echo "   assets/html/home-v2-cost.html"
echo "   assets/html/header-v2.html"
echo "   assets/css/home-v2.css"
echo ""
```

Now run those commands, then let's create the **new index-v2.html**:

```bash
# New homepage that pulls it all together
cat > index-v2.html << 'EOF'
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ukubona — Digital Twins for Healthcare</title>
    
    <!-- CSS -->
    <link rel="stylesheet" href="assets/css/main.css">
    <link rel="stylesheet" href="assets/css/home-v2.css">
    
    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- HEADER -->
    <div id="header-container"></div>
    
    <!-- HERO -->
    <div id="hero-container"></div>
    
    <!-- PROBLEM -->
    <div id="problem-container"></div>
    
    <!-- SOLUTION -->
    <div id="solution-container"></div>
    
    <!-- SCALE -->
    <div id="scale-container"></div>
    
    <!-- PROOF -->
    <div id="proof-container"></div>
    
    <!-- COST -->
    <div id="cost-container"></div>
    
    <!-- FOOTER -->
    <div id="footer-container"></div>
    
    <!-- JavaScript to load sections -->
    <script>
        // Load all HTML sections
        async function loadSection(file, containerId) {
            try {
                const response = await fetch(file);
                const html = await response.text();
                document.getElementById(containerId).innerHTML = html;
            } catch (error) {
                console.error(`Error loading ${file}:`, error);
            }
        }
        
        // Load all sections
        loadSection('assets/html/header-v2.html', 'header-container');
        loadSection('assets/html/home-v2-hero.html', 'hero-container');
        loadSection('assets/html/home-v2-problem.html', 'problem-container');
        loadSection('assets/html/home-v2-solution.html', 'solution-container');
        loadSection('assets/html/home-v2-scale.html', 'scale-container');
        loadSection('assets/html/home-v2-proof.html', 'proof-container');
        loadSection('assets/html/home-v2-cost.html', 'cost-container');
        loadSection('assets/html/footer.html', 'footer-container');
        
        // Mobile nav toggle
        document.addEventListener('DOMContentLoaded', () => {
            const toggle = document.querySelector('.nav-toggle');
            const menu = document.querySelector('.nav-menu');
            
            if (toggle) {
                toggle.addEventListener('click', () => {
                    menu.classList.toggle('active');
                });
            }
        });
    </script>
</body>
</html>
EOF

echo "🚀 NEW HOMEPAGE CREATED: index-v2.html"
echo ""
echo "🔥 TO TEST:"
echo "   1. Open index-v2.html in browser"
echo "   2. Your old index.html is UNTOUCHED"
echo "   3. When ready to deploy, just rename:"
echo "      mv index.html index-old.html"
echo "      mv index-v2.html index.html"
echo ""
```

## SHIP IT:

```bash
# Run everything
chmod +x *.sh
bash tree.sh .

# Then open in browser
open index-v2.html

# Or if you're on Linux
xdg-open index-v2.html
```

Your entire old site still works. The new site is **parallel**. You can A/B test, iterate, or just go live when ready.

**What we built:**
- ✅ Clear problem statement (loss landscape)
- ✅ Concrete solution (digital twins)
- ✅ Scale demonstration (person → government)
- ✅ Proof (NHANES, Uganda, Game of Care)
- ✅ Energy honesty (kWh costs)
- ✅ 50-year timeline
- ✅ All your philosophy intact (linked from nav)

**NO FILES TOUCHED. ALL NEW. READY TO RUN.**

Let's fucking go. 🚀
## III
# FUCK YES. LET'S SYNTHESIZE THE BEST OF ALL THREE.

Looking at all three approaches, here's what each one nails:

**My approach (Claude):** 
- Narrative coherence from problem → solution → proof
- Explicit scale demonstration (Person → Government)
- Energy honesty (kWh costs)

**Gemini's approach:**
- **BRUTAL simplification** - "Stop philosophizing, start refactoring"
- The operational spine: Sensing → Modeling → Acting
- "Make SGD literal in site behavior" (interactive, not decorative)

**O's approach:**
- **CLEAN minimalist aesthetic** - no bullshit
- Perfect balance: accessible without dumbing down
- "Post-metaphor means translating narrative into metrics"

## HERE'S THE SYNTHESIS:

I'm going to create **ONE coherent system** that combines:
1. **O's clean aesthetic** (that HTML/CSS is fucking perfect)
2. **Gemini's operational clarity** (Sensing/Modeling/Acting layers)
3. **My narrative structure** (problem → algorithm → scale → proof)

Let me rebuild with this unified vision:

```bash
# UNIFIED APPROACH - Best of all three
# Clean structure (Gemini), Clean aesthetic (O), Clear narrative (Claude)

# 1. CREATE THE OPERATIONAL LAYERS
cat > assets/html/layer-sensing.html << 'EOF'
<section id="sensing" class="operational-layer">
    <div class="container">
        <div class="layer-header">
            <span class="layer-tag">Layer 1</span>
            <h2>Sensing</h2>
        </div>
        
        <div class="layer-content">
            <div class="layer-text">
                <p class="layer-principle">
                    Measurement acknowledges uncertainty.<br>
                    Data is partial. Signals are noisy.<br>
                    <strong>Perception is iterative.</strong>
                </p>
                
                <div class="layer-examples">
                    <div class="example">
                        <h4>Person</h4>
                        <p>Biomarkers, symptoms, behavioral tracking. Your body generates 10¹⁴ signals per second.</p>
                    </div>
                    <div class="example">
                        <h4>Clinic</h4>
                        <p>EHR data, lab results, outcome tracking. Pattern recognition across patient cohorts.</p>
                    </div>
                    <div class="example">
                        <h4>Ministry</h4>
                        <p>District-level prevalence, resource allocation, intervention outcomes across 127 regions.</p>
                    </div>
                </div>
            </div>
            
            <div class="layer-demo">
                <div class="demo-card">
                    <h4>Live: NHANES Data</h4>
                    <p>40,000+ participants. Real biomarkers. Interactive exploration.</p>
                    <a href="assets/html/nhanes.html" class="demo-link">Explore the data →</a>
                </div>
            </div>
        </div>
    </div>
</section>
EOF

cat > assets/html/layer-modeling.html << 'EOF'
<section id="modeling" class="operational-layer">
    <div class="container">
        <div class="layer-header">
            <span class="layer-tag">Layer 2</span>
            <h2>Modeling</h2>
        </div>
        
        <div class="layer-content">
            <div class="layer-text">
                <p class="layer-principle">
                    Every intervention is a hypothesis.<br>
                    Outcomes are gradient signals.<br>
                    <strong>Systems improve through structured iteration.</strong>
                </p>
                
                <div class="math-block">
                    <p>Reality − Model = Loss</p>
                    <p>Loss → Feedback</p>
                    <p>Feedback → Update</p>
                    <p>Update → Reduced Loss</p>
                </div>
                
                <p class="layer-detail">
                    We turn validated equations into <strong>playable scenarios</strong>.
                    Cox models, competing risks, survival curves—all interactive.
                    Adjust parameters, watch curves shift, rehearse before committing.
                </p>
            </div>
            
            <div class="layer-demo">
                <div class="demo-card">
                    <h4>Game of Care Engine</h4>
                    <p>Survival curves → rehearsable decisions. Validated equations. Real clinical data.</p>
                    <a href="assets/html/game.html" class="demo-link">Play the scenarios →</a>
                </div>
                
                <div class="ant-colony-viz">
                    <img src="assets/img/ant-colony-simulation-game-prototype-pheromone-foraging.jpg" alt="Ant colony optimization">
                    <p class="viz-caption">Stochastic exploration → Gradient detection → Collective descent</p>
                </div>
            </div>
        </div>
    </div>
</section>
EOF

cat > assets/html/layer-acting.html << 'EOF'
<section id="acting" class="operational-layer">
    <div class="container">
        <div class="layer-header">
            <span class="layer-tag">Layer 3</span>
            <h2>Acting</h2>
        </div>
        
        <div class="layer-content">
            <div class="layer-text">
                <p class="layer-principle">
                    Deployment. Pilot testing. Iteration.<br>
                    Policy without measurement is blind descent.<br>
                    <strong>Structured experimentation enables adaptive governance.</strong>
                </p>
                
                <div class="deployment-timeline">
                    <div class="timeline-stage">
                        <strong>2026-2027</strong>
                        <p>Digital twin for chronic disease. Uganda mental health dashboard deployed.</p>
                    </div>
                    <div class="timeline-stage">
                        <strong>2027-2035</strong>
                        <p>Every clinic has real-time prediction. Physicians rehearse before prescribing.</p>
                    </div>
                    <div class="timeline-stage">
                        <strong>2035-2076</strong>
                        <p>Healthcare = continuous gradient descent. Ministry dashboards track population loss surfaces.</p>
                    </div>
                </div>
            </div>
            
            <div class="layer-demo">
                <div class="demo-card highlight">
                    <h4>Uganda Depression Map</h4>
                    <p>30.2% prevalence. 127 districts. 123,859 participants. Real-time policy cartography.</p>
                    <a href="assets/html/cartography-256.html" class="demo-link">See the deployment →</a>
                </div>
            </div>
        </div>
    </div>
</section>
EOF

# 2. CREATE THE UNIFIED STYLESHEET (O's aesthetic + operational clarity)
cat > assets/css/unified.css << 'EOF'
/* ============================================
   UKUBONA UNIFIED SYSTEM
   O's aesthetic + Gemini's operational clarity
   ============================================ */

:root {
    /* O's palette - perfect, keeping it */
    --bg: #0d0f14;
    --text: #e6e9ef;
    --accent: #4cc9f0;
    --muted: #9aa3b2;
    --card: #151923;
    
    /* Additional operational colors */
    --gradient: #FF4D00;
    --success: #00ff88;
    --warning: #ffaa00;
    
    /* Spacing (Gemini's Apollonian integers) */
    --space-unit: 8px;
    --space-xs: calc(var(--space-unit) * 1);
    --space-sm: calc(var(--space-unit) * 2);
    --space-md: calc(var(--space-unit) * 3);
    --space-lg: calc(var(--space-unit) * 6);
    --space-xl: calc(var(--space-unit) * 8);
    --space-geo: calc(var(--space-unit) * 16);
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
}

body {
    background: var(--bg);
    color: var(--text);
    line-height: 1.6;
}

.container {
    max-width: 1100px;
    margin: 0 auto;
    padding: 0 var(--space-md);
}

/* ============================================
   HEADER - Minimal, operational
   ============================================ */
header {
    padding: var(--space-geo) var(--space-md);
    text-align: center;
    border-bottom: 1px solid #222;
}

header h1 {
    font-size: 2.8rem;
    letter-spacing: 1px;
    margin-bottom: var(--space-md);
}

header .tagline {
    color: var(--muted);
    font-size: 1.2rem;
    max-width: 700px;
    margin: 0 auto;
}

header .tagline strong {
    color: var(--accent);
}

/* ============================================
   NAV - Clean, functional
   ============================================ */
nav {
    display: flex;
    justify-content: center;
    gap: var(--space-lg);
    padding: var(--space-md);
    border-bottom: 1px solid #222;
    position: sticky;
    top: 0;
    background: var(--bg);
    z-index: 100;
}

nav a {
    color: var(--muted);
    text-decoration: none;
    font-size: 0.9rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: var(--accent);
}

/* ============================================
   PREMISE SECTION
   ============================================ */
.premise-section {
    padding: var(--space-geo) var(--space-md);
}

.premise-section h2 {
    font-size: 2rem;
    color: var(--accent);
    margin-bottom: var(--space-lg);
}

.premise-section p {
    font-size: 1.2rem;
    line-height: 1.8;
    margin-bottom: var(--space-md);
    color: var(--text);
}

.premise-section strong {
    color: var(--success);
}

.loss-equation {
    background: var(--card);
    border: 1px solid #222;
    border-radius: 8px;
    padding: var(--space-lg);
    margin: var(--space-xl) 0;
    text-align: center;
}

.loss-equation p {
    font-family: 'Courier New', monospace;
    font-size: 1.3rem;
    margin: var(--space-sm) 0;
    color: var(--accent);
}

.loss-equation .arrow {
    color: var(--gradient);
    font-size: 1.5rem;
}

/* ============================================
   OPERATIONAL LAYERS
   ============================================ */
.operational-layer {
    padding: var(--space-geo) var(--space-md);
    border-bottom: 1px solid #222;
}

.layer-header {
    margin-bottom: var(--space-lg);
}

.layer-tag {
    display: inline-block;
    background: var(--accent);
    color: var(--bg);
    padding: var(--space-xs) var(--space-sm);
    border-radius: 4px;
    font-size: 0.8rem;
    font-weight: 600;
    margin-bottom: var(--space-sm);
}

.layer-header h2 {
    font-size: 2.5rem;
    color: var(--text);
}

.layer-content {
    display: grid;
    grid-template-columns: 1.5fr 1fr;
    gap: var(--space-xl);
}

.layer-principle {
    font-size: 1.3rem;
    line-height: 1.8;
    color: var(--muted);
    margin-bottom: var(--space-lg);
}

.layer-principle strong {
    color: var(--accent);
}

.layer-examples {
    display: grid;
    gap: var(--space-md);
    margin-top: var(--space-lg);
}

.example {
    background: var(--card);
    padding: var(--space-md);
    border-radius: 8px;
    border-left: 3px solid var(--accent);
}

.example h4 {
    color: var(--accent);
    margin-bottom: var(--space-xs);
}

.example p {
    color: var(--muted);
    font-size: 0.95rem;
}

/* Math block - clean, functional */
.math-block {
    background: var(--card);
    border: 1px solid #333;
    border-radius: 8px;
    padding: var(--space-lg);
    margin: var(--space-lg) 0;
}

.math-block p {
    font-family: 'Courier New', monospace;
    font-size: 1.1rem;
    margin: var(--space-sm) 0;
    color: var(--text);
}

.layer-detail {
    margin-top: var(--space-lg);
    color: var(--muted);
    line-height: 1.8;
}

/* Demo cards */
.demo-card {
    background: var(--card);
    padding: var(--space-lg);
    border-radius: 8px;
    border: 1px solid #222;
    margin-bottom: var(--space-md);
}

.demo-card.highlight {
    border: 2px solid var(--success);
}

.demo-card h4 {
    color: var(--accent);
    margin-bottom: var(--space-sm);
    font-size: 1.3rem;
}

.demo-card p {
    color: var(--muted);
    margin-bottom: var(--space-md);
    line-height: 1.6;
}

.demo-link {
    display: inline-block;
    color: var(--accent);
    text-decoration: none;
    font-weight: 600;
    transition: all 0.3s ease;
    border-bottom: 2px solid transparent;
}

.demo-link:hover {
    border-bottom: 2px solid var(--accent);
    transform: translateX(5px);
}

/* Ant colony viz */
.ant-colony-viz {
    margin-top: var(--space-lg);
}

.ant-colony-viz img {
    width: 100%;
    border-radius: 8px;
    margin-bottom: var(--space-sm);
}

.viz-caption {
    text-align: center;
    color: var(--muted);
    font-size: 0.9rem;
    font-style: italic;
}

/* Deployment timeline */
.deployment-timeline {
    display: grid;
    gap: var(--space-lg);
    margin-top: var(--space-lg);
}

.timeline-stage {
    padding-left: var(--space-md);
    border-left: 3px solid var(--gradient);
}

.timeline-stage strong {
    display: block;
    color: var(--accent);
    font-size: 1.2rem;
    margin-bottom: var(--space-xs);
}

.timeline-stage p {
    color: var(--muted);
    line-height: 1.6;
}

/* ============================================
   FOOTER
   ============================================ */
footer {
    text-align: center;
    padding: var(--space-geo) var(--space-md);
    border-top: 1px solid #222;
    color: var(--muted);
    font-size: 0.9rem;
}

/* ============================================
   RESPONSIVE
   ============================================ */
@media (max-width: 768px) {
    .layer-content {
        grid-template-columns: 1fr;
    }
    
    header h1 {
        font-size: 2rem;
    }
    
    .layer-header h2 {
        font-size: 2rem;
    }
    
    nav {
        flex-wrap: wrap;
        gap: var(--space-md);
    }
}
EOF

# 3. CREATE THE UNIFIED INDEX
cat > index-unified.html << 'EOF'
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ukubona — Adaptive Systems for Health</title>
    
    <link rel="stylesheet" href="assets/css/unified.css">
    
    <!-- MathJax for equations -->
    <script>
      window.MathJax = {
        tex: {
          inlineMath: [['$', '$'], ['\\(', '\\)']],
          displayMath: [['$$','$$'], ['\\[','\\]']],
          processEscapes: true
        }
      };
    </script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
</head>
<body>

<header>
    <h1>Ukubona</h1>
    <p class="tagline">
        We build adaptive systems for health and human development.<br>
        We operate in <strong>incomplete information</strong> environments.<br>
        We reduce the gap between intention and outcome.
    </p>
</header>

<nav>
    <a href="#premise">Premise</a>
    <a href="#sensing">Sensing</a>
    <a href="#modeling">Modeling</a>
    <a href="#acting">Acting</a>
    <a href="assets/html/team.html">Team</a>
    <a href="assets/html/ukhona.html">Philosophy</a>
</nav>

<!-- PREMISE SECTION -->
<section id="premise" class="premise-section">
    <div class="container">
        <h2>Premise</h2>
        <p>
            The world is not fully visible. It arrives as signals, delays, and noise.
            Every person, household, clinic, and ministry operates with <strong>incomplete maps</strong> of reality.
        </p>
        <p>
            The difference between the map and the territory is <strong>loss</strong>.<br>
            Loss is measurable. Loss is improvable.
        </p>
        
        <div class="loss-equation">
            <p>Reality − Model = Loss</p>
            <p class="arrow">↓</p>
            <p>Loss → Feedback → Update</p>
            <p class="arrow">↓</p>
            <p>Update → Reduced Loss</p>
        </div>
        
        <p>
            Ukubona exists to reduce that gap.<br>
            We turn incomplete information into <strong>structured iteration</strong>.<br>
            We make the gradient visible.
        </p>
    </div>
</section>

<!-- OPERATIONAL LAYERS -->
<div id="sensing-container"></div>
<div id="modeling-container"></div>
<div id="acting-container"></div>

<footer>
    <p>Ukubona LLC · Adaptive Systems for Health & Human Development</p>
    <p>Kampala · Baltimore · Boston · Washington DC</p>
</footer>

<script>
    // Load operational layer sections
    async function loadSection(file, containerId) {
        try {
            const response = await fetch(file);
            const html = await response.text();
            document.getElementById(containerId).innerHTML = html;
        } catch (error) {
            console.error(`Error loading ${file}:`, error);
        }
    }
    
    loadSection('assets/html/layer-sensing.html', 'sensing-container');
    loadSection('assets/html/layer-modeling.html', 'modeling-container');
    loadSection('assets/html/layer-acting.html', 'acting-container');
</script>

</body>
</html>
EOF

echo "🔥 UNIFIED SYSTEM CREATED"
echo ""
echo "What we combined:"
echo "  ✓ O's clean aesthetic (minimal, functional)"
echo "  ✓ Gemini's operational clarity (Sensing → Modeling → Acting)"
echo "  ✓ Claude's narrative structure (problem → proof → scale)"
echo ""
echo "📁 New files:"
echo "   assets/html/layer-sensing.html"
echo "   assets/html/layer-modeling.html"
echo "   assets/html/layer-acting.html"
echo "   assets/css/unified.css"
echo "   index-unified.html"
echo ""
echo "🚀 DEPLOY:"
echo "   open index-unified.html"
echo ""
```

**THIS IS THE ONE.** 

It combines:
- **O's brutal simplicity** (no decorative bullshit)
- **Gemini's operational rigor** (Sensing/Modeling/Acting is *chef's kiss*)
- **My scale narrative** (Person → Clinic → Ministry actually shown)

The key insights from Gemini that I integrated:
1. "Make SGD literal in site behavior" - your ant colony sim becomes CENTRAL, not decorative
2. "Stop philosophizing, start refactoring" - the operational layers ARE the story
3. "Post-metaphor means translating narrative into metrics" - that's the whole premise section now

Run it. It's clean. It's coherent. It's operational.

## IV
# GROK'S APPROACH IS ACTUALLY THE MISSING PIECE

Looking at Grok's implementation plan, here's what's **fucking brilliant** about it:

## What Grok Nails That We All Missed:

1. **The 4-move loop is the ACTUAL navigation structure**
   - See, blindly → Forage, stochastically → Rehearse, consequentially → Descend
   - This IS your product taxonomy
   - This IS your mental model
   - This IS the user journey

2. **"Works at every scale" should be a VISUAL MODULE, not buried prose**
   - Person • Household • Clinic • Ministry
   - Should be clickable, expandable, or at minimum a clear grid

3. **The framework page solves the "what the fuck does this company actually do" problem**
   - Right now someone lands on your site and sees philosophy + scattered demos
   - They need ONE PAGE that says: "Here's the system. Here's how it works. Here's proof."

4. **The one-sentence mission is PERFECT:**
   > "Ukubona builds the meta-cognitive layer that lets every scale of human organization run stochastic gradient descent on its own health outcomes when the full gradient is unknowable."
   
   That's it. That's the whole company.

## HERE'S THE SYNTHESIS OF ALL FOUR APPROACHES:

Let me create **the final unified version** that combines:
- **O's aesthetic** (clean, minimal, functional)
- **Gemini's operational rigor** (Sensing/Modeling/Acting)
- **Claude's narrative arc** (problem → algorithm → proof)
- **Grok's structural clarity** (the 4-move loop IS the site architecture)

```bash
# THE FINAL SYNTHESIS - All four minds combined

# 1. THE 4-MOVE FRAMEWORK PAGE (Grok's insight)
cat > assets/html/framework.html << 'EOF'
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Framework — Ukubona</title>
    <link rel="stylesheet" href="../css/unified.css">
</head>
<body>

<header>
    <h1>The Ukubona Framework</h1>
    <p class="tagline">
        The loss landscape is real. Every human system (body, family, clinic, ministry)<br>
        is running stochastic gradient descent on an unknowable surface.<br>
        <strong>The map is never the territory. So we operate anyway.</strong>
    </p>
</header>

<nav>
    <a href="../../index-unified.html">Home</a>
    <a href="#moves">The 4 Moves</a>
    <a href="#scales">Scales</a>
    <a href="#products">Products</a>
    <a href="team.html">Team</a>
</nav>

<section id="moves" class="framework-section">
    <div class="container">
        <h2>The 4 Operational Moves</h2>
        <p class="section-intro">Same algorithm at every scale. Different loss functions.</p>
        
        <div class="moves-grid">
            <div class="move-card">
                <div class="move-number">1</div>
                <h3>See, blindly (UKB)</h3>
                <p>
                    Estimate the local gradient from whatever data exist + counterfactual simulation.
                    Your digital twin is the blind scout sweeping the loss surface right now.
                </p>
                <div class="move-example">
                    <strong>Technical:</strong> Sensing layer. NHANES biomarkers → survival curves.
                </div>
            </div>
            
            <div class="move-card">
                <div class="move-number">2</div>
                <h3>Forage, stochastically (UB)</h3>
                <p>
                    High-variance exploration. Run thousands of parallel futures so the system
                    can discover paths no linear plan would ever find.
                </p>
                <div class="move-example">
                    <strong>Technical:</strong> Monte Carlo simulation. Policy search. A/B testing at scale.
                </div>
            </div>
            
            <div class="move-card">
                <div class="move-number">3</div>
                <h3>Rehearse, consequentially</h3>
                <p>
                    Play the full trajectory with real stakes attached — but zero irreversible cost.
                    Watch money, health, regret, and coordination cost cascade across time.
                </p>
                <div class="move-example">
                    <strong>Technical:</strong> Interactive survival models. Game of Care engine.
                </div>
            </div>
            
            <div class="move-card">
                <div class="move-number">4</div>
                <h3>Descend (UI)</h3>
                <p>
                    Once a better direction is visible, linearize and exploit.
                    Turn the pheromone trail into protocol, dashboard, workflow, policy.
                </p>
                <div class="move-example">
                    <strong>Technical:</strong> Clinical decision support. Ministry dashboards. DHIS2 integration.
                </div>
            </div>
        </div>
    </div>
</section>

<section id="scales" class="framework-section scales-section">
    <div class="container">
        <h2>Scales of Application</h2>
        <p class="section-intro">Same 4 moves. Different substrates. Different loss functions.</p>
        
        <div class="scales-grid">
            <div class="scale-card">
                <div class="scale-icon">🧬</div>
                <h3>Person</h3>
                <p class="scale-description">
                    Your body is the terrain. We give you a personal digital twin so you can
                    see absolute risk, forage untested treatment sequences, and rehearse
                    the next 5 years of your life before you live them.
                </p>
                <div class="scale-example">
                    <strong>Example:</strong> "Should I start this medication? What if I don't? What about surgery?"
                    <a href="nhanes.html">→ Try the model</a>
                </div>
            </div>
            
            <div class="scale-card">
                <div class="scale-icon">🏠</div>
                <h3>Household</h3>
                <p class="scale-description">
                    One person's gradient affects everyone. Rehearse cascading impacts
                    across family members, finances, and time.
                </p>
                <div class="scale-example">
                    <strong>Example:</strong> "If Mum starts dialysis, what happens to Dad's retirement,
                    the kids' school fees, and family mental health?"
                </div>
            </div>
            
            <div class="scale-card">
                <div class="scale-icon">🏥</div>
                <h3>Firm (Clinic · Hospital · School)</h3>
                <p class="scale-description">
                    Rehearse triage pathways, staffing, outbreak response,
                    wellness policies before rollout.
                </p>
                <div class="scale-example">
                    <strong>Example:</strong> Protocol optimization. Resource allocation under uncertainty.
                    <a href="game.html">→ Game of Care</a>
                </div>
            </div>
            
            <div class="scale-card">
                <div class="scale-icon">🗺️</div>
                <h3>Government (Ministry of Health)</h3>
                <p class="scale-description">
                    National loss surface: DALYs, budget, equity. Real-time loss map from DHIS2 + surveys,
                    stochastic foraging across intervention packages, rehearsal before policy becomes law.
                </p>
                <div class="scale-example">
                    <strong>Live:</strong> Uganda Depression Map — 127 districts, 30.2% prevalence, policy simulation.
                    <a href="cartography-256.html">→ See the map</a>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="products" class="framework-section products-section">
    <div class="container">
        <h2>How the Products Map to the Moves</h2>
        
        <div class="product-mapping">
            <div class="mapping-item">
                <div class="product-name">Personalized Risk Models</div>
                <div class="arrow">→</div>
                <div class="move-name">See, blindly</div>
            </div>
            
            <div class="mapping-item">
                <div class="product-name">Game of Care</div>
                <div class="arrow">→</div>
                <div class="move-name">Forage + Rehearse</div>
            </div>
            
            <div class="mapping-item">
                <div class="product-name">Health Infrastructure</div>
                <div class="arrow">→</div>
                <div class="move-name">Descend</div>
            </div>
        </div>
        
        <div class="mission-statement">
            <h3>One-Sentence Mission</h3>
            <p>
                Ukubona builds the <strong>meta-cognitive layer</strong> that lets every scale
                of human organization run stochastic gradient descent on its own health outcomes
                when the full gradient is unknowable.
            </p>
        </div>
    </div>
</section>

<footer>
    <p>See, blindly • Forage, stochastically • Rehearse, consequentially • Descend</p>
    <p><a href="team.html">Meet the scouts who are building it →</a></p>
</footer>

</body>
</html>
EOF

# 2. ENHANCED UNIFIED CSS (adding framework styles)
cat >> assets/css/unified.css << 'EOF'

/* ============================================
   FRAMEWORK PAGE STYLES
   ============================================ */

.framework-section {
    padding: var(--space-geo) var(--space-md);
    border-bottom: 1px solid #222;
}

.section-intro {
    text-align: center;
    font-size: 1.2rem;
    color: var(--muted);
    margin-bottom: var(--space-xl);
}

/* The 4 Moves Grid */
.moves-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: var(--space-lg);
    max-width: 1200px;
    margin: 0 auto;
}

.move-card {
    background: var(--card);
    padding: var(--space-lg);
    border-radius: 8px;
    border: 1px solid #222;
    position: relative;
}

.move-number {
    position: absolute;
    top: var(--space-md);
    right: var(--space-md);
    width: 50px;
    height: 50px;
    background: var(--accent);
    color: var(--bg);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.5rem;
    font-weight: 700;
}

.move-card h3 {
    font-size: 1.5rem;
    color: var(--accent);
    margin-bottom: var(--space-md);
    padding-right: 60px;
}

.move-card p {
    color: var(--text);
    line-height: 1.7;
    margin-bottom: var(--space-md);
}

.move-example {
    background: rgba(76, 201, 240, 0.05);
    padding: var(--space-sm);
    border-radius: 4px;
    border-left: 3px solid var(--accent);
    font-size: 0.9rem;
}

.move-example strong {
    color: var(--accent);
}

/* Scales Grid */
.scales-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: var(--space-lg);
    max-width: 1200px;
    margin: 0 auto;
}

.scale-card {
    background: var(--card);
    padding: var(--space-lg);
    border-radius: 8px;
    border: 1px solid #222;
    transition: all 0.3s ease;
}

.scale-card:hover {
    border-color: var(--accent);
    transform: translateY(-5px);
}

.scale-icon {
    font-size: 3rem;
    margin-bottom: var(--space-md);
}

.scale-card h3 {
    font-size: 1.5rem;
    color: var(--accent);
    margin-bottom: var(--space-sm);
}

.scale-description {
    color: var(--text);
    line-height: 1.7;
    margin-bottom: var(--space-md);
}

.scale-example {
    background: rgba(255, 77, 0, 0.05);
    padding: var(--space-sm);
    border-radius: 4px;
    border-left: 3px solid var(--gradient);
    font-size: 0.9rem;
}

.scale-example strong {
    color: var(--gradient);
    display: block;
    margin-bottom: var(--space-xs);
}

.scale-example a {
    color: var(--accent);
    text-decoration: none;
    font-weight: 600;
}

/* Product Mapping */
.product-mapping {
    max-width: 800px;
    margin: 0 auto var(--space-xl);
}

.mapping-item {
    display: grid;
    grid-template-columns: 1fr auto 1fr;
    align-items: center;
    gap: var(--space-md);
    padding: var(--space-md);
    background: var(--card);
    border-radius: 8px;
    margin-bottom: var(--space-md);
    border: 1px solid #222;
}

.product-name {
    text-align: right;
    font-weight: 600;
    color: var(--text);
}

.arrow {
    color: var(--accent);
    font-size: 1.5rem;
}

.move-name {
    color: var(--accent);
    font-weight: 600;
}

/* Mission Statement */
.mission-statement {
    max-width: 800px;
    margin: var(--space-xl) auto 0;
    text-align: center;
    background: var(--card);
    padding: var(--space-xl);
    border-radius: 8px;
    border: 2px solid var(--success);
}

.mission-statement h3 {
    color: var(--success);
    margin-bottom: var(--space-md);
    font-size: 1.3rem;
}

.mission-statement p {
    font-size: 1.2rem;
    line-height: 1.8;
    color: var(--text);
}

.mission-statement strong {
    color: var(--accent);
}

/* Responsive */
@media (max-width: 768px) {
    .moves-grid,
    .scales-grid {
        grid-template-columns: 1fr;
    }
    
    .mapping-item {
        grid-template-columns: 1fr;
        text-align: center;
    }
    
    .product-name {
        text-align: center;
    }
}
EOF

# 3. UPDATE INDEX-UNIFIED TO LINK TO FRAMEWORK
cat > index-unified-v2.html << 'EOF'
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ukubona — Adaptive Systems for Health</title>
    <link rel="stylesheet" href="assets/css/unified.css">
</head>
<body>

<header>
    <h1>Ukubona</h1>
    <p class="tagline">
        We build adaptive systems for health and human development.<br>
        We operate in <strong>incomplete information</strong> environments.<br>
        We reduce the gap between intention and outcome.
    </p>
</header>

<nav>
    <a href="#premise">Premise</a>
    <a href="assets/html/framework.html">🧭 Framework</a>
    <a href="#sensing">Sensing</a>
    <a href="#modeling">Modeling</a>
    <a href="#acting">Acting</a>
    <a href="assets/html/team.html">Team</a>
    <a href="assets/html/ukhona.html">Philosophy</a>
</nav>

<section id="premise" class="premise-section">
    <div class="container">
        <h2>Premise</h2>
        <p>
            The world is not fully visible. It arrives as signals, delays, and noise.
            Every person, household, clinic, and ministry operates with <strong>incomplete maps</strong> of reality.
        </p>
        <p>
            The difference between the map and the territory is <strong>loss</strong>.<br>
            Loss is measurable. Loss is improvable.
        </p>
        
        <div class="loss-equation">
            <p>Reality − Model = Loss</p>
            <p class="arrow">↓</p>
            <p>Loss → Feedback → Update</p>
            <p class="arrow">↓</p>
            <p>Update → Reduced Loss</p>
        </div>
        
        <p>
            Ukubona exists to reduce that gap.<br>
            We turn incomplete information into <strong>structured iteration</strong>.
        </p>
        
        <div style="text-align: center; margin-top: var(--space-xl);">
            <h3>The Ukubona Framework</h3>
            <p>We don't have the full gradient. We never will.<br>
            So we <strong>see blindly • forage stochastically • rehearse consequentially • descend</strong>.</p>
            <p><a href="assets/html/framework.html" style="color: var(--accent); font-weight: 600; font-size: 1.1rem;">
                Read the operational framework →
            </a></p>
            
            <h3 style="margin-top: var(--space-lg);">Works at every scale</h3>
            <p style="font-size: 1.2rem; color: var(--accent);">
                Person • Household • Clinic/Hospital/School • Ministry of Health
            </p>
        </div>
    </div>
</section>

<div id="sensing-container"></div>
<div id="modeling-container"></div>
<div id="acting-container"></div>

<footer>
    <p>See, blindly • Forage, stochastically • Rehearse, consequentially • Descend</p>
    <p>Ukubona LLC · Adaptive Systems for Health & Human Development</p>
    <p>Kampala · Baltimore · Boston · Washington DC</p>
</footer>

<script>
    async function loadSection(file, containerId) {
        try {
            const response = await fetch(file);
            const html = await response.text();
            document.getElementById(containerId).innerHTML = html;
        } catch (error) {
            console.error(`Error loading ${file}:`, error);
        }
    }
    
    loadSection('assets/html/layer-sensing.html', 'sensing-container');
    loadSection('assets/html/layer-modeling.html', 'modeling-container');
    loadSection('assets/html/layer-acting.html', 'acting-container');
</script>

</body>
</html>
EOF

echo "🚀 FINAL SYNTHESIS COMPLETE"
echo ""
echo "What we combined from all 4 LLMs:"
echo "  ✓ O (ChatGPT): Clean aesthetic, no bullshit"
echo "  ✓ Gemini: Operational clarity (Sensing/Modeling/Acting)"
echo "  ✓ Claude: Narrative structure (problem → proof)"
echo "  ✓ Grok: The 4-move loop IS the architecture"
echo ""
echo "📁 New/Updated files:"
echo "   assets/html/framework.html (THE KEY PAGE)"
echo "   assets/css/unified.css (enhanced)"
echo "   index-unified-v2.html (links to framework)"
echo ""
echo "🎯 CRITICAL INSIGHT FROM GROK:"
echo "   The framework page answers: 'What does this company actually do?'"
echo "   See → Forage → Rehearse → Descend"
echo "   Person → Household → Firm → Government"
echo ""
echo "   THIS is the missing coherence piece."
echo ""
echo "🔥 DEPLOY:"
echo "   open index-unified-v2.html"
echo "   open assets/html/framework.html"
echo ""
```

**GROK'S KEY CONTRIBUTION:**

The framework page is the **rosetta stone** that translates between:
- Your philosophy (SGD, loss landscapes, ants)
- Your products (Risk Models, Game of Care, Infrastructure)
- Your scales (Person → Government)
- Your operational moves (See → Forage → Rehearse → Descend)

Without this page, visitors have to piece it together themselves. **With it, it's instant clarity.**

This is the final piece. Run it. 🚀
## V

Looks like we'll go with `A IV`

# YES. ONE SCRIPT. DONE.

```bash
cat > run.sh << 'EOF'
#!/bin/bash

echo "🚀 UKUBONA UNIFIED DEPLOYMENT"
echo "================================"
echo ""

# Create the operational layer HTML files
echo "📄 Creating operational layers..."

cat > assets/html/layer-sensing.html << 'SENSING'
<section id="sensing" class="operational-layer">
    <div class="container">
        <div class="layer-header">
            <span class="layer-tag">Layer 1</span>
            <h2>Sensing</h2>
        </div>
        
        <div class="layer-content">
            <div class="layer-text">
                <p class="layer-principle">
                    Measurement acknowledges uncertainty.<br>
                    Data is partial. Signals are noisy.<br>
                    <strong>Perception is iterative.</strong>
                </p>
                
                <div class="layer-examples">
                    <div class="example">
                        <h4>Person</h4>
                        <p>Biomarkers, symptoms, behavioral tracking. Your body generates 10¹⁴ signals per second.</p>
                    </div>
                    <div class="example">
                        <h4>Clinic</h4>
                        <p>EHR data, lab results, outcome tracking. Pattern recognition across patient cohorts.</p>
                    </div>
                    <div class="example">
                        <h4>Ministry</h4>
                        <p>District-level prevalence, resource allocation, intervention outcomes across 127 regions.</p>
                    </div>
                </div>
            </div>
            
            <div class="layer-demo">
                <div class="demo-card">
                    <h4>Live: NHANES Data</h4>
                    <p>40,000+ participants. Real biomarkers. Interactive exploration.</p>
                    <a href="assets/html/nhanes.html" class="demo-link">Explore the data →</a>
                </div>
            </div>
        </div>
    </div>
</section>
SENSING

cat > assets/html/layer-modeling.html << 'MODELING'
<section id="modeling" class="operational-layer">
    <div class="container">
        <div class="layer-header">
            <span class="layer-tag">Layer 2</span>
            <h2>Modeling</h2>
        </div>
        
        <div class="layer-content">
            <div class="layer-text">
                <p class="layer-principle">
                    Every intervention is a hypothesis.<br>
                    Outcomes are gradient signals.<br>
                    <strong>Systems improve through structured iteration.</strong>
                </p>
                
                <div class="math-block">
                    <p>Reality − Model = Loss</p>
                    <p>Loss → Feedback</p>
                    <p>Feedback → Update</p>
                    <p>Update → Reduced Loss</p>
                </div>
                
                <p class="layer-detail">
                    We turn validated equations into <strong>playable scenarios</strong>.
                    Cox models, competing risks, survival curves—all interactive.
                    Adjust parameters, watch curves shift, rehearse before committing.
                </p>
            </div>
            
            <div class="layer-demo">
                <div class="demo-card">
                    <h4>Game of Care Engine</h4>
                    <p>Survival curves → rehearsable decisions. Validated equations. Real clinical data.</p>
                    <a href="assets/html/game.html" class="demo-link">Play the scenarios →</a>
                </div>
                
                <div class="ant-colony-viz">
                    <img src="assets/img/ant-colony-simulation-game-prototype-pheromone-foraging.jpg" alt="Ant colony optimization">
                    <p class="viz-caption">Stochastic exploration → Gradient detection → Collective descent</p>
                </div>
            </div>
        </div>
    </div>
</section>
MODELING

cat > assets/html/layer-acting.html << 'ACTING'
<section id="acting" class="operational-layer">
    <div class="container">
        <div class="layer-header">
            <span class="layer-tag">Layer 3</span>
            <h2>Acting</h2>
        </div>
        
        <div class="layer-content">
            <div class="layer-text">
                <p class="layer-principle">
                    Deployment. Pilot testing. Iteration.<br>
                    Policy without measurement is blind descent.<br>
                    <strong>Structured experimentation enables adaptive governance.</strong>
                </p>
                
                <div class="deployment-timeline">
                    <div class="timeline-stage">
                        <strong>2026-2027</strong>
                        <p>Digital twin for chronic disease. Uganda mental health dashboard deployed.</p>
                    </div>
                    <div class="timeline-stage">
                        <strong>2027-2035</strong>
                        <p>Every clinic has real-time prediction. Physicians rehearse before prescribing.</p>
                    </div>
                    <div class="timeline-stage">
                        <strong>2035-2076</strong>
                        <p>Healthcare = continuous gradient descent. Ministry dashboards track population loss surfaces.</p>
                    </div>
                </div>
            </div>
            
            <div class="layer-demo">
                <div class="demo-card highlight">
                    <h4>Uganda Depression Map</h4>
                    <p>30.2% prevalence. 127 districts. 123,859 participants. Real-time policy cartography.</p>
                    <a href="assets/html/cartography-256.html" class="demo-link">See the deployment →</a>
                </div>
            </div>
        </div>
    </div>
</section>
ACTING

# Create the framework page
echo "📄 Creating framework page..."

cat > assets/html/framework.html << 'FRAMEWORK'
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Framework — Ukubona</title>
    <link rel="stylesheet" href="../css/unified.css">
</head>
<body>

<header>
    <h1>The Ukubona Framework</h1>
    <p class="tagline">
        The loss landscape is real. Every human system (body, family, clinic, ministry)<br>
        is running stochastic gradient descent on an unknowable surface.<br>
        <strong>The map is never the territory. So we operate anyway.</strong>
    </p>
</header>

<nav>
    <a href="../../index-unified.html">Home</a>
    <a href="#moves">The 4 Moves</a>
    <a href="#scales">Scales</a>
    <a href="#products">Products</a>
    <a href="team.html">Team</a>
</nav>

<section id="moves" class="framework-section">
    <div class="container">
        <h2>The 4 Operational Moves</h2>
        <p class="section-intro">Same algorithm at every scale. Different loss functions.</p>
        
        <div class="moves-grid">
            <div class="move-card">
                <div class="move-number">1</div>
                <h3>See, blindly (UKB)</h3>
                <p>
                    Estimate the local gradient from whatever data exist + counterfactual simulation.
                    Your digital twin is the blind scout sweeping the loss surface right now.
                </p>
                <div class="move-example">
                    <strong>Technical:</strong> Sensing layer. NHANES biomarkers → survival curves.
                </div>
            </div>
            
            <div class="move-card">
                <div class="move-number">2</div>
                <h3>Forage, stochastically (UB)</h3>
                <p>
                    High-variance exploration. Run thousands of parallel futures so the system
                    can discover paths no linear plan would ever find.
                </p>
                <div class="move-example">
                    <strong>Technical:</strong> Monte Carlo simulation. Policy search. A/B testing at scale.
                </div>
            </div>
            
            <div class="move-card">
                <div class="move-number">3</div>
                <h3>Rehearse, consequentially</h3>
                <p>
                    Play the full trajectory with real stakes attached — but zero irreversible cost.
                    Watch money, health, regret, and coordination cost cascade across time.
                </p>
                <div class="move-example">
                    <strong>Technical:</strong> Interactive survival models. Game of Care engine.
                </div>
            </div>
            
            <div class="move-card">
                <div class="move-number">4</div>
                <h3>Descend (UI)</h3>
                <p>
                    Once a better direction is visible, linearize and exploit.
                    Turn the pheromone trail into protocol, dashboard, workflow, policy.
                </p>
                <div class="move-example">
                    <strong>Technical:</strong> Clinical decision support. Ministry dashboards. DHIS2 integration.
                </div>
            </div>
        </div>
    </div>
</section>

<section id="scales" class="framework-section scales-section">
    <div class="container">
        <h2>Scales of Application</h2>
        <p class="section-intro">Same 4 moves. Different substrates. Different loss functions.</p>
        
        <div class="scales-grid">
            <div class="scale-card">
                <div class="scale-icon">🧬</div>
                <h3>Person</h3>
                <p class="scale-description">
                    Your body is the terrain. We give you a personal digital twin so you can
                    see absolute risk, forage untested treatment sequences, and rehearse
                    the next 5 years of your life before you live them.
                </p>
                <div class="scale-example">
                    <strong>Example:</strong> "Should I start this medication? What if I don't? What about surgery?"
                    <a href="nhanes.html">→ Try the model</a>
                </div>
            </div>
            
            <div class="scale-card">
                <div class="scale-icon">🏠</div>
                <h3>Household</h3>
                <p class="scale-description">
                    One person's gradient affects everyone. Rehearse cascading impacts
                    across family members, finances, and time.
                </p>
                <div class="scale-example">
                    <strong>Example:</strong> "If Mum starts dialysis, what happens to Dad's retirement,
                    the kids' school fees, and family mental health?"
                </div>
            </div>
            
            <div class="scale-card">
                <div class="scale-icon">🏥</div>
                <h3>Firm (Clinic · Hospital · School)</h3>
                <p class="scale-description">
                    Rehearse triage pathways, staffing, outbreak response,
                    wellness policies before rollout.
                </p>
                <div class="scale-example">
                    <strong>Example:</strong> Protocol optimization. Resource allocation under uncertainty.
                    <a href="game.html">→ Game of Care</a>
                </div>
            </div>
            
            <div class="scale-card">
                <div class="scale-icon">🗺️</div>
                <h3>Government (Ministry of Health)</h3>
                <p class="scale-description">
                    National loss surface: DALYs, budget, equity. Real-time loss map from DHIS2 + surveys,
                    stochastic foraging across intervention packages, rehearsal before policy becomes law.
                </p>
                <div class="scale-example">
                    <strong>Live:</strong> Uganda Depression Map — 127 districts, 30.2% prevalence, policy simulation.
                    <a href="cartography-256.html">→ See the map</a>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="products" class="framework-section products-section">
    <div class="container">
        <h2>How the Products Map to the Moves</h2>
        
        <div class="product-mapping">
            <div class="mapping-item">
                <div class="product-name">Personalized Risk Models</div>
                <div class="arrow">→</div>
                <div class="move-name">See, blindly</div>
            </div>
            
            <div class="mapping-item">
                <div class="product-name">Game of Care</div>
                <div class="arrow">→</div>
                <div class="move-name">Forage + Rehearse</div>
            </div>
            
            <div class="mapping-item">
                <div class="product-name">Health Infrastructure</div>
                <div class="arrow">→</div>
                <div class="move-name">Descend</div>
            </div>
        </div>
        
        <div class="mission-statement">
            <h3>One-Sentence Mission</h3>
            <p>
                Ukubona builds the <strong>meta-cognitive layer</strong> that lets every scale
                of human organization run stochastic gradient descent on its own health outcomes
                when the full gradient is unknowable.
            </p>
        </div>
    </div>
</section>

<footer>
    <p>See, blindly • Forage, stochastically • Rehearse, consequentially • Descend</p>
    <p><a href="team.html">Meet the scouts who are building it →</a></p>
</footer>

</body>
</html>
FRAMEWORK

# Create the unified CSS
echo "🎨 Creating unified stylesheet..."

cat > assets/css/unified.css << 'CSS'
/* ============================================
   UKUBONA UNIFIED SYSTEM
   ============================================ */

:root {
    --bg: #0d0f14;
    --text: #e6e9ef;
    --accent: #4cc9f0;
    --muted: #9aa3b2;
    --card: #151923;
    --gradient: #FF4D00;
    --success: #00ff88;
    
    --space-unit: 8px;
    --space-xs: calc(var(--space-unit) * 1);
    --space-sm: calc(var(--space-unit) * 2);
    --space-md: calc(var(--space-unit) * 3);
    --space-lg: calc(var(--space-unit) * 6);
    --space-xl: calc(var(--space-unit) * 8);
    --space-geo: calc(var(--space-unit) * 16);
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
}

body {
    background: var(--bg);
    color: var(--text);
    line-height: 1.6;
}

.container {
    max-width: 1100px;
    margin: 0 auto;
    padding: 0 var(--space-md);
}

header {
    padding: var(--space-geo) var(--space-md);
    text-align: center;
    border-bottom: 1px solid #222;
}

header h1 {
    font-size: 2.8rem;
    letter-spacing: 1px;
    margin-bottom: var(--space-md);
}

header .tagline {
    color: var(--muted);
    font-size: 1.2rem;
    max-width: 700px;
    margin: 0 auto;
}

header .tagline strong {
    color: var(--accent);
}

nav {
    display: flex;
    justify-content: center;
    gap: var(--space-lg);
    padding: var(--space-md);
    border-bottom: 1px solid #222;
    position: sticky;
    top: 0;
    background: var(--bg);
    z-index: 100;
}

nav a {
    color: var(--muted);
    text-decoration: none;
    font-size: 0.9rem;
    transition: color 0.3s ease;
}

nav a:hover {
    color: var(--accent);
}

.premise-section {
    padding: var(--space-geo) var(--space-md);
}

.premise-section h2 {
    font-size: 2rem;
    color: var(--accent);
    margin-bottom: var(--space-lg);
}

.premise-section p {
    font-size: 1.2rem;
    line-height: 1.8;
    margin-bottom: var(--space-md);
    color: var(--text);
}

.premise-section strong {
    color: var(--success);
}

.loss-equation {
    background: var(--card);
    border: 1px solid #222;
    border-radius: 8px;
    padding: var(--space-lg);
    margin: var(--space-xl) 0;
    text-align: center;
}

.loss-equation p {
    font-family: 'Courier New', monospace;
    font-size: 1.3rem;
    margin: var(--space-sm) 0;
    color: var(--accent);
}

.loss-equation .arrow {
    color: var(--gradient);
    font-size: 1.5rem;
}

.operational-layer {
    padding: var(--space-geo) var(--space-md);
    border-bottom: 1px solid #222;
}

.layer-header {
    margin-bottom: var(--space-lg);
}

.layer-tag {
    display: inline-block;
    background: var(--accent);
    color: var(--bg);
    padding: var(--space-xs) var(--space-sm);
    border-radius: 4px;
    font-size: 0.8rem;
    font-weight: 600;
    margin-bottom: var(--space-sm);
}

.layer-header h2 {
    font-size: 2.5rem;
    color: var(--text);
}

.layer-content {
    display: grid;
    grid-template-columns: 1.5fr 1fr;
    gap: var(--space-xl);
}

.layer-principle {
    font-size: 1.3rem;
    line-height: 1.8;
    color: var(--muted);
    margin-bottom: var(--space-lg);
}

.layer-principle strong {
    color: var(--accent);
}

.layer-examples {
    display: grid;
    gap: var(--space-md);
    margin-top: var(--space-lg);
}

.example {
    background: var(--card);
    padding: var(--space-md);
    border-radius: 8px;
    border-left: 3px solid var(--accent);
}

.example h4 {
    color: var(--accent);
    margin-bottom: var(--space-xs);
}

.example p {
    color: var(--muted);
    font-size: 0.95rem;
}

.math-block {
    background: var(--card);
    border: 1px solid #333;
    border-radius: 8px;
    padding: var(--space-lg);
    margin: var(--space-lg) 0;
}

.math-block p {
    font-family: 'Courier New', monospace;
    font-size: 1.1rem;
    margin: var(--space-sm) 0;
    color: var(--text);
}

.layer-detail {
    margin-top: var(--space-lg);
    color: var(--muted);
    line-height: 1.8;
}

.demo-card {
    background: var(--card);
    padding: var(--space-lg);
    border-radius: 8px;
    border: 1px solid #222;
    margin-bottom: var(--space-md);
}

.demo-card.highlight {
    border: 2px solid var(--success);
}

.demo-card h4 {
    color: var(--accent);
    margin-bottom: var(--space-sm);
    font-size: 1.3rem;
}

.demo-card p {
    color: var(--muted);
    margin-bottom: var(--space-md);
    line-height: 1.6;
}

.demo-link {
    display: inline-block;
    color: var(--accent);
    text-decoration: none;
    font-weight: 600;
    transition: all 0.3s ease;
    border-bottom: 2px solid transparent;
}

.demo-link:hover {
    border-bottom: 2px solid var(--accent);
    transform: translateX(5px);
}

.ant-colony-viz {
    margin-top: var(--space-lg);
}

.ant-colony-viz img {
    width: 100%;
    border-radius: 8px;
    margin-bottom: var(--space-sm);
}

.viz-caption {
    text-align: center;
    color: var(--muted);
    font-size: 0.9rem;
    font-style: italic;
}

.deployment-timeline {
    display: grid;
    gap: var(--space-lg);
    margin-top: var(--space-lg);
}

.timeline-stage {
    padding-left: var(--space-md);
    border-left: 3px solid var(--gradient);
}

.timeline-stage strong {
    display: block;
    color: var(--accent);
    font-size: 1.2rem;
    margin-bottom: var(--space-xs);
}

.timeline-stage p {
    color: var(--muted);
    line-height: 1.6;
}

/* Framework page styles */
.framework-section {
    padding: var(--space-geo) var(--space-md);
    border-bottom: 1px solid #222;
}

.section-intro {
    text-align: center;
    font-size: 1.2rem;
    color: var(--muted);
    margin-bottom: var(--space-xl);
}

.moves-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: var(--space-lg);
    max-width: 1200px;
    margin: 0 auto;
}

.move-card {
    background: var(--card);
    padding: var(--space-lg);
    border-radius: 8px;
    border: 1px solid #222;
    position: relative;
}

.move-number {
    position: absolute;
    top: var(--space-md);
    right: var(--space-md);
    width: 50px;
    height: 50px;
    background: var(--accent);
    color: var(--bg);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.5rem;
    font-weight: 700;
}

.move-card h3 {
    font-size: 1.5rem;
    color: var(--accent);
    margin-bottom: var(--space-md);
    padding-right: 60px;
}

.move-card p {
    color: var(--text);
    line-height: 1.7;
    margin-bottom: var(--space-md);
}

.move-example {
    background: rgba(76, 201, 240, 0.05);
    padding: var(--space-sm);
    border-radius: 4px;
    border-left: 3px solid var(--accent);
    font-size: 0.9rem;
}

.move-example strong {
    color: var(--accent);
}

.scales-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: var(--space-lg);
    max-width: 1200px;
    margin: 0 auto;
}

.scale-card {
    background: var(--card);
    padding: var(--space-lg);
    border-radius: 8px;
    border: 1px solid #222;
    transition: all 0.3s ease;
}

.scale-card:hover {
    border-color: var(--accent);
    transform: translateY(-5px);
}

.scale-icon {
    font-size: 3rem;
    margin-bottom: var(--space-md);
}

.scale-card h3 {
    font-size: 1.5rem;
    color: var(--accent);
    margin-bottom: var(--space-sm);
}

.scale-description {
    color: var(--text);
    line-height: 1.7;
    margin-bottom: var(--space-md);
}

.scale-example {
    background: rgba(255, 77, 0, 0.05);
    padding: var(--space-sm);
    border-radius: 4px;
    border-left: 3px solid var(--gradient);
    font-size: 0.9rem;
}

.scale-example strong {
    color: var(--gradient);
    display: block;
    margin-bottom: var(--space-xs);
}

.scale-example a {
    color: var(--accent);
    text-decoration: none;
    font-weight: 600;
}

.product-mapping {
    max-width: 800px;
    margin: 0 auto var(--space-xl);
}

.mapping-item {
    display: grid;
    grid-template-columns: 1fr auto 1fr;
    align-items: center;
    gap: var(--space-md);
    padding: var(--space-md);
    background: var(--card);
    border-radius: 8px;
    margin-bottom: var(--space-md);
    border: 1px solid #222;
}

.product-name {
    text-align: right;
    font-weight: 600;
    color: var(--text);
}

.arrow {
    color: var(--accent);
    font-size: 1.5rem;
}

.move-name {
    color: var(--accent);
    font-weight: 600;
}

.mission-statement {
    max-width: 800px;
    margin: var(--space-xl) auto 0;
    text-align: center;
    background: var(--card);
    padding: var(--space-xl);
    border-radius: 8px;
    border: 2px solid var(--success);
}

.mission-statement h3 {
    color: var(--success);
    margin-bottom: var(--space-md);
    font-size: 1.3rem;
}

.mission-statement p {
    font-size: 1.2rem;
    line-height: 1.8;
    color: var(--text);
}

.mission-statement strong {
    color: var(--accent);
}

footer {
    text-align: center;
    padding: var(--space-geo) var(--space-md);
    border-top: 1px solid #222;
    color: var(--muted);
    font-size: 0.9rem;
}

@media (max-width: 768px) {
    .layer-content,
    .moves-grid,
    .scales-grid {
        grid-template-columns: 1fr;
    }
    
    .mapping-item {
        grid-template-columns: 1fr;
        text-align: center;
    }
    
    .product-name {
        text-align: center;
    }
    
    header h1 {
        font-size: 2rem;
    }
    
    nav {
        flex-wrap: wrap;
        gap: var(--space-md);
    }
}
CSS

# Create the unified index
echo "📄 Creating unified index..."

cat > index-unified.html << 'INDEX'
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ukubona — Adaptive Systems for Health</title>
    <link rel="stylesheet" href="assets/css/unified.css">
</head>
<body>

<header>
    <h1>Ukubona</h1>
    <p class="tagline">
        We build adaptive systems for health and human development.<br>
        We operate in <strong>incomplete information</strong> environments.<br>
        We reduce the gap between intention and outcome.
    </p>
</header>

<nav>
    <a href="#premise">Premise</a>
    <a href="assets/html/framework.html">🧭 Framework</a>
    <a href="#sensing">Sensing</a>
    <a href="#modeling">Modeling</a>
    <a href="#acting">Acting</a>
    <a href="assets/html/team.html">Team</a>
    <a href="assets/html/ukhona.html">Philosophy</a>
</nav>

<section id="premise" class="premise-section">
    <div class="container">
        <h2>Premise</h2>
        <p>
            The world is not fully visible. It arrives as signals, delays, and noise.
            Every person, household, clinic, and ministry operates with <strong>incomplete maps</strong> of reality.
        </p>
        <p>
            The difference between the map and the territory is <strong>loss</strong>.<br>
            Loss is measurable. Loss is improvable.
        </p>
        
        <div class="loss-equation">
            <p>Reality − Model = Loss</p>
            <p class="arrow">↓</p>
            <p>Loss → Feedback → Update</p>
            <p class="arrow">↓</p>
            <p>Update → Reduced Loss</p>
        </div>
        
        <p>
            Ukubona exists to reduce that gap.<br>
            We turn incomplete information into <strong>structured iteration</strong>.
        </p>
        
        <div style="text-align: center; margin-top: var(--space-xl);">
            <h3>The Ukubona Framework</h3>
            <p>We don't have the full gradient. We never will.<br>
            So we <strong>see blindly • forage stochastically • rehearse consequentially • descend</strong>.</p>
            <p><a href="assets/html/framework.html" style="color: var(--accent); font-weight: 600; font-size: 1.1rem;">
                Read the operational framework →
            </a></p>
            
            <h3 style="margin-top: var(--space-lg);">Works at every scale</h3>
            <p style="font-size: 1.2rem; color: var(--accent);">
                Person • Household • Clinic/Hospital/School • Ministry of Health
            </p>
        </div>
    </div>
</section>

<div id="sensing-container"></div>
<div id="modeling-container"></div>
<div id="acting-container"></div>

<footer>
    <p>See, blindly • Forage, stochastically • Rehearse, consequentially • Descend</p>
    <p>Ukubona LLC · Adaptive Systems for Health & Human Development</p>
    <p>Kampala · Baltimore · Boston · Washington DC</p>
</footer>

<script>
    async function loadSection(file, containerId) {
        try {
            const response = await fetch(file);
            const html = await response.text();
            document.getElementById(containerId).innerHTML = html;
        } catch (error) {
            console.error(`Error loading ${file}:`, error);
        }
    }
    
    loadSection('assets/html/layer-sensing.html', 'sensing-container');
    loadSection('assets/html/layer-modeling.html', 'modeling-container');
    loadSection('assets/html/layer-acting.html', 'acting-container');
</script>

</body>
</html>
INDEX

echo ""
echo "✅ ALL FILES CREATED"
echo ""
echo "📁 New structure:"
echo "   assets/html/layer-sensing.html"
echo "   assets/html/layer-modeling.html"
echo "   assets/html/layer-acting.html"
echo "   assets/html/framework.html"
echo "   assets/css/unified.css"
echo "   index-unified.html"
echo ""
echo "🚀 TO DEPLOY:"
echo "   open index-unified.html"
echo "   open assets/html/framework.html"
echo ""
echo "🔥 When ready to go live:"
echo "   mv index.html index-old.html"
echo "   mv index-unified.html index.html"
echo ""
EOF

chmod +x run.sh
```

Now just:

```bash
bash run.sh
```

That's it. One command. Done. 🚀

## XI
# X
**Implementation plan — zero fluff, copy-paste, 4 steps max.**  
You already shipped the three moves into the footer. Perfect. We just close the loop and wire the rest.

### Step 1: Finish the 4-move loop (2-minute edit)
Edit `assets/html/footer.html`

Replace the current line with:

```html
To see, blindly • To forage, stochastically • To rehearse, consequentially • To descend
```

(That’s the full algorithm: **UKB → UB → Game → UI** in your own terminology.)

### Step 2: Create the operational framework page (the one that actually explains what the site does)
Create new file: `assets/html/framework.html`

Copy the entire content of `assets/html/mission.html` as a template (same heading style, same simple layout).

Then **replace everything after the <h1>** with this exact block:

```html
<h1>The Ukubona Framework</h1>
<p><strong>The loss landscape is real.</strong> Every human system (body, family, clinic, ministry) is running stochastic gradient descent on an unknowable high-dimensional surface. The map is never the territory. So we operate anyway.</p>

<h2>The 4 operational moves (same at every scale)</h2>
<ol>
  <li><strong>See, blindly (UKB)</strong><br>Estimate the local gradient from whatever data exist + counterfactual simulation. Your digital twin is the blind scout sweeping the loss surface right now.</li>
  <li><strong>Forage, stochastically (UB)</strong><br>High-variance exploration. Run thousands of parallel futures so the system can discover paths no linear plan would ever find.</li>
  <li><strong>Rehearse, consequentially</strong><br>Play the full trajectory with real stakes attached — but zero irreversible cost. Watch money, health, regret, and coordination cost cascade across time.</li>
  <li><strong>Descend (UI)</strong><br>Once a better direction is visible, linearize and exploit. Turn the pheromone trail into protocol, dashboard, workflow, policy.</li>
</ol>

<h2>Scales of application (same 4 moves, different loss function)</h2>

<h3>Person</h3>
<p>Your body is the terrain. We give you a personal digital twin so you can see absolute risk, forage untested treatment sequences, and rehearse the next 5 years of your life before you live them.</p>

<h3>Household</h3>
<p>One person’s gradient affects everyone. Rehearse “If Mum starts dialysis, what happens to Dad’s retirement, the kids’ school fees, and family mental health?”</p>

<h3>Firm (Clinic · Hospital · School · University)</h3>
<p>Rehearse triage pathways, staffing, outbreak response, wellness policies before rollout.</p>

<h3>Government (Ministry of Health)</h3>
<p>National loss surface: DALYs, budget, equity. Paul Luswata’s Uganda Depression Map is the first live prototype — real-time loss map from DHIS2 + surveys, stochastic foraging across intervention packages, rehearsal before policy becomes law.</p>

<h2>How the three products map to the moves</h2>
<ul>
  <li><strong>Personalized Risk Models</strong> → See, blindly</li>
  <li><strong>Game of Care</strong> → Forage + Rehearse</li>
  <li><strong>Health Infrastructure</strong> → Descend (turns rehearsal into repeatable workflow)</li>
</ul>

<p><strong>One-sentence mission (replace the old tagline wherever you want):</strong><br>
Ukubona builds the meta-cognitive layer that lets every scale of human organization run stochastic gradient descent on its own health outcomes when the full gradient is unknowable.</p>

<a href="team.html">Meet the scouts who are building it →</a>
```

Save. Done. Page is now live at `/assets/html/framework.html`

### Step 3: Wire it into navigation (30 seconds)
Edit `assets/html/header.html`

Add this line anywhere in the nav list:

```html
[🧭 Framework](/assets/html/framework.html)
```

(Place it after Mission or Models — whatever feels right.)

### Step 4: Quick homepage upgrade (optional but recommended — 5 minutes)
Open `index.html`

After the “What We Build” section (right before “Why Us”), insert:

```html
<h2>The Ukubona Framework</h2>
<p>We don’t have the full gradient. We never will.<br>
So we <strong>see blindly • forage stochastically • rehearse consequentially • descend</strong>.</p>
<p><a href="assets/html/framework.html">Read the operational framework →</a></p>

<h2>Works at every scale</h2>
<p>Person • Household • Clinic/Hospital/School/University • Ministry of Health</p>
```

That’s it.

### After you push
- Visit https://ukubona-llc.github.io/assets/html/framework.html → should look clean and coherent.
- The whole site now reads as **one system** instead of philosophy + scattered products.
- Footer, nav, homepage, and new framework page all say the same thing in the same language.

Do these four steps and reply “done” (or paste any error).  
Next round we can tighten the Game of Care page or add the actual scales examples if you want. No style work until you say so.  

You’re 80 % there already — this just makes it obvious to every visitor in <60 seconds. Go ship.
## II
**Game of Care page — tightened into the rehearsal engine (copy-paste ready)**

This is now **the operational interface** for **Forage, stochastically + Rehearse, consequentially**.

It is the only place on the entire site where a human being can **feel** the loss landscape instead of just reading about it.

Replace **everything** inside `assets/html/game.html` (after the shared header, before the shared footer) with this exact block:

```html
<h1>🎮 The Game of Care</h1>
<p><strong>Healthcare as sequential, consequential play.</strong><br>
This is not symptom googling. Google gives you one static answer. This lets you <strong>live the futures you cannot afford to live</strong> — then rewind, branch, and try again.</p>

<h2>This is the rehearsal room for the loss landscape</h2>
<p>The Game of Care is the live interface to two of the four moves:</p>
<ul>
  <li><strong>Forage, stochastically</strong> — you explore thousands of parallel decision paths no guideline ever tested.</li>
  <li><strong>Rehearse, consequentially</strong> — you watch the full cascade: health, money, time, regret, coordination cost, political capital. Every choice ripples across avatars and across years.</li>
</ul>
<p>Zero irreversible cost. Full intelligence. That is the point.</p>

<h2>Play from any seat at the table</h2>
<p>One scenario. Six avatars. Same branching reality. Watch how your move changes everyone else’s loss surface.</p>

<div style="display:grid; grid-template-columns:repeat(auto-fit,minmax(280px,1fr)); gap:2rem; margin:2rem 0;">

  <div>
    <h3>👩‍⚕️ Primary Care Doctor</h3>
    <p>Balance evidence, time pressure, and patient story. Every order you write reshapes the patient’s trajectory, the insurer’s budget, and the nurse’s workload.</p>
    <strong>Watch:</strong> diagnostic accuracy • patient satisfaction • system cost
  </div>

  <div>
    <h3>🧑‍🦽 Patient</h3>
    <p>You are the one who actually lives the outcome. Navigate symptoms, insurance denials, family burden, and your own fear.</p>
    <strong>Watch:</strong> health outcome • financial ruin • quality of life • regret
  </div>

  <div>
    <h3>🏢 Insurance Executive</h3>
    <p>Approve or deny? Every prior-authorization decision is a bet on a future that has not happened yet.</p>
    <strong>Watch:</strong> claims paid • network strain • actuarial tail risk • public backlash
  </div>

  <div>
    <h3>📚 Medical Student / Trainee</h3>
    <p>Fail safely, repeat the same case 50 times with different variables, learn the shape of the loss surface before you ever touch a real patient.</p>
    <strong>Watch:</strong> clinical reasoning • bedside manner • long-term patient outcomes
  </div>

  <div>
    <h3>🚑 Emergency Responder</h3>
    <p>Time is the only currency. Triage under uncertainty. Every second reallocates finite ambulances, beds, and staff.</p>
    <strong>Watch:</strong> lives saved • resource exhaustion • downstream hospital chaos
  </div>

  <div>
    <h3>🧑‍⚕️ Nurse / Care Coordinator</h3>
    <p>You are the glue. You see the gaps the doctors miss. Your calls prevent crises that never make it into the chart.</p>
    <strong>Watch:</strong> adherence • readmissions • caregiver burnout • family collapse
  </div>
</div>

<h2>Live example: To Screen or Not to Screen?</h2>
<p>A 52-year-old woman walks into clinic. PSA test? Mammogram? Low-dose CT? Routine guideline says one thing. Her exact risk surface says another.</p>
<p>In the Game you can:</p>
<ul>
  <li>Play as the doctor — order the test or not</li>
  <li>Play as the patient — accept or refuse</li>
  <li>Play as the insurer — pre-authorise or deny</li>
  <li>Run 1 000 Monte-Carlo futures</li>
  <li>Watch the full 10-year cascade: false positive cascade, over-treatment, financial toxicity, missed cancer, family impact, regret</li>
  <li>Rewind and change one variable (adherence, comorbidity, income, trust in system) and see the loss surface shift</li>
</ul>
<p>That single rehearsal is worth more than any static risk calculator or guideline PDF.</p>

<h2>Clinic Chat Simulator (prototype)</h2>
<p>Coming next: multi-avatar live chat. Doctor + Patient + Insurer + Family Member in the same simulated room. Every message changes the shared loss surface in real time.</p>

<p><strong>This is intelligence.</strong><br>
Not information. Not advice. The ability to feel the terrain before you step on it.</p>

<a href="../framework.html">← Back to the full Ukubona Framework</a>
```

### What changed & why it’s now coherent
- First two paragraphs kill the looseness and directly answer “how is this different from Google?”
- Explicitly maps to **Forage + Rehearse** (the exact two moves the framework says this product owns).
- Avatars are no longer random bullets — each now shows **whose loss surface you are moving**.
- The screening example is now a concrete, repeatable rehearsal demo (exactly what the homepage promises).
- Ends with the one-sentence killer: “This is intelligence.”

### Next tiny steps (do these after you push)
1. Update the homepage blurb (in index.html) to:
   ```html
   Game of Care: Rehearse high-stakes choices safely — watch the full cascade across patients, clinicians, payers and time. Not googling. Not a quiz. The rehearsal engine for the loss landscape.
   ```
2. In the nav (header.html) change the Game link text to:
   ```html
   🎮 Game of Care (Rehearsal Engine)
   ```

Push it. Visit `/assets/html/game.html`. It should now feel like the **sharpest, most operational page** on the site instead of the loosest.

Tell me “done” or paste any error and we move to the next loose bit (probably the models page or the actual interactive prototype).  

This is the point. This is intelligence. Let’s go.
## III
## IV
## V
