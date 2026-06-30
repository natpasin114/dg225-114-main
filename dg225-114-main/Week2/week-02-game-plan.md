```mermaid
mindmap
 root((Pac-Man))
  Theme
   เขาวงกต
   อาเขตยุค 80
   Retro / Nostalgia
  Mechanics
   เดินในเขาวงกต
   กิน Pellet
   Power Pellet
   Lives System
  Content
   ผีศัตรู 4 ตัว
   Blinky / Pinky / Inky / Clyde
   ผลไม้โบนัส
  Audience
   ผู้เล่น Casual
   ทุกวัย
   ผู้ที่ชอบแข่งทำคะแนน
  Art Style
   Pixel Art 8-bit
   Color Palette สดใส
   Simple Shapes
```

```mermaid
quadrantChart
    title Pac-Man — Feature Prioritization
    x-axis Low Effort --> High Effort
    y-axis Low Impact --> High Impact
    quadrant-1 Quick Wins 
    quadrant-2 Major 
    quadrant-3 Nice to Have
    quadrant-4 Reconsider
    Maze Movement: [0.3, 0.95]
    Pellet & Score System: [0.35, 0.92]
    Ghost AI : [0.65, 0.88]
    Power Pellet: [0.5, 0.85]
    Lives / Game Over: [0.25, 0.80]
    Bonus Fruit: [0.45, 0.70]
    High Score Display: [0.4, 0.60]
    Level Difficulty Scaling: [0.7, 0.75]
    Online Leaderboard: [0.85, 0.45]
```


---
### MVP (Minimum Viable Product) — ทำให้เสร็จใน 6 สัปดาห์:

**Quadrant 1 (Quick Wins)**: ทำ ASAP
- ✅ Maze Movement
- ✅ Pellet & Score System
- ✅ Lives / Game Over
- ✅ High Score Display

**Quadrant 2 (Major Features)**: Core of the game
- ✅ Ghost AI (Basic ก่อน)
- ✅ Power Pellet
- 🔄 Bonus Fruit (ถ้ามีเวลา)

**Quadrant 3 (Nice to Have)**: ตัดหรือทำทีหลัง
- ❌ Level Difficulty Scaling (ยาก + ประโยชน์น้อย)
- ❌ Advanced Ghost AI (ไว้ Post-Launch)

**Quadrant 4**: ไม่มีตัวอย่างที่เหมาะสม (ไม่ควรเอามา)
- ❌ Online Leaderboard (Effort สูง Impact ต่ำ)

**สรุป MVP Scope**:
- **ต้องทำ**: Quadrant 1 + Quadrant 2 ทั้งหมด (7 features)
- **ถ้ามีเวลา**:Level Scaling
- **ตัดออก**: Online Leaderboard, Advanced AI
---

```mermaid
gantt
 title Pac-Man — Production Timeline (6 สัปดาห์)
 dateFormat YYYY-MM-DD

 section Pre-Production
 Concept & GDD :done, c1, 2026-07-06, 5d
 Prototype & Asset Planning : done, c2, after c1, 3d

 section Production (Week 1-3)
 Maze Movement :active, p1, after c2, 7d
 Ghost AI : p3, after p1, 5d
 Pellet & Score : p2, after p1, 8d

 section Production (Week 4-5)
 Power Pellet Mechanic : p4, after p3, 5d
 Bonus Fruit System : p5, after p2, 5d
 Pellet & Score : p6, after p4, 3d

 section Production (Week 6)
 High Score Display :p7, after p6, 2d

 section Post
 QA & Bug Fix : q1, after p3, 5d
 Release Build :milestone, m1, after q1, 0d
```


---
### Timeline Breakdown:

**Week 1 (Jul 6–12)**: Pre-Production & Foundation
- Concept, GDD, Prototype → Maze Movement (foundation)

**Week 2 (Jul 13–19)**: Core Mechanics
- Pellet System, Ghost AI (คู่ขนาน)

**Week 3 (Jul 20–26)**: Power-up & Bonus
- Power Pellet, Bonus Fruit

**Week 4 (Jul 27–Aug 2)**: Polish
- Lives System, Score Display

**Week 5-6 (Aug 3–15)**: QA & Release
- Alpha → Bug Fix → Final QA → Gold Master 

**Milestone**:
- **Alpha Build** (end of Week 4): ทั้ง MVP feature พร้อม
- **Gold Master** (end of Week 6): เกมพร้อมปล่อย
---
