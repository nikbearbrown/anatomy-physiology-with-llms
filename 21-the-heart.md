# Chapter 21 — The Heart: A Pump Built from Muscle
*Why One Pump Cannot Solve the Problem, and How Two Do.*

Here is a puzzle the body has to solve: you need one circuit running at high pressure to force blood through the capillary beds of the muscles and organs, and you need another circuit running at low pressure to move blood gently through the delicate air sacs of the lungs. One pump cannot do both. If the pump is powerful enough for the body, it will rupture the lungs. If it is gentle enough for the lungs, it will not reach the fingertips.

The heart's solution is so obvious in retrospect that it is easy to miss how elegant it is: become two pumps, running in series, sharing one electrical rhythm.

The right side of the heart pushes blood to the lungs at low pressure — the right ventricle wall is about three millimeters thick. The left side pushes blood to the body at high pressure — the left ventricle wall is about fifteen millimeters thick. Five times the muscle, because the left side faces five times the resistance. Both sides beat simultaneously, triggered by the same electrical signal. Both eject the same volume of blood per beat — they have to, because they are in series, and if one ejected more than the other, blood would accumulate somewhere and not get somewhere else.

This is the architecture. Everything else in this chapter is a consequence of it.

---

## The Problem of Pressure

The lung circuit operates at about 25 millimeters of mercury systolic. The systemic circuit operates at about 120. If you know nothing else about the heart, you can reconstruct the fact that there must be two separate pumping chambers with different wall thicknesses, because the wall thickness is what generates the pressure, and the pressures required are radically different.

<!-- → [IMAGE: cross-section diagram of the heart showing all four chambers — label right atrium, right ventricle (thin wall, ~3 mm), left atrium, left ventricle (thick wall, ~15 mm), interventricular septum; show pulmonary circuit path (right ventricle → pulmonary trunk → lungs → pulmonary veins → left atrium) and systemic circuit path (left ventricle → aorta → body → venae cavae → right atrium); annotate pressures: ~25 mmHg in pulmonary circuit, ~120 mmHg in systemic circuit; student should see why wall thickness difference is a direct consequence of pressure difference] -->

The two circuits run in parallel temporally — both sides contract and relax together — but in series functionally. Blood completes a full loop: right heart pushes deoxygenated blood to lungs; lungs oxygenate it; oxygenated blood returns to left heart; left heart pushes it to body; body uses the oxygen; deoxygenated blood returns to right heart. The output of the right side is the input to the left. The output of the left side is the input to the right.

Because they are in series, they must match volumes. If the left ventricle ejected 70 milliliters per beat and the right ejected 80, blood would accumulate in the lungs. In the short term, the lungs can buffer a small mismatch. In the long term, they cannot. Congestive heart failure is what happens when the left ventricle weakens and the right keeps pumping: fluid backs up in the pulmonary circuit, pressure rises in the lung capillaries, and fluid leaks through the capillary walls into the air sacs. The patient drowns, slowly, in their own accumulated fluid.

This is not a flaw in the design. It is a consequence of the series arrangement — a constraint that the healthy heart satisfies effortlessly but that becomes visible when one side fails.

---

## A Cell That Beats Alone

In the 1960s, a researcher isolated a single cardiac cell from a chicken embryo and kept it alive in a culture dish. No nervous system. No hormones. No neighboring cells. The cell began to beat spontaneously — depolarizing on its own, contracting, relaxing, waiting a moment, then doing it again. It kept its own rhythm without being told to.

This is autorhythmicity, and it is unique to cardiac muscle. Skeletal muscle will not do this. Smooth muscle will not. The cardiac muscle of the conductive system has it as an intrinsic electrical property.

Here is the mechanism. Most cells — including most cardiac cells — maintain a stable resting potential of around negative 90 millivolts. They sit there and wait to be stimulated. But the cells of the conductive system do something different: they have channels that allow a slow, steady leak of sodium into the cell even at rest. The membrane potential does not stay constant. It creeps upward, slowly, from about negative 60 millivolts toward negative 40. This slow drift is called the prepotential, or spontaneous depolarization. When it reaches about negative 40, voltage-gated calcium channels open, calcium rushes in, and the membrane depolarizes rapidly to about positive 15 millivolts. Then potassium channels open, potassium flows out, and the membrane repolarizes to negative 60 to begin the cycle again.

<!-- → [CHART: pacemaker cell action potential — x-axis: time in milliseconds; y-axis: membrane voltage (−60 mV to +15 mV); show prepotential (slow upward creep from −60 to −40 mV, label "Na⁺ leak channels open / slow spontaneous depolarization"), rapid depolarization phase (label "Ca²⁺ channels open"), peak (+15 mV), repolarization (label "K⁺ channels open"), return to −60 mV; compare to a second panel showing a contractile cell action potential with stable resting potential at −90 mV and steep rapid depolarization via Na⁺ channels; student should see the absence of a stable resting potential in pacemaker cells as the key distinction] -->

The rate of the prepotential determines the firing rate. Faster sodium leak means the threshold is reached sooner and the cell fires more often. Slower leak means fewer beats per minute.

The heart contains a population of these self-firing cells arranged in a hierarchy. The sinoatrial node sits in the upper wall of the right atrium, near where the superior vena cava enters. It has the fastest prepotential — it reaches threshold at 60 to 100 times per minute. The atrioventricular node, sitting at the boundary between atria and ventricles, fires at 40 to 60 times per minute. The Purkinje fibers, deep in the ventricular walls, fire at 20 to 40 times per minute.

In a healthy heart, the sinoatrial node dominates by reaching threshold before anyone else does. Its signal spreads outward and arrives at the slower cells before they have had time to reach their own threshold. The slower cells fire not by their own schedule but because they are recruited by the faster one. This is overdrive suppression: the fastest pacemaker dictates to all the others.

The consequence of this hierarchy matters clinically. If the SA node fails — from ischemia, fibrosis, or disease — it does not mean the heart stops. The AV node takes over as pacemaker, but at 40 to 60 beats per minute instead of 70. The Purkinje fibers can take over too, but at only 20 to 40 beats per minute. The patient is alive but slow. In severe cases, an artificial pacemaker is implanted to restore a normal rate.

---

## The Path of the Impulse

Once the SA node fires, the electrical impulse spreads across both atria like a wave on a pond. The atria depolarize and contract, squeezing blood down into the ventricles. Three internodal pathways carry the signal preferentially toward the AV node, but the atrial muscle also conducts it cell to cell.

At the AV node, something important happens: the impulse slows down. The cells of the AV node are small and conduct slowly. This creates a delay of about 100 milliseconds — long enough for the atria to finish contracting before the ventricles begin. Without this delay, both chambers would contract simultaneously, and the atrial contraction would not have time to finish filling the ventricles before they started to squeeze.

After the delay, the impulse accelerates again. It enters the bundle of His, a tract of fast-conducting cells that runs down the interventricular septum. The bundle splits into left and right branches, each running down one side of the septum. From there, the signal enters the Purkinje fibers — the fastest-conducting cells in the heart — which distribute it through the ventricular myocardium. The apex of the heart activates first, then the signal spreads upward toward the base. This bottom-to-top activation is intentional: the ventricles wring blood upward toward the outflow tracts, not downward and out through the bottom.

The whole sequence — SA node fires, atria contract, AV delay, ventricles contract — takes about 225 milliseconds.

<!-- → [IMAGE: conduction system diagram of the heart — label SA node (right atrial wall near superior vena cava), three internodal pathways (anterior, middle, posterior), AV node (at boundary of atria and ventricles), bundle of His (entering interventricular septum), left and right bundle branches (running down each side of septum), Purkinje fibers (spreading through ventricular myocardium); annotate intrinsic rates: SA node 60–100 bpm, AV node 40–60 bpm, Purkinje fibers 20–40 bpm; show direction of impulse spread with arrows; note the AV delay (~100 ms); student should see the hierarchy as a physical pathway with a built-in bottleneck at the AV node] -->

If you attach electrodes to the skin and record the summed electrical activity of the heart, you get an electrocardiogram. The P wave is atrial depolarization. The QRS complex is ventricular depolarization — rapid, prominent, because the ventricular mass is large. The T wave is ventricular repolarization. The intervals between these waves are as diagnostically useful as the waves themselves. A prolonged PR interval means the AV node is conducting slowly. A wide QRS means the impulse is not traveling the normal fast pathway through the bundle branches. An absent P wave means the rhythm is not originating in the SA node. Each pattern is a message about where the system has broken down.

---

## The Mechanics of One Beat

Now to what the electrical signal actually accomplishes: mechanical work. A single cardiac cycle — one beat — has four phases, and understanding them requires tracking pressure and volume simultaneously.

Start at the beginning of filling. The ventricle is relaxed. Pressure inside it is low. Pressure in the atrium is slightly higher, so blood flows passively from atrium to ventricle. This passive filling accounts for about 70 percent of ventricular volume. The atrium then contracts — the atrial kick — adding the remaining 30 percent. The ventricle is now at its maximum volume: the end-diastolic volume, about 130 milliliters in the left ventricle.

Now the ventricle begins to contract. Pressure inside rises rapidly. When ventricular pressure exceeds atrial pressure, blood tries to flow back into the atrium. The mitral valve snaps shut — this is the first heart sound, the "lub." But ventricular pressure has not yet exceeded aortic pressure, so the aortic valve is still closed. The ventricle is contracting, but blood has nowhere to go. Volume stays constant while pressure continues to rise. This is isovolumic contraction.

When ventricular pressure finally exceeds aortic pressure — about 80 millimeters of mercury — the aortic valve opens. Blood begins to eject. The ventricle continues to contract, volume decreases, and pressure rises further to about 120 millimeters of mercury at peak ejection. The ventricle ejects roughly 70 milliliters — the stroke volume — leaving about 60 milliliters behind. The ratio of ejected to total volume is the ejection fraction: 70 divided by 130, or about 54 percent. Normal is 55 to 70 percent. In a failing heart, this number falls.

Then contraction ends. Pressure inside the ventricle drops. When it falls below aortic pressure, the aortic valve snaps shut — the second heart sound, the "dub." Again blood has nowhere to go, and volume stays constant while pressure falls. This is isovolumic relaxation.

When ventricular pressure drops below atrial pressure, the mitral valve opens, passive filling begins again, and the cycle repeats.

<!-- → [CHART: pressure-volume loop of the left ventricle — x-axis: ventricular volume (mL, from ~60 to ~130); y-axis: ventricular pressure (mmHg, from 0 to ~120); label the four phases as segments of the loop: (1) filling — horizontal segment at low pressure, volume increasing left to right; (2) isovolumic contraction — vertical segment, volume constant, pressure rising; (3) ejection — top segment, volume decreasing, pressure rising then falling; (4) isovolumic relaxation — vertical segment, volume constant, pressure falling; label EDV (~130 mL), ESV (~60 mL), stroke volume (difference = ~70 mL); mark points where mitral valve opens and closes, and where aortic valve opens and closes; student should see each valve event as the point where one phase transitions to the next] -->

Four phases: filling, isovolumic contraction, ejection, isovolumic relaxation. Two valve closures: the "lub" when the mitral closes, the "dub" when the aortic closes. Every sound, every pressure change, every volume change follows necessarily from the architecture described above.

---

## What Governs the Output

Cardiac output — the volume pumped per minute — is the product of two numbers: stroke volume times heart rate. To increase output, you can increase either one, or both.

Three factors govern stroke volume.

The first is preload: the volume of blood in the ventricle at the moment contraction begins, which is the end-diastolic volume. More blood in the ventricle means the muscle fibers are stretched more before they contract. Cardiac muscle, like skeletal muscle, follows a length-tension relationship: a stretched fiber generates more force than a slack one — up to a point. This is the Frank-Starling relationship, and it is the reason the heart automatically adjusts its output to match venous return. If more blood flows back from the body, the ventricle fills more, the fibers stretch more, they contract harder, and more blood is ejected. The heart responds to increased demand without needing a signal from the nervous system.

The second is afterload: the pressure the ventricle must overcome to eject blood. For the left ventricle, afterload is essentially aortic pressure. For the right, it is pulmonary arterial pressure. Higher afterload means the ventricle must generate more pressure before the outflow valve opens, which takes more time and energy. In chronic hypertension, afterload is persistently elevated, and the left ventricle responds by adding muscle — hypertrophy. A thicker wall is stronger, but it is also stiffer and fills more poorly. The treatment for the pressure creates a new problem in the relaxation phase.

The third is contractility: the intrinsic strength of contraction at a given preload and afterload. Sympathetic stimulation increases contractility through norepinephrine binding to beta-adrenergic receptors in the cardiac myocytes. Hypoxia, acidosis, and certain drugs decrease it. During exercise, sympathetic activation increases both heart rate and contractility, while elevated venous return increases preload. All three variables shift together, and cardiac output can increase four to five fold above resting levels.

A worked example makes this concrete. At rest, a heart beats at 70 times per minute with a stroke volume of 70 milliliters. Cardiac output is 4.9 liters per minute. During maximal exercise, heart rate rises to 180 and stroke volume rises to 130 milliliters. Cardiac output is 23.4 liters per minute — nearly five times the resting value.

There is a ceiling. At very high heart rates — above 180 or so — diastolic filling time becomes so short that the ventricle does not have enough time to fill before the next contraction. Preload drops. Stroke volume falls. Cardiac output plateaus and can even decline. This is why simply having a very fast heart rate is not the same as having a very high cardiac output: the relationship breaks down at the extremes.

---

## The System in Context

The heart does not operate in isolation. The autonomic nervous system continuously modulates the SA node's firing rate. Parasympathetic input through the vagus nerve releases acetylcholine onto the SA node, slowing the rate of spontaneous depolarization and reducing heart rate. Sympathetic input releases norepinephrine, steepening the slope of the prepotential and increasing heart rate. At rest, the vagus nerve dominates, which is why the resting heart rate is 60 to 80 beats per minute rather than the SA node's intrinsic rate of 100 to 120.

When you stand up quickly, blood pools in your legs, venous return falls, cardiac output drops, blood pressure falls. Baroreceptors in the carotid artery and aortic arch detect the pressure drop and signal the medulla. The medulla withdraws parasympathetic tone and increases sympathetic tone. Heart rate rises. Contractility increases. The adjustment happens in under a second.

The hormonal layer adds duration. Epinephrine from the adrenal medulla reinforces the sympathetic effect, but through the bloodstream — slower to rise, slower to clear. During sustained exertion or genuine emergency, circulating epinephrine keeps heart rate and contractility elevated for minutes after the initial neural response.

Metabolism closes the loop from below. Exercising muscle produces carbon dioxide and metabolic acids. These shift blood chemistry toward acidity, which chemoreceptors detect and translate into increased sympathetic drive. The same muscle also releases adenosine as it breaks down ATP; adenosine dilates local capillaries, reducing downstream vascular resistance. Lower resistance means lower afterload for the heart, making ejection easier and increasing cardiac output even without changing heart rate or contractility directly.

What emerges from all of this is a system that can run continuously for seventy or eighty years, adjust its output moment-to-moment over a five-fold range, and do so without any single point of failure — because every layer of regulation has a backup, and the heart's own electrical rhythm is the most fundamental backup of all.

---

## Exercises

**Warm-up**

1. A patient's echocardiogram shows an end-diastolic volume of 140 mL and an end-systolic volume of 80 mL. Calculate the stroke volume and ejection fraction. Is the ejection fraction within normal range? What does an ejection fraction below 40% tell a clinician about systolic function? *(Tests: stroke volume and ejection fraction calculation, clinical interpretation)*

2. Explain why the right ventricle wall is thinner than the left ventricle wall, using the relationship between wall thickness, muscle force generation, and the pressure each side must produce. What would happen over time if both ventricles faced the same afterload? *(Tests: pressure-wall thickness relationship, afterload, hypertrophy mechanism)*

3. A researcher blocks all sympathetic and parasympathetic input to an isolated heart. The heart continues to beat, but at a rate of about 100 beats per minute instead of the typical resting rate of 70. Explain both findings: why the heart still beats, and why the rate is higher than the normal resting rate. *(Tests: autorhythmicity, SA node intrinsic rate, parasympathetic tone at rest)*

**Application**

4. During atrial fibrillation, the atria contract chaotically and the "atrial kick" is lost. A patient with atrial fibrillation complains of fatigue and reduced exercise tolerance. Using the concept of preload and the Frank-Starling relationship, explain why loss of the atrial kick reduces cardiac output, and predict whether the effect would be more pronounced at rest or during exercise. *(Tests: atrial kick as contribution to preload, Frank-Starling, exercise physiology)*

5. A patient with chronic hypertension (persistently elevated aortic pressure) develops left ventricular hypertrophy — the left ventricle wall thickens. Trace the causal chain from elevated afterload to hypertrophy. Then explain why this hypertrophied ventricle, despite being stronger in systole, often leads to diastolic dysfunction. *(Tests: afterload mechanism, compensatory hypertrophy, stiffness and diastolic filling)*

6. A marathon runner has a resting heart rate of 45 beats per minute and a resting stroke volume of 100 mL. Calculate her resting cardiac output. A sedentary person of the same age has a resting heart rate of 75 bpm and a stroke volume of 65 mL. Calculate his cardiac output. The outputs are nearly equal — so what does the athlete's lower heart rate actually reflect about the efficiency of her cardiovascular system? *(Tests: cardiac output calculation, stroke volume vs. heart rate trade-off, training adaptations)*

**Synthesis**

7. A patient suffers a myocardial infarction that damages the posterolateral left ventricle. Three months later, an ECG shows a wide QRS complex. Explain: (a) why damage to the ventricular myocardium produces a wide QRS; (b) what the wide QRS reveals about how the impulse is now traveling through the ventricle; and (c) why this altered conduction pattern might reduce stroke volume even if the remaining myocardium is contractile. *(Tests: ECG interpretation, conduction pathway, ventricular synchrony and mechanical efficiency)*

8. At very high heart rates (above 200 bpm), cardiac output paradoxically decreases despite the faster rate. Explain the mechanism using the concepts of diastolic filling time, preload, and the Frank-Starling relationship. Then predict how a trained athlete's larger ventricular volume (from cardiac remodeling) would affect the heart rate at which output begins to decline, compared to an untrained person. *(Tests: diastolic filling time, Frank-Starling at high rates, training-induced cardiac remodeling)*

**Challenge**

9. A drug is developed that selectively blocks the funny current (If) — the sodium leak channels responsible for the pacemaker prepotential — in SA node cells but has no effect on AV node or Purkinje fiber channels. At a low dose, the drug slows the SA node's prepotential slope, reducing heart rate from 75 to 55 bpm. At a high dose, the SA node no longer reaches threshold. Predict what happens to heart rhythm at the high dose: (a) which pacemaker takes over, (b) at what rate, (c) what the QRS complex would look like on an ECG if the AV node becomes the pacemaker vs. if the Purkinje fibers become the pacemaker, and (d) why the P wave would disappear or change. Explain each prediction from the mechanism of overdrive suppression and the conduction pathway anatomy. *(Tests: pacemaker hierarchy, overdrive suppression, ECG correlates of conduction pathway, escape rhythms)*

---

*Byline: Nik Bear Brown*
