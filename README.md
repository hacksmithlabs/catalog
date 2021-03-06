# catalog

##### Weave Product

| Field       | Type                  | Description                                       |
|-------------|-----------------------|---------------------------------------------------|
| name        | string                |                                                   |
| strain      | string                | ID of matching strain if that exists              |
| description | string                |                                                   |
| brand       | string                |                                                   |
| subcategory | string                | See Category Table                                |
| category    | string                | concentrate, edible, flower, merchandise, topical |
| id          | string                | UUID                                              |
| type        | string                | cannabis, hemp, other                             |
| variants    | array of Weave Variant|                                                   |
| experience  | string                | focus, unwind, sleep, energize etc                |
| effects     | Array of strings      | Sleepy, hungry, pain relief, happy, relaxed       |

##### Weave Variant

| Field     | Type                | Description                                 |
|-----------|---------------------|---------------------------------------------|
| name      | string              |                                             |
| price     | float               | Base retail price                           |
| cpc       | string              | Weave cannabis product code                 |
| type      | string              | unit, loose, shake, prepack                 |
| potency   | Object compounds and mg| {thc: 100, cbd: 20, cbn: 4}              |
| count     | number              | Quantity in package                         |
| UOM       | string              | ct, oz, ml, g                               |

##### Category Structure

| Category    | Subcategories                                                                                                           |
|-------------|-------------------------------------------------------------------------------------------------------------------------|
| concentrate | syringe, crumble, crystalline, cured extract, shatter, tincture, resin, budder, hash, solventless, distillate, wax, kief, live extract, oil, cartridge |
| edible      | snack, drink, cooking, capsule, tincture, candy, chocolate, baked                                                      |
| flower      | indica, sativa, clone, other, seeds, hybrid, caviar                                                                     |
| merchandise | vape, glass, accessory, clothing, misc                                                                                  |
| topical     | bath, ointment, oil, lotion, patch, salve, balm   
