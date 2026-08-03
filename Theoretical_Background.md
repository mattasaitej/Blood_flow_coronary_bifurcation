## Blood Flow in Coronary Arteries

The coronary arteries supply oxygen-rich blood to the heart muscle (myocardium), ensuring it receives the oxygen and nutrients required for continuous contraction. The two main coronary arteries are the **Right Coronary Artery (RCA)** and the **Left Coronary Artery (LCA)**. The LCA further divides into the **Left Anterior Descending (LAD)** and **Left Circumflex (LCX)** arteries.

Blood flow within the coronary arteries is **pulsatile**, varying throughout the cardiac cycle due to the rhythmic contraction and relaxation of the heart. During systole, the heart generates a pressure wave that drives blood through the arteries, while during diastole, the elastic recoil of the arterial walls helps maintain continuous blood flow, a phenomenon known as the **Windkessel effect**.

Under normal physiological conditions, coronary blood flow is predominantly **laminar**, producing smooth streamlines and efficient transport of oxygen to the myocardium. However, changes in arterial geometry, such as branching or narrowing, can disturb the flow, leading to variations in velocity, pressure, and wall shear stress. These hemodynamic changes play a crucial role in the development of cardiovascular diseases and are therefore important to study using Computational Fluid Dynamics (CFD).

---

## Coronary Artery Bifurcation

A coronary artery bifurcation is the region where a parent coronary artery divides into two daughter branches. One of the most significant examples is the division of the **Left Coronary Artery (LCA)** into the **Left Anterior Descending (LAD)** and **Left Circumflex (LCX)** arteries.

Bifurcations introduce geometric complexity that alters blood flow patterns. As blood passes through the branching region, changes in vessel direction and cross-sectional area produce variations in velocity and pressure. Flow separation and recirculation zones may develop, resulting in regions of **low wall shear stress (WSS)** and increased **residence time**.

These disturbed flow conditions promote the accumulation of lipids, inflammatory cells, and platelets along the vessel wall, making bifurcation regions highly susceptible to **atherosclerotic plaque formation**. Conversely, extremely high wall shear stress can contribute to plaque rupture and thrombus formation. Because of these unique hemodynamic characteristics, coronary bifurcations are among the most frequently studied regions in cardiovascular CFD analyses.

---

## Blood Rheology

Blood is a complex biological fluid composed of **plasma**, **red blood cells (RBCs)**, **white blood cells (WBCs)**, and **platelets**. Unlike simple fluids such as water, blood exhibits **non-Newtonian** behavior because its viscosity varies with the applied shear rate.

At **high shear rates**, such as those found in large arteries, red blood cells deform and align with the direction of flow, causing blood to behave approximately as a Newtonian fluid with nearly constant viscosity. At **low shear rates**, red blood cells tend to aggregate into structures known as *rouleaux*, increasing the apparent viscosity and enhancing the non-Newtonian characteristics of blood.

This shear-thinning behavior can be represented using rheological models such as the **Casson model** and the **Carreau–Yasuda model**. However, for simulations involving large coronary arteries, blood is often approximated as a Newtonian fluid because the high shear rates minimize non-Newtonian effects while significantly reducing computational complexity.

Understanding blood rheology is essential for accurately predicting important hemodynamic parameters such as velocity, pressure distribution, wall shear stress, and flow separation, all of which influence the progression of coronary artery disease.
