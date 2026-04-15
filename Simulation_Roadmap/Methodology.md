Roadmap de Simulation / Simulation Roadmap
Objectif : Modéliser le Flux / Objective: Modeling the Flow

FR : Le but est de remplacer les simulateurs N-corps classiques (basés sur la gravité) par des simulateurs de mécanique des fluides (CFD) intégrant le champ scalaire ϕ.
EN: The goal is to replace classic N-body simulators (gravity-based) with Computational Fluid Dynamics (CFD) simulators integrating the ϕ scalar field.
1. Le Moteur Physique / The Physics Engine

FR : Nous utilisons une version adaptée des équations de Navier-Stokes incluant notre terme source galactique Sgal​.
EN: We use an adapted version of the Navier-Stokes equations including our Sgal​ galactic source term.
ρϕ​(∂t∂vϕ​​+(vϕ​⋅∇)vϕ​)=−∇P+η∇2vϕ​+fext​

    η (Viscosity) : Paramètre clé remplaçant la Matière Noire pour stabiliser les bras spiraux. / Key parameter replacing Dark Matter to stabilize spiral arms.

    −∇P (Pressure Gradient) : La force motrice venant des Vides vers les Puits. / The driving force coming from the Voids toward the Sinks (Sinks).

2. Méthode SPH (Smoothed Particle Hydrodynamics)

FR : Pour simuler la condensation du flux en matière, nous utilisons la méthode SPH. Chaque particule représente un paquet de flux ϕ qui peut changer de phase (devenir "matière" quand la densité dépasse un seuil).
EN: To simulate the condensation of the flow into matter, we use the SPH method. Each particle represents a packet of ϕ flux that can change phase (becoming "matter" when density exceeds a threshold).
3. Prédictions de Simulation / Simulation Predictions
Feature / Caractéristique	Expected Result (TGF) / Résultat Attendu	Observation / Preuve Réelle
Rotation Curve	Flat due to η (Viscosity).	Observed in all spiral galaxies.
Fermi Bubbles	Automatic ejection at high Sgal​.	Observed by Fermi-LAT (Gamma rays).
Spiral Arms	Density waves in the ϕ flow.	Observed (Grand Design Spirals).
Tidal Tails	Fluid stripping, not just gravity.	Observed in merging galaxies.

📝 Conclusion de la Roadmap / Roadmap Conclusion

FR : En ajustant uniquement la densité ρϕ​ et la viscosité η, nous devrions être capables de reproduire l'intégralité de la séquence de Hubble sans ajouter de masse invisible.
EN: By adjusting only the ρϕ​ density and the η viscosity, we should be able to reproduce the entire Hubble sequence without adding any invisible mass.
