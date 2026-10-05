# 🎮 Unity Story Game Development Board

## 📊 Project Overview
- **Game Title**: [اختر الاسم]
- **Genre**: 2D Story Adventure
- **Platform**: PC (Windows)
- **Team**: 2 أشخاص
- **Start Date**: October 2026
- **Target Release**: June 2028 (20 شهر)
- **Total Story Duration**: ~6+ ساعات لعب

---

## 🎯 Project Vision
لعبة قصة 2D مع نظام اختيارات يؤثر على سير الأحداث. تحتوي على 6 فصول كاملة، حوارات متفرعة، وأنظمة save/load متقدمة.

---

## 📅 Timeline Overview

```
الشهر 1-2:    تعلم + تصميم          (Learning & Design)
الشهر 3-4:    المشروع الأساسي        (Project Foundation)
الشهر 5-8:    أنظمة القصة           (Story Systems)
الشهر 9-12:   الفصول 1-3           (Chapters Production)
الشهر 13-16:  الفصول 4-6           (More Chapters)
الشهر 17-18:  البولش والصوت         (Polish & Audio)
الشهر 19-20:  الاختبار والإصدار    (Testing & Release)
```

---

## 📊 Current Status

### Phase 1: Learning & Design ⏳ IN PROGRESS
- [ ] Unity fundamentals learned
- [ ] C# basics learned
- [ ] Story written & approved
- [ ] Characters designed
- [ ] Art style finalized
- [ ] Game design document completed

**Duration**: Month 1-2
**Target Completion**: [DATE]

---

### Phase 2: Foundation 🔄 PENDING
- [ ] Project structure created
- [ ] Git repository setup
- [ ] Player character created
- [ ] Basic movement implemented
- [ ] Simple dialogue system
- [ ] First test scene

**Duration**: Month 3-4
**Target Completion**: [DATE]

---

### Phase 3: Story Systems ⏳ PENDING
- [ ] Dialogue manager advanced
- [ ] Choice & branching system
- [ ] Scene transitions
- [ ] Save/Load system
- [ ] Data-driven dialogue
- [ ] Multiple save slots

**Duration**: Month 5-8
**Target Completion**: [DATE]

---

### Phase 4: Production (Chapters 1-3) ⏳ PENDING
- [ ] Chapter 1 complete
- [ ] Chapter 2 complete
- [ ] Chapter 3 complete
- [ ] All assets finished
- [ ] All animations done
- [ ] Playtime: ~1.5 hours

**Duration**: Month 9-12
**Target Completion**: [DATE]

---

### Phase 5: Production (Chapters 4-6) ⏳ PENDING
- [ ] Chapter 4 complete
- [ ] Chapter 5 complete
- [ ] Chapter 6 complete
- [ ] All endings finished
- [ ] All dialogue complete

**Duration**: Month 13-16
**Target Completion**: [DATE]

---

### Phase 6: Polish & Audio ⏳ PENDING
- [ ] Background music added
- [ ] Sound effects added
- [ ] Particle effects
- [ ] Screen transitions
- [ ] UI improvements
- [ ] Visual polish

**Duration**: Month 17-18
**Target Completion**: [DATE]

---

### Phase 7: Release ⏳ PENDING
- [ ] Internal testing
- [ ] Bug fixes
- [ ] Final build
- [ ] itch.io page
- [ ] Release announcement

**Duration**: Month 19-20
**Target Completion**: [DATE]

---

## 👥 Team & Responsibilities

### Person 1: [اسمك]
**Role**: Lead Programmer + Project Manager

**Responsibilities**:
- C# scripting
- Dialogue system development
- Save/Load system
- Scene management
- Bug fixing & optimization
- Git management

---

### Person 2: [اسم صاحبك]
**Role**: Artist + Story Writer

**Responsibilities**:
- Character design & sprites
- Background art
- Animations
- UI design
- Story writing
- Voice/Audio direction

---

## 📁 Project Structure

```
StoryGame/
│
├── Assets/
│   ├── Scripts/
│   │   ├── Dialogue/
│   │   │   ├── DialogueManager.cs
│   │   │   ├── DialogueParser.cs
│   │   │   └── ChoiceSystem.cs
│   │   ├── Player/
│   │   │   ├── PlayerController.cs
│   │   │   └── PlayerAnimator.cs
│   │   ├── UI/
│   │   │   ├── DialogueUI.cs
│   │   │   ├── MainMenuUI.cs
│   │   │   └── SettingsUI.cs
│   │   ├── Manager/
│   │   │   ├── GameManager.cs
│   │   │   ├── SceneManager.cs
│   │   │   ├── SaveSystem.cs
│   │   │   └── AudioManager.cs
│   │   └── Utilities/
│   │       └── Helper.cs
│   │
│   ├── Art/
│   │   ├── Characters/
│   │   │   ├── Player/
│   │   │   ├── NPC1/
│   │   │   └── [NPCs]
│   │   ├── Backgrounds/
│   │   │   ├── Chapter1/
│   │   │   ├── Chapter2/
│   │   │   └── [More]
│   │   ├── UI/
│   │   │   ├── Buttons/
│   │   │   ├── Backgrounds/
│   │   │   └── Icons/
│   │   └── Effects/
│   │       ├── Particles/
│   │       └── Animations/
│   │
│   ├── Audio/
│   │   ├── Music/
│   │   │   ├── Chapter1.wav
│   │   │   └── [More]
│   │   ├── SFX/
│   │   │   ├── UI_Click.wav
│   │   │   └── [More]
│   │   └── Voice/
│   │       └── [Optional]
│   │
│   ├── Scenes/
│   │   ├── MainMenu.unity
│   │   ├── Settings.unity
│   │   ├── Chapter1/
│   │   │   ├── Scene1.unity
│   │   │   ├── Scene2.unity
│   │   │   └── [More]
│   │   ├── Chapter2/
│   │   └── [More Chapters]
│   │
│   ├── Prefabs/
│   │   ├── Player.prefab
│   │   ├── DialogueBox.prefab
│   │   ├── ChoiceButton.prefab
│   │   └── [More]
│   │
│   ├── Data/
│   │   ├── Dialogue/
│   │   │   ├── Chapter1.json
│   │   │   ├── Chapter2.json
│   │   │   └── [More]
│   │   ├── GameData.json
│   │   └── Characters.json
│   │
│   └── Resources/
│       └── [Any runtime loaded assets]
│
├── Builds/
│   ├── v0.1/
│   ├── v0.2/
│   └── [Latest builds]
│
├── Docs/
│   ├── GameDesignDocument.md
│   ├── ArtStyleGuide.md
│   ├── StoryOutline.md
│   └── TechnicalGuide.md
│
├── README.md
├── CHANGELOG.md
├── .gitignore
└── ProjectSettings/
    └── [Unity project files]
```

---

## 🎯 Monthly Goals & Milestones

### Month 1-2: Learning & Planning
**Main Goal**: Understand Unity/C# + finalize game design

**Milestones**:
- [ ] M1: Unity & C# basics complete
- [ ] M2: Story design document approved
- [ ] M3: Character designs approved
- [ ] M4: Art style finalized

**Deliverables**:
- ✅ Game Design Document
- ✅ Story outline
- ✅ Character bios
- ✅ Art style guide
- ✅ Technical design

**Discord Post Template**:
```
📌 MONTH 1-2: Learning & Planning
🎓 Programming Progress
- [x] Week 1: Unity Setup & Interface
- [x] Week 2: C# Fundamentals
- [x] Week 3: 2D Mechanics
- [x] Week 4: UI & Input

📖 Design Progress
- [x] Story outline written
- [x] Characters created
- [x] Art style chosen
- [x] Game mechanics finalized

✅ Status: COMPLETE
📊 Documents Ready: 5/5
🎨 Art Concepts: Ready for production
```

---

### Month 3-4: Foundation
**Main Goal**: Create playable foundation

**Milestones**:
- [ ] M5: Basic character movement
- [ ] M6: Dialogue system working
- [ ] M7: First test scene playable
- [ ] M8: Save system functional

**Deliverables**:
- ✅ Player prefab
- ✅ Dialogue manager
- ✅ UI system
- ✅ Scene structure
- ✅ First playable build

**Discord Post Template**:
```
📌 MONTH 3-4: Project Foundation
🏗️ Development Progress
- [x] Project structure setup
- [x] Git configured
- [x] Player character created
- [x] Movement system implemented
- [x] Dialogue UI designed
- [x] Basic animations

🎮 Builds
- v0.1: Player can move & talk
- Playable: ~5 minutes

✅ Status: Foundation Ready
🚀 Ready for content production
```

---

### Month 5-8: Story Systems
**Main Goal**: Build choice/branching system

**Milestones**:
- [ ] M9: Choice system working
- [ ] M10: Branching logic complete
- [ ] M11: Save/Load system done
- [ ] M12: Multiple chapters testable

**Deliverables**:
- ✅ Dialogue branching
- ✅ Save/Load system
- ✅ Choice tracking
- ✅ Scene transitions
- ✅ Data files

**Discord Post Template**:
```
📌 MONTH 5-8: Story Systems
💾 Systems Implemented
- [x] Advanced dialogue system
- [x] Choice & branching
- [x] Save/Load with 5 slots
- [x] Scene management
- [x] Persistent data

📊 Content
- Dialogue format: JSON
- Branching paths: 3+ main routes
- Save system: Fully functional

✅ Status: Story engines ready
🎮 Build v0.2: Full story flow testable
```

---

### Month 9-12: Chapters 1-3
**Main Goal**: Produce first 3 complete chapters

**Milestones**:
- [ ] M13: Chapter 1 complete
- [ ] M14: Chapter 2 complete
- [ ] M15: Chapter 3 complete
- [ ] M16: Polish first chapters

**Deliverables**:
- ✅ 12+ scenes
- ✅ 200+ dialogue lines
- ✅ 20+ animations
- ✅ Playable 1.5 hours

**Discord Post Template**:
```
📌 MONTH 9-12: Chapters 1-3 Production

📖 Chapter 1: [Title]
- [x] Story complete
- [x] All scenes created (4 scenes)
- [x] Dialogue finished
- [x] Art assets done
- [x] Animations complete
⏱️ Playtime: ~15 minutes

📖 Chapter 2: [Title]
- [x] Story complete
- [x] All scenes created (5 scenes)
- [x] Dialogue done
- [x] Art assets done
- [x] Animations done
⏱️ Playtime: ~20 minutes

📖 Chapter 3: [Title]
- [x] Story complete
- [x] All scenes created (4 scenes)
- [x] Dialogue in progress
- [ ] Art assets in progress
- [ ] Animations pending
⏱️ Playtime: ~20 minutes

📊 Content Summary
- Total Scenes: 13+
- Total Dialogue: 200+
- Total Playtime: 1.5+ hours

🎮 Build v0.3: Chapters 1-3 complete
```

---

### Month 13-16: Chapters 4-6
**Same structure as Chapters 1-3**

**Deliverables**:
- ✅ Remaining 3 chapters
- ✅ All endings
- ✅ 3+ hours total content

---

### Month 17-18: Polish & Audio
**Main Goal**: Improve quality and add sound

**Deliverables**:
- ✅ Background music
- ✅ Sound effects
- ✅ Particle effects
- ✅ UI polish
- ✅ Optimization

---

### Month 19-20: Testing & Release
**Main Goal**: Release game

**Deliverables**:
- ✅ Final build
- ✅ itch.io page
- ✅ All bugs fixed
- ✅ Official release

---

## 📋 Weekly Task Template

### Week X: [Weekly Goal]
**Duration**: [DATE] - [DATE]

#### 👤 Person 1 Tasks
- [ ] Task 1
- [ ] Task 2
- [ ] Task 3

**Status**: Not Started / In Progress / Complete
**Progress**: 0% / 50% / 100%

---

#### 👤 Person 2 Tasks
- [ ] Task 1
- [ ] Task 2
- [ ] Task 3

**Status**: Not Started / In Progress / Complete
**Progress**: 0% / 50% / 100%

---

#### 🐛 Issues Found
- [ ] Issue 1
- [ ] Issue 2

#### ✅ Completed
- ✅ ...

#### 📝 Notes
- ...

---

## 🎮 Build History

| Build | Date | Chapter | Status | Notes |
|-------|------|---------|--------|-------|
| v0.0 | - | - | ⏳ Pending | Project setup |
| v0.1 | - | Foundation | ⏳ Pending | Player movement |
| v0.2 | - | Systems | ⏳ Pending | Story systems |
| v0.3 | - | 1-3 | ⏳ Pending | First 3 chapters |
| v0.4 | - | 4-6 | ⏳ Pending | Last 3 chapters |
| v0.5 | - | Alpha | ⏳ Pending | Polish |
| v1.0 | - | Release | ⏳ Pending | Final release |

---

## 🐛 Bug Tracking

### Critical Bugs
- [ ] Bug 1: [Description]
- [ ] Bug 2: [Description]

### Minor Bugs
- [ ] Bug 1: [Description]
- [ ] Bug 2: [Description]

### Fixed Bugs
- ✅ Bug 1: [Fixed in v0.X]

---

## 📊 Statistics

| Metric | Current | Target |
|--------|---------|--------|
| Lines of Code | 0 | 5000+ |
| Scenes | 0 | 20+ |
| Dialogue Lines | 0 | 500+ |
| Characters | 0 | 10+ |
| Background Assets | 0 | 30+ |
| Total Playtime | 0 hours | 6+ hours |
| Total Assets | 0 | 500+ |

---

## 📚 Resources & Links

### Learning
- Unity Learn: https://learn.unity.com/
- C# Microsoft Docs: https://docs.microsoft.com/en-us/dotnet/csharp/
- Brackeys Tutorials: https://www.youtube.com/c/Brackeys

### Tools
- Visual Studio Code: https://code.visualstudio.com/
- GitHub Desktop: https://desktop.github.com/
- Aseprite (Pixel Art): https://www.aseprite.org/
- Audacity (Audio): https://www.audacityteam.org/

### Publishing
- itch.io: https://itch.io/
- Steam: https://steampowered.com/

---

## 💬 Communication Channels (Discord Servers)

Create these channels in your Discord:

### 📌 Main Channels
- `#announcements` - مهم جداً
- `#general` - الحوارات العامة
- `#updates` - تحديثات يومية

### 👨‍💻 Development
- `#tasks` - المهام الجديدة
- `#in-progress` - المهام قيد العمل
- `#code-review` - مراجعة الكود
- `#bugs` - الأخطاء المكتشفة

### 🎨 Content
- `#art` - الفنون الجديدة
- `#animations` - الحركات الجديدة
- `#audio` - الموسيقى والصوت
- `#ui-design` - تصاميم الواجهة

### 📖 Story
- `#story-ideas` - أفكار القصة
- `#dialogue` - الحوارات الجديدة
- `#feedback` - الملاحظات

### 🎮 Testing
- `#playtesting` - اختبار اللعب
- `#builds` - روابط الإصدارات
- `#feedback` - التقييمات

### 📚 Resources
- `#tutorials` - الشروحات المفيدة
- `#assets` - مصادر الفنون والصوت
- `#references` - المراجع

### 🎉 Social
- `#wins` - النجاحات والإنجازات
- `#random` - أحاديث عشوائية
- `#off-topic` - خارج الموضوع

---

## ⏰ Schedule

### Daily
- Morning standup (quick update)
- End of day: commit code & upload assets

### Weekly
- Monday: Plan the week
- Friday: Review & retrospective

### Monthly
- Review phase progress
- Adjust timeline if needed

---

## 🎯 Key Success Factors

1. **Regular Communication**
   - Daily updates
   - Weekly sync meetings
   - Monthly reviews

2. **Clear Tasks**
   - Each task has owner
   - Each task has deadline
   - Each task has deliverable

3. **Version Control**
   - Commit frequently
   - Write clear commit messages
   - Review code before merging

4. **Testing**
   - Play daily
   - Report bugs immediately
   - Test all features

5. **Documentation**
   - Write comments in code
   - Keep README updated
   - Document design decisions

---

## 📝 Important Notes

### For Person 1 (Programmer):
- Start small, ship often
- Write comments for Person 2 to understand
- Test everything before merging
- Ask questions when unclear

### For Person 2 (Artist):
- Provide assets in organized folders
- Name assets clearly
- Ask for feedback on designs
- Keep art consistent

### For Both:
- Communicate daily
- Celebrate wins
- Help each other
- Stay motivated

---

## 🚀 Getting Started

### Week 1 Tasks (For Both)
1. [ ] Read this entire document
2. [ ] Set up Discord channels (as listed above)
3. [ ] Clone the repository
4. [ ] Set up Git locally
5. [ ] Create first branch
6. [ ] Plan Month 1 in detail

### First Meeting Agenda
- [ ] Agree on game idea
- [ ] Divide responsibilities
- [ ] Set up communication
- [ ] Plan first milestone
- [ ] Create first tasks

---

## 📞 Support

**Stuck on something?**
- Google the error
- Check Unity documentation
- Ask in Discord
- Restart Unity

---

**Made with ❤️ for game development**

*Last Updated: October 2026*
*Next Review: [DATE]*
