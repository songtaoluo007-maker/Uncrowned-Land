# 数据字典（初始）

| 实体 | 核心字段 |
|---|---|
| Character | id, originalName, nickname, might, cunning, governance, diplomacy, personality, talent, loyalty, role |
| Party | id, leaderId, companionIds, troopStacks, food, payroll, morale, wounded |
| Settlement | id, ownerId, resources, population, buildings, developmentFocus, appointedCharacterIds |
| TechnologyProject | id, sourceProblem, optionId, leaderId, cost, duration, status |
| Contract | id, employerId, contractorId, type, payment, bonus, compensation, scope, status |
| SaveMetadata | saveVersion, createdAt, updatedAt, randomSeed |
