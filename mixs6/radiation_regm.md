
# Slot: radiation_regm


Information about treatment involving exposure of plant or a plant part to a particular radiation regimen; should include the radiation type, amount or intensity administered, treatment regimen including how many times the treatment was repeated, how long each treatment lasted, and the start and end time of the entire treatment; can include multiple radiation regimens

URI: [mixs.vocab:radiation_regm](https://w3id.org/mixs/vocab/radiation_regm)


## Domain and Range

None ->  <sub>OPT</sub> [String](types/String.md)

## Parents

 *  is_a: [environment field](environment_field.md)

## Children


## Used by

 * [Plant-associated](Plant-associated.md)
 * [Plant-associatedME](Plant-associatedME.md)
 * [Plant-associatedMIGSBacteria](Plant-associatedMIGSBacteria.md)
 * [Plant-associatedMIGSEukaryote](Plant-associatedMIGSEukaryote.md)
 * [Plant-associatedMIGSOrg](Plant-associatedMIGSOrg.md)
 * [Plant-associatedMIGSPlant](Plant-associatedMIGSPlant.md)
 * [Plant-associatedMIGSVirus](Plant-associatedMIGSVirus.md)
 * [Plant-associatedMIMAG](Plant-associatedMIMAG.md)
 * [Plant-associatedMIMARKSSpecimen](Plant-associatedMIMARKSSpecimen.md)
 * [Plant-associatedMIMARKSSurvey](Plant-associatedMIMARKSSurvey.md)
 * [Plant-associatedMISAG](Plant-associatedMISAG.md)
 * [Plant-associatedMIUVIG](Plant-associatedMIUVIG.md)

## Other properties

|  |  |  |
| --- | --- | --- |
| **Aliases:** | | radiation regimen |
| **Mappings:** | | MIXS:0000575 |
| **Comments:** | | Expected value: radiation type name;radiation amount;treatment interval and duration |
|  | | Preferred unit: rad, gray |
|  | | Occurrence: m |
|  | | Position: 1.0 |
|  | | This field is used uniquely in: plant-associated |
| **Examples:** | | Example(value='gamma radiation;60 gray;R2/2018-05-11T14:30/2018-05-11T19:30/P1H30M', description=None) |

