# Chapter 29: Metabolism and Nutrition

**TL;DR:** Your body runs on a continuous trade-off between breaking down food for immediate energy and storing it for later. The same fuel molecules can be reshuffled into glucose, fat, or used to power muscle—all controlled by a handful of hormones that read your fed or fasted state and redirect chemistry accordingly.

---

## Chapter Opening

You haven't eaten in eight hours. Your brain is burning glucose, your muscles are burning fat, your liver is manufacturing new glucose from lactate and glycerol because your blood sugar cannot drop below 80 mg/dL without consequence. Somewhere in those mitochondria, oxygen is accepting electrons at the end of an assembly line of proteins, and that acceptance is the only reason you're breathing at all.

At the same time, if someone hands you a sandwich, everything changes. Within minutes your pancreas reads the glucose spike and releases insulin. Your liver stops making glucose and starts storing it. Your muscles stop burning fat and start stockpiling glycogen. The same molecular machinery switches direction on a hormone signal.

This chapter moves through three mechanisms. The first is how a single glucose molecule becomes ATP—the path from glycolysis through the Krebs cycle to the electron transport chain, and why oxygen is not optional. The second is how the body switches between the three metabolic states: fed, fasting, starving. The third is thermoregulation—why roughly 60 percent of the energy your body extracts from food is released as heat, and how your hypothalamus acts as a thermostat to keep that heat output exactly right.

## Concept 1: From Glucose to ATP—The Central Pathway

### Cold Open

The electron doesn't care about energy; it cares about stability. At the beginning of glycolysis, glucose is a six-carbon sugar holding chemical bonds like a coiled spring. By the time that glucose molecule reaches the electron transport chain, electrons have been stripped from it in a careful, step-by-step process. Each time an electron is removed and passed to a carrier (NAD+ or FAD), a small amount of energy is released. Those electrons flow downhill through a series of protein complexes in the mitochondrial membrane, their fall powering the pumping of protons across the membrane. Those protons create a gradient—a pressure—that drives a spinning turbine called ATP synthase. The turbine drives the creation of ATP.

But here's the constraint: the electrons have to go somewhere at the end of the line. If they don't, the entire chain backs up and stops. That's why oxygen is the terminal electron acceptor. Without it, the chain halts. Your cells can run on glycolysis alone for a few seconds—enough for a sprint, not enough for a run. After that, you need oxygen.

### Mechanism: Glycolysis → Pyruvate → Krebs Cycle → ETC → ATP

The machinery has three stages, each extracting energy from different parts of the glucose molecule.

**Glycolysis** (cytoplasm): Glucose enters the cell and is immediately phosphorylated—a phosphate is clamped onto it. This "traps" the glucose inside the cell (it can't cross the membrane anymore) and establishes a concentration gradient that keeps glucose flowing in. The six-carbon glucose is split into two three-carbon molecules called pyruvate. In this process, two ATP are consumed (priming phase) and four ATP are generated (payoff phase), yielding a net gain of two ATP and two electron-carrying NADH molecules.

$$\text{Glucose} + 2\text{ATP} + 2\text{NAD}^{+} \rightarrow 2\text{Pyruvate} + 4\text{ATP} + 2\text{NADH}$$

That's quick energy. But it's also meager—only two ATP per glucose, and the majority of the chemical energy in the glucose molecule is still locked in the pyruvate.

**Krebs Cycle** (mitochondrial matrix): The pyruvate enters the mitochondria and is converted to acetyl CoA—a two-carbon fragment that carries what's left of the glucose molecule's energy. This step releases the first carbon as CO₂. The acetyl CoA enters the cycle by combining with a four-carbon molecule (oxaloacetate) to form a six-carbon molecule (citrate). The cycle systematically strips the remaining carbons as CO₂ (waste product) and electrons (the real treasure). For each turn of the cycle—which happens twice per glucose (since one glucose makes two pyruvate)—three NADH and one FADH₂ are produced. A small amount of ATP (or GTP, which is equivalent) is also made.

For each glucose, the net yield from the Krebs cycle is 6 NADH, 2 FADH₂, and 2 ATP. All the carbons of the glucose are now in CO₂, which you exhale.

**Electron Transport Chain & Oxidative Phosphorylation** (inner mitochondrial membrane): This is where the real payoff lives. NADH and FADH₂ don't produce ATP directly; they're electron carriers. They approach the inner mitochondrial membrane and hand their electrons to Protein Complex I (NADH) or Complex II (FADH₂). Electrons flow through a series of protein complexes embedded in the membrane, and at each step, the electron loses energy. That energy is used to pump protons (H⁺) across the membrane, creating a proton gradient—a higher concentration of protons in the intermembrane space than in the matrix.

This is the crucial insight: the gradient is the battery. The protons want to flow back into the matrix, but the membrane blocks them. The only route is through ATP synthase, a protein turbine. As protons flow through, the turbine spins, and that mechanical motion powers the phosphorylation of ADP into ATP. One NADH yields roughly 3 ATP (because NADH starts at Complex I, which is higher up the energy ladder). One FADH₂ yields roughly 2 ATP (because it starts at Complex II, partway down).

At the end of the chain, electrons combine with protons and oxygen to form water. This is why oxygen is non-negotiable. Without it to accept the electrons, the gradient collapses and ATP synthesis stops.

**Total Yield:** Per glucose, aerobic respiration produces roughly 32-36 ATP (accounting for the cost of moving NADH produced in the cytoplasm into the mitochondria). If you used only the glycolytic pathway (anaerobic), you'd get 2 ATP. The difference—a 15-fold increase in energy yield—is the difference between a sprint and a distance run.

### Trade-off: Speed vs. Efficiency

Glycolysis is fast. It happens in the cytoplasm, no mitochondria required, and it makes ATP in seconds. Erythrocytes (red blood cells) don't have mitochondria, so they live entirely on glycolysis. During intense exercise, muscles switch partly to glycolysis because it's quick—they produce pyruvate faster than oxygen can be delivered. The pyruvate becomes lactate (to regenerate the NAD+ the cycle needs to keep running), and lactate diffuses into the blood for the liver to convert back to glucose (the Cori cycle).

But glycolytic ATP is expensive per unit of glucose. You get two ATP instead of thirty-six. If sustained energy is the goal, you have to burn far more glucose to generate the same power. This is why endurance athletes train to improve oxygen delivery to muscles; more oxygen in the mitochondria means less reliance on glycolysis and more ATP per calorie burned.

The trade-off is one the body navigates in real time. During rest, the Krebs cycle and ETC dominate. During a sprint, glycolysis contributes. During starvation (when the next meal is uncertain), the body switches to fatty acid oxidation, which feeds acetyl CoA directly into the Krebs cycle, bypassing glycolysis entirely.

### Worked Example

A marathon runner burns roughly 2,600 calories in 4 hours. Assuming the runner uses mostly aerobic metabolism (Krebs + ETC), how many moles of glucose are oxidized?

- 1 mole of glucose = 686 kcal (when fully oxidized to CO₂ and H₂O)
- 2,600 kcal ÷ 686 kcal/mol ≈ 3.8 mol glucose
- 3.8 mol × 180 g/mol = 684 g glucose

That's 1.5 pounds of glucose equivalent. The runner doesn't carry that much glucose in blood or muscle glycogen. Where does the rest come from? About half the ATP comes from fat oxidation (which yields fewer ATP per mole of oxygen consumed but more ATP per unit mass). The other major fuel source is amino acids from muscle protein, contributing roughly 5-10% during prolonged exertion.

The runner is not burning pure carbohydrate. The runner is running a hybrid engine, switching between fuels to sustain the power output for four hours.

### Misconceptions

**Myth: "We need carbohydrates for energy; fat is just storage."** 
False. Once acetyl CoA is formed, fat and carbohydrates feed the exact same Krebs cycle. During starvation or low-carb diets, the body runs predominantly on fat-derived acetyl CoA. Carbohydrates are preferred (they're faster to mobilize) but not essential for the Krebs cycle itself. The brain does require glucose specifically, but the liver can manufacture glucose from glycerol and amino acids via gluconeogenesis even when carbohydrates are absent.

**Myth: "Oxygen burns fat; it doesn't burn carbohydrate."**
False. Both carbohydrates and fat require oxygen at the electron transport chain. The difference is that carbohydrate (glucose) enters at glycolysis, while fat (fatty acids) are converted to acetyl CoA and enter at the Krebs cycle. But both paths end at the same terminal electron acceptor: oxygen. You can't burn either fuel without it.

**Myth: "The mitochondria is a furnace; it burns calories as heat."**
Partially true, but misleading. The mitochondria generates ATP by creating a proton gradient and harvesting its dissipation. Roughly 40% of the energy released by breaking chemical bonds in glucose is captured as ATP. The other 60% is released as heat—which is why the body is warm and why exercise generates body heat. But the heat is not wasted; it's what allows mammals to maintain constant core temperature. A dead mitochondrion or a broken ETC is not generating heat; it's generating nothing.

---

## Concept 2: The Three Metabolic States—Fed, Fasting, Starving

### Cold Open

Three hours after breakfast, your blood glucose is rising. Insulin is released from pancreatic beta cells. Your liver stops making glucose and starts storing it. Muscles take up glucose and convert it to glycogen. Fat is moving from the intestines to adipose tissue. This is the fed state—anabolism exceeds catabolism.

Eight hours later (middle of the night), breakfast is long gone. Your blood glucose drops. Insulin falls. The pancreas releases glucagon from alpha cells. The liver reads that signal and does the opposite: it stops storing glucose and starts releasing it. Glycogen is broken down to glucose. Liver cells begin manufacturing new glucose from pyruvate and lactate (from muscles and red blood cells) and glycerol (from adipose tissue lipolysis). Fat is released from adipose tissue as fatty acids; muscles and the heart burn fatty acids instead of glucose, preserving glucose for the brain. This is the postabsorptive (fasting) state—catabolism begins to exceed anabolism.

Three days into starvation, something else happens. The Krebs cycle is overloaded with acetyl CoA from aggressive fat oxidation. The liver begins synthesizing ketone bodies—acetoacetate and β-hydroxybutyrate—which enter the blood and supply the brain and heart. Muscle protein is spared as long as possible; only when fat stores are depleted does significant muscle breakdown occur. This is the starvation state, and it's a hierarchy of metabolic priorities: glucose for the brain, fat for the body, muscle only when necessary.

### Mechanism: Hormonal Orchestration of Metabolic Switching

Three hormones orchestrate the shift: insulin, glucagon, and cortisol. Each reads a different metabolic signal and triggers a cascade of enzyme activations and deactivations.

**Absorptive State (Fed):** Blood glucose rises after a meal. Pancreatic beta cells respond and release insulin. Insulin signals three major events:

1. **Glucose uptake:** Muscle cells and adipocytes have glucose transporters (GLUT4) that respond to insulin. When insulin binds, GLUT4 moves to the cell membrane, allowing glucose to enter. The glucose is immediately phosphorylated to glucose-6-phosphate (trapping it inside) and shunted toward glycolysis or glycogen synthesis.

2. **Glycogen storage:** The enzyme glycogen synthase is activated by insulin. Glucose-6-phosphate is converted to glycogen in liver and muscle. This is short-term buffering—the body can store 500 grams of glycogen (enough for 12-18 hours of basal metabolism).

3. **Fat storage:** Excess glucose is converted to acetyl CoA, which is used to synthesize triglycerides via lipogenesis. These triglycerides are packaged into VLDL particles (very low-density lipoproteins) and shipped to adipose tissue for long-term storage.

Insulin also inhibits glucagon release, effectively turning off glucose manufacture in the liver. The absorptive state lasts 3-4 hours, until glucose begins to fall and insulin drops.

**Postabsorptive State (Fasting):** As blood glucose drops below ~100 mg/dL, insulin secretion decreases. The pancreatic alpha cells release glucagon. Glucagon does three things:

1. **Glycogenolysis:** Glycogen phosphorylase is activated. Glucose units are cleaved from glycogen and released as glucose-1-phosphate, which is converted to glucose and released into the blood. The liver uses glycogenolysis to rapidly restore blood glucose within the first few hours of fasting.

2. **Gluconeogenesis:** After glycogen is depleted (4-8 hours), the liver synthesizes new glucose from non-carbohydrate sources. The principal substrates are lactate (from muscle and red blood cell glycolysis), glycerol (from adipose tissue lipolysis), and amino acids (alanine and glutamine from muscle). The key enzyme is PEPCK (phosphoenolpyruvate carboxykinase), which catalyzes the conversion of oxaloacetate to phosphoenolpyruvate, the rate-limiting step of gluconeogenesis.

3. **Lipolysis:** Adipose tissue responds to low insulin and elevated glucagon by increasing the activity of hormone-sensitive lipase. Triglycerides are broken down to glycerol and fatty acids. Glycerol returns to the liver for gluconeogenesis. Fatty acids enter the blood as free fatty acids, taken up by muscle and heart for β-oxidation.

The postabsorptive state typically lasts 12-16 hours (a normal overnight fast).

**Starvation State (Extended Fasting):** After 24-36 hours without food, liver glycogen is depleted. Gluconeogenesis continues but at a cost: the amino acids required are pulled from muscle protein. If this continues, muscle wasting accelerates. To spare muscle, the body shifts to ketogenesis.

The liver, flooded with acetyl CoA from fat oxidation, converts excess acetyl CoA to ketone bodies. The process:

$$2\text{ Acetyl CoA} \rightarrow \text{Acetoacetyl CoA} \rightarrow \text{β-hydroxybutyrate} + \text{Acetoacetate}$$

These enter the blood. The brain, which normally uses only glucose, adapts to use ketone bodies as a primary fuel source within 3-4 days. The shift preserves muscle protein because fat stores, not muscle, are now the primary fuel.

The starvation state can be sustained as long as fat stores remain. When fat is depleted, muscle breakdown accelerates. Historical records of starvation (famines, shipwrecks) show that death typically follows when the body's fat and muscle reserves are exhausted.

### Trade-off: Buffering Capacity vs. Metabolic Flexibility

The body maintains multiple energy buffers:

- **Immediate ATP** (~0.25 mol): Enough for seconds of maximum effort. Phosphocreatine can regenerate ATP for ~10 seconds more.
- **Muscle glycogen** (~500 g glucose equivalent): Fuels the muscle that stores it for hours, unavailable to the brain (muscles lack glucose-6-phosphatase, the enzyme required to release glucose).
- **Liver glycogen** (~100 g): Available to the whole body, depleted in ~8 hours of fasting.
- **Blood glucose** (~5 g): Tightly regulated by the liver, maintained at 80-120 mg/dL.
- **Fat stores** (~15 kg in a lean adult, providing ~135,000 kcal): The largest reserve, sustaining the body for weeks.

The trade-off is one of responsiveness vs. density. Glucose (glycogen) is mobilized fast but stored in small quantities. Fat is stored abundantly but requires several metabolic steps to mobilize (hydrolysis → transport → β-oxidation). The body prioritizes glucose availability to the brain while sequestering fat as the long-term reserve.

Gluconeogenesis illustrates another trade-off: it's expensive. Glucose synthesis requires 6 ATP equivalents per glucose molecule, whereas glucose release from glycogen costs nothing. But gluconeogenesis can operate when glycogen is gone, making it the survival mechanism when buffering capacity is exhausted.

### Worked Example

A person fasts for 24 hours. The liver's glycogen store (~100 g glucose, or 0.56 mol) is depleted in the first 8 hours. How much amino acid is oxidized to sustain glucose for the brain in hours 8-24?

The brain uses ~120 g glucose per day (0.67 mol). If 100 g came from glycogen, the remaining 20 g must come from gluconeogenesis over the remaining 16 hours.

Assuming gluconeogenesis from alanine (molecular weight 89 g/mol):

- 20 g glucose ≈ 0.11 mol glucose required
- Alanine → pyruvate → oxaloacetate → phosphoenolpyruvate → glucose (3 ATP per glucose)
- 0.11 mol glucose × 89 g/mol alanine ≈ 10 g alanine (or 40 g protein, assuming amino acids are 25% of protein mass)

The body breaks down roughly 40 g of muscle protein per day during early starvation. With ~7 kg of mobilizable muscle protein, this is sustainable for ~3 months before critical function is lost. This is why prolonged fasting leads to muscle loss; the brain's glucose demand is inelastic.

### Misconceptions

**Myth: "Your liver is smart; it knows to store fat when you eat and burn it when you fast."**
Partially true but misdirected. The liver doesn't "know" anything; it responds to hormone signals. If insulin is high, it stores. If glucagon is high, it mobilizes. This works well when fasting and feeding are regular, but in an environment where food is constantly available (high insulin), the liver stores fat but never fully mobilizes it. The problem is not the liver's storage strategy; it's that the signal—perpetually high insulin—never turns off.

**Myth: "Ketosis is dangerous; it's what kills you in starvation."**
False. Ketosis (elevated blood ketones) is a normal, healthy adaptation to fasting. The danger in starvation is not ketosis per se but depletion of fat and muscle stores to a point where vital organs fail. Ketoacidosis (diabetic ketoacidosis) is dangerous because it combines uncontrolled glucose (from insulin deficiency) with ketosis, creating extreme pH drop. But nutritional ketosis from fasting is not inherently toxic.

**Myth: "The body prefers glucose over fat; it will burn glucose first."**
This is roughly true during the fed and early postabsorptive states, but it's an oversimplification. Tissues differ. The brain and red blood cells *require* glucose (or ketones in extended fasting). Muscle and heart *prefer* fat during the postabsorptive state—they conserve glucose for the brain. Fatty acid oxidation actually begins within minutes of fasting, competing with glucose for ATP production. The "glucose first" principle is really "spare the glucose for the brain."

---

## Concept 3: Thermoregulation—Why Heat Matters

### Cold Open

On a cold winter day, you step outside and your body temperature holds steady at 37°C. Your muscles are shivering, burning glucose rapidly. Heat is being generated as a byproduct of ATP synthesis—the 60% of energy released as heat instead of captured as ATP. The hypothalamus, reading core temperature through thermoreceptors, has dialed up metabolic heat production. Your thyroid gland is releasing more thyroid hormone, which increases the efficiency of ATP synthesis (less ATP, more heat per energy released).

On a hot day, you're sweating. Evaporating water is carrying heat away from the skin. Blood vessels near the skin are dilated, radiating more heat. The hypothalamus is suppressing thyroid hormone release to reduce metabolic rate and minimize heat generation. Every thermoregulatory mechanism is an energy cost: shivering burns calories, sweating requires effort to pump water to the skin, vasoconstriction reduces blood flow and requires vascular control. The body maintains core temperature within ±0.5°C, and that precision costs energy.

### Mechanism: Heat Generation and Dissipation

The thermoregulatory system operates as a negative feedback loop. The hypothalamus sets a temperature setpoint (~37°C). Temperature sensors in the skin and core signal deviations. The hypothalamus triggers corrective responses.

**If Core Temperature Falls Below Setpoint:**

1. **Shivering thermogenesis:** Muscles are signaled to contract involuntarily. Muscle contraction generates ATP hydrolysis (ADP + Pi release) without producing mechanical work. The energy is released as heat. A person can generate 5-10 times their basal metabolic rate through vigorous shivering.

2. **Non-shivering thermogenesis:** Brown adipose tissue (brown fat) contains uncoupling protein (UCP1) in its mitochondrial membrane. UCP1 allows protons to leak back across the membrane without passing through ATP synthase. The proton gradient dissipates, and the energy is released as heat instead of captured as ATP. Newborns and small mammals use this mechanism extensively; humans rely more on shivering but retain brown fat in certain regions (neck, upper back, interscapular region).

3. **Hormonal increases:** The sympathetic nervous system releases norepinephrine, which stimulates thyroid hormone release. Thyroid hormone (T3 and T4) increases the cellular metabolic rate. This is slower (hours to days) but sustains heat production during chronic cold.

4. **Vasoconstriction:** Blood vessels near the skin constrict, reducing blood flow to the surface and minimizing heat loss. This is a trade-off: your extremities get colder, but core temperature is preserved.

**If Core Temperature Rises Above Setpoint:**

1. **Sweating:** Sudomotor neurons trigger sweat glands to release water onto the skin. Evaporation of water requires energy (~2.4 kJ per mL). This energy comes from body heat. Heavy sweating can dissipate ~1000 W of heat power—more than any other mechanism.

2. **Vasodilation:** Blood vessels near the skin dilate, increasing blood flow. More blood is delivered to the skin where heat is radiated and lost by convection.

3. **Behavioral changes:** You remove clothing, seek shade, or immerse in water. These are not physiological but are central to thermoregulation.

**Heat Exchange Mechanisms:**

The body loses heat through four physical processes:

- **Radiation (~60%):** Infrared radiation from the skin to the environment. Effective when the environment is cooler than the skin.
- **Conduction (~3%):** Direct heat transfer to objects in contact (ground, clothing, water). Large pools of water absorb enormous amounts of heat; hypothermia develops rapidly in cold water.
- **Convection (~15%):** Heat transfer to moving air. Wind increases convective heat loss significantly (wind chill effect).
- **Evaporation (~22%):** Heat required to convert liquid water to vapor. This is the only mechanism that works when the environment is hotter than the skin (since radiation, conduction, and convection reverse).

In desert heat, evaporation is the only effective cooling mechanism. In humid heat, sweating becomes ineffective because air is already saturated with water vapor, so evaporation slows. This is why humid 95°F is more dangerous than dry 95°F: the body cannot dissipate heat effectively.

### Trade-off: Metabolic Cost of Precision

Thermoregulation is energetically expensive. Shivering in cold, sweating in heat, and thyroid hormone elevation all increase metabolic rate above basal levels. A person exposed to cold for hours may increase metabolic rate by 20-40%. The metabolic cost is why people eating low-calorie diets in cold climates have higher caloric needs than those in warm climates.

The precision of thermoregulation (holding core temperature within ±0.5°C) is exceptional among physiological variables. Blood pH varies by ±0.05 units. Blood glucose varies by ±40 mg/dL. But core temperature varies by <1°C despite enormous fluctuations in environmental temperature and metabolic heat production.

This precision carries a cost. A set-point temperature that was 1°C higher would reduce the frequency of thermoregulatory responses and save energy. But the cost would be paid in enzyme efficiency (enzymes have narrow temperature optima; protein denaturation accelerates above 42°C) and metabolic rate (enzyme catalysis slows ~2% per degree Celsius below the set-point).

The body has chosen to pay the metabolic cost of precision. This is adaptive in stable environmental conditions (where the cost is manageable) but becomes maladaptive in extreme conditions (high fever, heat stroke, hypothermia) where thermoregulation itself becomes the problem.

### Worked Example

A 70 kg person is exposed to 4°C water for 1 hour. Core body temperature drops from 37°C to 32°C (5-degree drop). How much heat was lost?

Heat capacity of the human body ≈ 3.5 kJ/(kg·°C) (mostly water)

Heat lost = 70 kg × 3.5 kJ/(kg·°C) × 5°C = 1225 kJ

This is roughly equivalent to running for 30 minutes (expending ~100 W for 1800 seconds = 180 kJ) multiplied by 7. The body lost heat equivalent to seven 30-minute runs in one hour. 

If the person had not been shivering (shivering can generate ~500 W of heat), the temperature drop would have been:

Heat generated by shivering in 1 hour = 500 W × 3600 s = 1800 kJ

Net heat loss = Heat lost - Heat generated = 1225 - 1800 kJ (net heat retained)

But this calculation shows the limit: prolonged water immersion eventually overcomes even vigorous shivering. Humans have poor insulation (no fur or blubber like marine mammals). Cold water becomes life-threatening within minutes.

### Misconceptions

**Myth: "The body burns more calories in cold weather, so cold exposure is good for weight loss."**
Partially true, but impractical. Yes, cold increases metabolic rate ~10-20%. But the metabolic increase from cold exposure is small compared to the increase from exercise or dietary thermogenesis (the energy cost of digesting food). Someone losing weight would benefit far more from exercise or reducing caloric intake than from sitting in cold.

**Myth: "Sweating rids the body of toxins."**
False. Sweat is ~99% water and electrolytes (sodium, potassium, chloride). It contains urea (a waste product) but in tiny amounts. The kidneys, not sweat glands, eliminate the majority of metabolic waste. This myth has driven sauna use and sweat lodge practices with no metabolic justification.

**Myth: "Fever is bad; you should always try to reduce it."**
Oversimplified. Fever is a thermoregulatory response to infection. The elevated set-point temperature (induced by pyrogens—cytokines released during immune response) is thought to enhance immune function (some pathogens replicate less efficiently at higher temperatures). A moderate fever (up to 39°C/102°F) in an otherwise healthy person is generally self-limited and may aid recovery. However, fever above 40°C (104°F) is dangerous (proteins begin to denature) and should be treated. The key is distinguishing adaptive fever from dangerous hyperthermia.

---

## Integration: How the Three Concepts Connect

The three pathways—energy extraction, metabolic switching, and thermoregulation—are not independent. They're interlocking subsystems of a single metabolic control hierarchy.

When you eat, insulin rises, blood glucose rises, and core body temperature may rise slightly (postprandial thermogenesis—the energy cost of digesting, absorbing, and storing nutrients). The Krebs cycle and ETC are running at high capacity, extracting ATP and generating heat as a byproduct.

When you fast, glucagon rises, lipolysis increases, and the liver shifts to ketogenesis. If it's cold during the fast, cortisol (the third metabolic hormone, released during stress or fasting) amplifies gluconeogenesis and increases metabolic rate. If it's warm, the body may reduce metabolic rate slightly to conserve energy during the fast.

When you exercise, muscles consume ATP at 100-fold their resting rate. Blood glucose and fatty acids are mobilized. Core body temperature rises (muscles generate heat as a byproduct of work). Sweating is triggered to dissipate that heat. The hypothalamus effectively raises its temperature set-point during exercise, allowing body temperature to rise while still triggering cooling mechanisms at the new (higher) set-point.

These are not separate mechanisms. They're one integrated system: metabolism.

---

## Exercises

**Warm-up:**

1. A glucose molecule enters glycolysis. How many phosphate bonds are broken and formed?
   - Two ATP are used (hydrolyzed) in the energy-consuming phase (bonds broken: 2)
   - Four ATP are synthesized in the energy-yielding phase (bonds formed: 4)
   - Net: 2 bonds broken, 4 bonds formed, yielding 2 ATP net

2. If a person's basal metabolic rate is 1,600 kcal/day, how many grams of glucose would be needed to sustain that rate for one day if glucose were the only fuel?
   - 1,600 kcal ÷ 4 kcal/g = 400 g glucose per day
   - In reality, the body uses a mix of carbohydrate, fat, and protein. During fasting, fat contributes ~80% of the ATP.

**Application:**

3. A runner eats a high-carbohydrate meal 2 hours before a 10-mile race. Insulin is still elevated. Why might the runner feel sluggish at the start of the race?
   - High insulin signals the body that glucose is abundant. Lipolysis is suppressed; fatty acid oxidation is low. The muscles are primed to use glucose (glycogen stores are high). 
   - But as the race progresses and glycogen is depleted, the metabolic machinery must switch from glucose to fatty acid oxidation. This switch takes time (~5-10 minutes) and involves upregulating lipolysis and β-oxidation enzymes.
   - The "sluggish" feeling may reflect the lag in metabolic switching or the high insulin itself suppressing lipolysis.
   - The runner would feel better if the meal were 3-4 hours before the race (allowing insulin to fall) or if the meal emphasized fat and protein over carbohydrate, which would not trigger as large an insulin spike.

4. A person develops Type 2 diabetes (insulin resistance: pancreas produces insulin, but cells don't respond well). Explain why the person's blood glucose is high, and why they might feel hungry despite the high blood glucose.
   - High insulin but low cellular glucose uptake: blood glucose remains high because cells aren't taking up the glucose, but cells are "starving" for glucose (they're not getting it).
   - This signals the hypothalamus (via low intracellular glucose and metabolism) that the body is in a state of energy deficiency. Hunger increases.
   - The person eats more, raising insulin further. The cycle continues. This is the "starving in a sea of plenty" phenomenon.
   - Treatment involves increasing insulin sensitivity (exercise, weight loss, metformin) or providing additional insulin so cells can take up glucose despite the resistance.

**Synthesis:**

5. A person fasts for 48 hours in a warm environment and a second person fasts for 48 hours in a cold environment. Both maintain stable core temperature. Which person burns more calories?
   - The person in the cold environment burns more.
   - During fasting, both rely on gluconeogenesis and lipolysis. The cold person additionally relies on shivering thermogenesis and increased thyroid hormone-driven metabolic rate to generate heat.
   - The warm person can reduce metabolic rate slightly (vasodilation, reduced shivering) because heat dissipation is less challenging.
   - The cold person might burn 500-1000 extra kcal per day to maintain thermoregulation during the fast.
   - This is why people in cold climates have higher caloric requirements than those in warm climates, all else equal.

**Challenge:**

6. During a 24-hour fast, the liver's glycogen store (100 g) is depleted in ~8 hours. For hours 8-24, the liver shifts to gluconeogenesis to maintain blood glucose for the brain. What metabolic substrates are used, and in what proportion, to sustain this gluconeogenesis?
   - Lactate (from muscle and RBC glycolysis): ~40% of gluconeogenic substrate
   - Alanine (from muscle protein breakdown): ~25%
   - Glycerol (from adipose lipolysis): ~15%
   - Glutamine (from muscle protein breakdown): ~10%
   - Other amino acids: ~10%
   
   The alanine is produced in muscle by transamination (converting pyruvate to alanine, which is then transported to the liver and converted back to pyruvate for gluconeogenesis). This is the glucose-alanine cycle. Glycerol is released from adipose tissue when triglycerides are hydrolyzed for β-oxidation.
   
   As fasting extends beyond 24 hours, the proportion shifts: glycerol increases (from accelerating lipolysis) and alanine decreases (muscle is preserved, relying instead on ketone utilization). After 3-4 days, ketones supply ~70% of the brain's energy, reducing the gluconeogenic demand and sparing muscle protein.

---

## Chapter Summary

Metabolism is the sum of all chemical reactions occurring in the body. The central mechanism is the extraction of energy from glucose: glycolysis produces pyruvate and a net 2 ATP; the Krebs cycle extracts electrons (as NADH and FADH₂) and produces 1-2 ATP; the electron transport chain uses the electron gradient to pump protons, and ATP synthase harvests the proton gradient to synthesize ~30 ATP per glucose. Oxygen is the terminal electron acceptor; without it, the chain halts.

The body navigates three metabolic states: fed (absorptive, anabolism > catabolism), postabsorptive (fasting, catabolism > anabolism), and starvation. Insulin orchestrates the fed state (glucose uptake, glycogenesis, lipogenesis). Glucagon and cortisol orchestrate the postabsorptive and starvation states (glycogenolysis, gluconeogenesis, lipolysis, ketogenesis). The hierarchy of fuel use prioritizes glucose for the brain while sparing muscle protein as long as fat stores remain.

Thermoregulation maintains core body temperature (37°C ± 0.5°C) through a negative feedback loop controlled by the hypothalamus. Heat is generated by metabolism (~60% of ATP synthesis energy is released as heat). Heat is dissipated by radiation (~60%), evaporation (~22%, via sweating), convection (~15%), and conduction (~3%). Cold exposure triggers shivering, non-shivering thermogenesis (brown fat), and increased metabolic rate. Heat exposure triggers sweating, vasodilation, and reduced metabolic rate.

The three mechanisms are integrated: when fed, metabolism runs at high capacity and generates excess heat (thermoregulation increases cooling). When fasting and cold, metabolism increases (cortisol, thyroid) and thermoregulation increases heat generation. The body treats all three as one system.

---

## Connections Forward

The principle of metabolic switching—reading hormonal signals and redirecting biochemistry accordingly—appears throughout physiology. The nervous system (Chapters 11-12) demonstrates the same principle: neurotransmitters read sensory input and switch neuronal signaling. Endocrine regulation (Chapter 16) reveals that metabolism is controlled by a cascade of hormones (insulin, glucagon, thyroid, cortisol) that integrate inputs from the fed/fasted state and stress. The cardiovascular system (Chapter 18) delivers oxygen and fuel to tissues; without sufficient oxygen or glucose delivery, the metabolic machinery grinds to a halt.

The evolution of these mechanisms explains why we age and why we're vulnerable to metabolic disease. Insulin resistance (the primary driver of Type 2 diabetes) reflects a breakdown in the signaling system—cells stop responding to the "glucose is abundant" message. Chronic overfeeding upsets the metabolic balance, chronically elevated insulin suppresses lipolysis and gluconeogenesis, and the body defaults to storing energy as fat rather than mobilizing it. The mechanisms described here work for intermittent feeding patterns (fed, fasted, fed again). They falter when food is continuously available and insulin is perpetually elevated.

Understanding metabolism is understanding the trade-off between immediate energy needs and long-term energy storage, between the speed of energy extraction and its efficiency, between the precision of thermoregulation and its metabolic cost. These are the same trade-offs that shape evolution, ecology, and economics: the body is not a machine optimized for one goal, but a system optimized for survival under variable conditions.

---

**What would change my mind:** If experimental evidence showed that the electron transport chain produces ATP through a mechanism other than chemiosmotic coupling (proton gradient), or if thermoregulation were demonstrated to be primarily driven by behavioral mechanisms rather than physiological feedback, the reading here would require revision. The current evidence strongly supports the mechanisms described, but science remains open to refutation.

**Still puzzling:** I do not fully understand why the brain's addiction to glucose persists during starvation. Ketones supply 70% of energy after 3-4 days, but the liver continues gluconeogenesis to produce 30%, which seems metabolically wasteful. It may be that some brain functions (particularly rapid signal processing in certain neurons) truly do require glucose, or that the brain's partial reliance on glucose is a evolutionary holdover that was adaptive in environments where starvation was intermittent (not prolonged). The details remain unclear.

---

**Tags:** cellular respiration, ATP synthesis, thermoregulation, metabolic states, insulin, glucagon, glycolysis, Krebs cycle, electron transport chain, ketogenesis, gluconeogenesis, lipolysis, protein metabolism, urea cycle, basal metabolic rate, brown adipose tissue, thermoregulation, heat exchange

---

*Author: Nik Bear Brown*
*Revised: 2026-05-05*
*Status: Draft for review*
