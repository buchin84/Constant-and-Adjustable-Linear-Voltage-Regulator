# Modules-Week-3-Assignment

In this assignment, two linear voltage regulators have to be created. One must be adjustable, and the other needs to be constant. These can be created with the schematic layout in DipTrace, and then a hierarchy block can be created for both to easily use them for other projects.

The LM317LBZRAG was used for the adjustable regulator, the datasheet for the part is here which contains the schematic: https://www.digikey.com/en/products/detail/on-semiconductor/LM317LBZRAG/9086547
This is a low current, 3 pin regulator which only requires two resistors to set the output voltage. The simplified application schematic on the first page of the datasheet was replicated in Diptrace. After replicating the schematic, the entire schematic can be condensed into a hierarchy block to be used for bigger projects. This is done by selecting objects -> place block. This block can be imported into a new sheet on the same file or saved and imported into a new project in DipTrace. The values of all the components in the circuit can be seen in the Diptrace file and on the datasheet.

The LM78L05ACZ was used for the constant voltage regulator, the datasheet for the part is here which contains the schematic: https://www.ti.com/lit/ds/symlink/lm7800.pdf?ts=1643989821752&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252FLM7800%253FkeyMatch%253D%2526tisearch%253Dsearch-everything%2526usecase%253Dpartmatches
This 3 pin regulator is capable of outputting current up to 1.5A and has 3 fixed voltage options of 5V, 12V, and 15V. The fixed regulator schematic was deisgned to be simple, only requiring two capacitors coming from the input and output. The schematic was designed The same process was followed for recreating the schematic and exporting it as a hierarchy block. 
