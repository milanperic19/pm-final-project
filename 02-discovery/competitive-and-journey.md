# Competitive Analysis & Journey Map (Module 2)

## Responses
- **Role, who are you solving for? (the specific user segment or profile):** An experienced delivery driver working against the clock on dozens of stops a day, often in poor weather or with weak signal.
- **Goal, what is this user ultimately trying to achieve?:** To get through each stop as fast as possible, with the app keeping pace instead of slowing them down.
- **Friction, the main barrier (moment of misery) stopping them from succeeding:** Standing at a doorstep in the rain, package in one hand, tapping through three screens to mark a stop delivered (BUG-2055). He’s given up and now texts his dispatcher instead.
- **External tools, the outside platforms or tools the user is forced to use:** The phone’s text messaging, used to confirm deliveries to the dispatcher instead of marking them in the app, and a paper manifest carried as a backup in case the app fails.
- **The process, the 3 to 5 manual steps the user takes to get the job done:** Arrive at the stop and hand over the package.
Skip the three-screen Mark Delivered flow in the app.
Text the dispatcher that the stop is done, for example “Stop 14 delivered.”
Tick the stop off on the paper manifest.
Move to the next stop, leaving the dispatcher to update the system.
- **Core frustration, the exact moment the process feels most “broken”:** Standing at the doorstep in the rain, package in one hand, tapping through three separate screens just to confirm one delivery. A task that should take one tap holds the driver up at every stop, with downstream implications for efficiency and workload for the fleet coordinator.
- **The evidence, a specific quote or behavior from the research that proves this:** “To mark a stop delivered I tap through three screens. In the rain, at a doorstep, with a package in one hand. I’ve started just texting my dispatcher instead.” (Diego, delivery driver, UXR-01). The bug log backs this up: BUG-2055 rates three taps across three screens as High, calls it the top frontline complaint, and notes it “drives off-platform workarounds.”

The paper manifest comes from the focus group: five of seven drivers keep one “just in case the app dies” (UXR-12). Diego doesn’t mention it himself, so in the steps it stands for typical driver behaviour rather than his own words. If you want to stick strictly to Diego, drop step 4.
- **Your journey map, a shareable link, or the map file you committed (e.g. journey-map.html):** Velocity Driver Journey.html
