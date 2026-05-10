# Idea Parking Lot

> Store new ideas that may impact the existing architecture, avoiding disruption to current discussion flow. Created and managed by the main controller, all sub-skills can write.

---

## [Idea Staging Area]

| ID | Idea Description | Proposed Time | Proposed Stage | Impact Scope | Disposition Status | Disposition Decision | Reason |
|-----|---------|---------|---------|---------|---------|---------|------|
| I-001 | [灵感描述] | [日期] | [阶段名] | Architecture-level/Feature-level/Experience-level | Pending | - | - |

---

## [Idea Disposition Process]

### Trigger Timing
- At the end of each stage (e.g., after blueprint co-creation, after tech stack selection)
- When the founder actively requests
- Before final chapter delivery

### Disposition Steps

1. **Impact Assessment**
   - **Architecture-level**: Requires modifying system architecture or adding new microservices
   - **Feature-level**: Adding new feature modules on existing architecture
   - **Experience-level**: Only affects UI/interaction, no architecture impact

2. **Disposition Recommendation**
   - **Adopt**: Include in current version or future version roadmap
   - **Shelve**: Record for future reference, wait for right timing
   - **Discard**: Clearly record reason for discarding, avoid repeated proposals

3. **Founder Confirmation**
   - Script: "Boss, there are [N] ideas in the Idea Parking Lot. I recommend [Adopt/Shelve/Discard] this [idea name], because [reason]. What do you think?"

4. **Archive Update**
   - Update the disposition status in the Idea Parking Lot
   - If adopted, synchronize updates to related documents (feature list, roadmap, etc.)

---

## [Disposed Ideas Archive]

> Record disposed ideas for traceability

| ID | Idea Description | Disposition Decision | Disposition Time | Disposition Reason | Follow-up Action |
|-----|---------|---------|---------|---------|
| I-XXX | [描述] | Adopt/Shelve/Discard | [日期] | [理由] | [动作] |

---

## Usage Instructions

### Sub-skill Writing Guidelines
1. When discovering disruptive ideas, immediately record in `[Idea Staging Area]`
2. Fill in complete information: description, proposed time, proposed stage, impact scope
3. Default disposition status is "Pending"
4. Do not decide disposition independently, wait for main controller to handle uniformly

### Main Controller Disposition Guidelines
1. Regularly check the Idea Parking Lot
2. Execute disposition process at key milestones
3. Update status and archive after disposition
4. Synchronize adopted ideas to related documents

---

## Update Log

| Date | Update Content | Updated By |
|-----|---------|-------|
| [日期] | [内容] | [AI/创始人] |
