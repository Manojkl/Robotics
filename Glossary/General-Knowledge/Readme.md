# General Knowledge

## Number of degrees of Freedom in Human Body

The **human body** is often modeled as a system of interconnected rigid segments (limbs, head, torso, etc.) connected by joints that allow movement — and each joint adds specific **degrees of freedom (DOF)**.

---

### ✅ **Approximate Total DOF in the Human Body:**

The commonly cited number is:

> **244 degrees of freedom** (source: \[Cappozzo et al., 1995], \[Kerr & Roth, 1986], and biomechanical models used in robotics and animation)

---

### 📊 **Breakdown by Region** (based on anatomical joints):

| **Body Part**     | **Joint(s)**                | **Approx. DOF** | **Details**                                   |
| ----------------- | --------------------------- | --------------- | --------------------------------------------- |
| **Head/Neck**     | Cervical spine              | 3               | Flexion, lateral bending, rotation            |
| **Shoulders** (2) | Ball-and-socket joints      | 6 (3×2)         | Flexion/extension, abduction, rotation        |
| **Elbows** (2)    | Hinge                       | 2 (1×2)         | Flexion/extension                             |
| **Forearms** (2)  | Radioulnar joints           | 2 (1×2)         | Pronation/supination                          |
| **Wrists** (2)    | Condyloid                   | 4 (2×2)         | Flexion/extension, radial/ulnar deviation     |
| **Fingers** (10)  | Hinge + saddle              | 40+             | Each finger ≈ 4 DOF; thumb has more           |
| **Thumbs** (2)    | Saddle                      | 10 (5×2)        | Abduction, flexion, rotation, opposition      |
| **Torso/Spine**   | Intervertebral joints       | 3–6             | Flexion, bending, rotation                    |
| **Hips** (2)      | Ball-and-socket joints      | 6 (3×2)         | Flexion, abduction, rotation                  |
| **Knees** (2)     | Hinge (with small rotation) | 4 (2×2)         | Flexion/extension (+ passive rotation)        |
| **Ankles** (2)    | Hinge/Gliding               | 4 (2×2)         | Dorsiflexion/plantarflexion + small inversion |
| **Toes** (10)     | Hinge                       | 20              | Mainly flexion/extension                      |

---

### 🔢 **Summing it up:**

| **Region**           | **Approximate DOF** |
| -------------------- | ------------------- |
| Head & neck          | 3                   |
| Arms (incl. fingers) | \~80–90             |
| Torso/Spine          | 3–6                 |
| Legs (incl. toes)    | \~60–70             |
| **Total**            | **\~244**           |

---

### 📚 **Key References:**

1. **Kerr & Roth (1986)** – “Analysis of multifinger manipulation”
2. **Cappozzo et al. (1995)** – “Position and orientation in space of bones during movement”
3. **Winter, D. A. (2009)** – *Biomechanics and Motor Control of Human Movement*
4. **Zatsiorsky, V. M. (2002)** – *Kinetics of Human Motion*
5. **OpenSim** & **HUMANOS** biomechanical models

---

### 🚨 Note:

* These numbers vary based on **modeling assumptions** — some models consider micro-motions in spinal joints and finger sub-joints, while simpler ones reduce joint counts.
* **Functional DOF** may be fewer due to constraints like muscle limits or joint stiffness.

- On average, 10–30 DOF are used at a time, depending on the task.

The number of **possible combinations of human degrees of freedom (DOF)** is **astronomically large**, because:

1. The human body has **\~244 DOF**
2. Each DOF can take **many continuous values** (e.g., joint angles, positions)
3. DOFs can be used **independently or in combinations**

---

### 🔢 Let's break it down:

#### 🧠 If each DOF had only 2 states (e.g., "on/off" or two distinct positions):

* Number of combinations = $2^{244}$
* That’s over **3.8 × 10⁷³** combinations

> Just like 244 switches with 2 settings each → binary combinations.

But joints don’t just have 2 positions — they are **continuous**, not binary.

---

### 🔁 More realistic (simplified) model:

Assume each joint has **100 possible discrete positions** (e.g., angles in small increments):

> Combinations = $100^{244} = 10^{488}$

That’s a **googol to the 4.88 power** — a number so huge it exceeds the number of atoms in the observable universe (≈10⁸⁰).

---

### ✅ Real-world usable combinations:

* Many are **physiologically impossible** due to:

  * Joint limits
  * Muscle constraints
  * Pain/biomechanical inefficiencies
* Still, the **functionally viable combinations** are in the **billions to trillions**, easily.

---

### 🎯 Key Points:

* **Theoretical combinations** (mathematically): **10^488 or higher**
* **Biologically possible combinations**: fewer, but still **astronomically large**
* **Used in real tasks**: The brain simplifies this space using **motor synergies**, **muscle memory**, and **task constraints** — navigating only a **small region** of all possibilities efficiently.

Source: https://chatgpt.com/share/68505a78-0fc0-8007-a097-3e922c5b88bf

Date: 16/06/2025

# Human Eye: Resolution and Field of View (FOV)

The human eye has two key performance characteristics: **resolution** and **field of view (FOV)**. Here’s what they are and the best current estimates:

---

## 👁️ 1. Visual Resolution (Sharpness / Detail Perception)

- **Angular resolution** (the ability to distinguish two points):  
  ≈ **1 arcminute** (1/60 of a degree) in the **fovea**, the central part of the retina.

- **Pixel-equivalent resolution** (approximate for comparison with digital displays):  
  If you model the eye as a spherical retina capturing a 120° horizontal FOV and consider foveal detail:  
  🟢 **Theoretical equivalent**: ~**576 megapixels**  
  *But most of that detail is only in the center (fovea); peripheral vision is lower resolution.*

- **Realistically useful resolution** across wide vision:  
  Closer to **5–15 megapixels** when eye and brain integration is factored in.

---

## 👁️ 2. Field of View (FOV)

- **Monocular (one eye):**
  - Horizontal: ~**150°**
  - Vertical: ~**120°**

- **Binocular (both eyes combined):**
  - Horizontal FOV: ~**200°** total
    - ~**120°** with binocular overlap (depth perception zone)
    - Remaining ~**40°** on each side is peripheral vision from one eye
  - Vertical FOV: ~**135°**

---

## ⚡ Summary Table

| Parameter             | Value                                      |
|-----------------------|--------------------------------------------|
| Angular Resolution    | ~**1 arcminute** (fovea)                   |
| Megapixel Equivalent  | ~**576 MP** (theoretical), **5–15 MP** useful |
| Horizontal FOV        | ~**200°** (binocular), ~**150°** (monocular) |
| Vertical FOV          | ~**135°** (binocular), ~**120°** (monocular) |

---