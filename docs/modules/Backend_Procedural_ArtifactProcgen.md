# Module: Backend/Procedural/ArtifactProcgen

## Table of contents

### Variables

- [mockCommon](Backend_Procedural_ArtifactProcgen.md#mockcommon)
- [mockEpic](Backend_Procedural_ArtifactProcgen.md#mockepic)
- [mockLegendary](Backend_Procedural_ArtifactProcgen.md#mocklegendary)
- [mockRare](Backend_Procedural_ArtifactProcgen.md#mockrare)

### Functions

- [artifactBiomeAndName](Backend_Procedural_ArtifactProcgen.md#artifactbiomeandname)
- [artifactName](Backend_Procedural_ArtifactProcgen.md#artifactname)
- [dateMintedAt](Backend_Procedural_ArtifactProcgen.md#datemintedat)
- [mockArtifact](Backend_Procedural_ArtifactProcgen.md#mockartifact)
- [mockArtifactWithRarity](Backend_Procedural_ArtifactProcgen.md#mockartifactwithrarity)

## Variables

### mockCommon

• **mockCommon**: `Artifact`

---

### mockEpic

• **mockEpic**: `Artifact`

---

### mockLegendary

• **mockLegendary**: `Artifact`

---

### mockRare

• **mockRare**: `Artifact`

## Functions

### artifactBiomeAndName

▸ `Const` **artifactBiomeAndName**(`artifact`): `string`

#### Parameters

| Name       | Type                      |
| :--------- | :------------------------ |
| `artifact` | `undefined` \| `Artifact` |

#### Returns

`string`

---

### artifactName

▸ `Const` **artifactName**(`artifact`): `string`

#### Parameters

| Name       | Type                      |
| :--------- | :------------------------ |
| `artifact` | `undefined` \| `Artifact` |

#### Returns

`string`

---

### dateMintedAt

▸ `Const` **dateMintedAt**(`artifact`): `string`

#### Parameters

| Name       | Type                      |
| :--------- | :------------------------ |
| `artifact` | `undefined` \| `Artifact` |

#### Returns

`string`

---

### mockArtifact

▸ `Const` **mockArtifact**(`rarity`, `artifactType?`, `planetBiome?`): `Artifact`

#### Parameters

| Name           | Type             | Default value            |
| :------------- | :--------------- | :----------------------- |
| `rarity`       | `ArtifactRarity` | `undefined`              |
| `artifactType` | `ArtifactType`   | `ArtifactType.Spaceship` |
| `planetBiome`  | `Biome`          | `Biome.WASTELAND`        |

#### Returns

`Artifact`

---

### mockArtifactWithRarity

▸ `Const` **mockArtifactWithRarity**(`rarity`, `artifactType?`, `planetBiome?`): `Artifact`

#### Parameters

| Name           | Type             | Default value            |
| :------------- | :--------------- | :----------------------- |
| `rarity`       | `ArtifactRarity` | `undefined`              |
| `artifactType` | `ArtifactType`   | `ArtifactType.Spaceship` |
| `planetBiome`  | `Biome`          | `Biome.WASTELAND`        |

#### Returns

`Artifact`
