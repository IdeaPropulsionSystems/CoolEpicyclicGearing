# CoolEpicyclicGearing
Some resources for designing a special high-ratio planetary gearing system.
About Split-Ring Compound-Planet Epicyclic Gear Sets

Interesting Gear Arrangement:
This type of gear box is a little obscure, but I have found it to turn up in antique clock gearing, in auto-mirror motor gearboxes, and in avionic motors for moving aircraft wing flaps. It's best features are that it lends itself to be flat, highly compact for the ratios possible, and strong because of how much tooth engagement is maintained. Probems include difficulty in making gears of such similar but *slightly different* pitch, and just the complexity of holding all these compound planets square with respect to the annulus gears - Applying large torque to the output annulus tends to try to make the planets 'lean' in the direction of the torque, jamming the teeth, reducing the actual power output. That said, it is a very practical gear system to create using plastic 3D printers because the gear count is very small for such high ratios. Also, printing gears very flat reduces the torque-planet-jamming problem I mentioned above. 

The Parts of this System:
Talking about this particular type of planetary gear arrangement, the 'split-ring' just means that there are two internal annulus gears. One gear is stationary with respect to the gearbox's housing, and the other annulus rotates. The input shaft for this gear arrangement drives a single sun gear at the center of the fixed annulus. Some number of planet gears are arranged radially around the sun so that they engage both the sun gear and the fixed planet gear. These planet gears orbiting the sun gear are co-axially conjoined with a set of planet gears that engage with the rotating annulus gear. The output shaft is connected to the center of the rotating annulus. 

The term 'compound-planet' just referrs to that arrangement where the there are planetary gears coaxially arranged so that the top gear teeth engage with one annulus, and the bottom teeth with the other annulus. 

The tooth counts of the annulus gears differ by as few as one tooth and as many as perhaps the number of planet gears that orbit the sun. If the fixed annulus has more teeth than the rotating annulus, the output shaft will turn in the same direction as the input shaft. If the rotating annulus has more teeth than the fixed annulus, the output shaft turns in the opposite direction as the input shaft. The fewer teeth diffeence, the higher the gear ratio from the final stage of the gear system. 

Talking about Pitch:
There are two different diametral pitches used in this type of gear set. One diametral pitch is used for the sungear, the fixed annulus, and the first half of the planet gears. A second diametral pitch is used for the second half of the planet gears and for the output annulus. 

Talking about Joining the Planet Gears:
Each compound planet gear as an input-side gear and an output side gear. The gears would typically have the same toothcount, but would have slightly different pitches. The simplest arrangement of this while system has the top and bottom gears for each compound planet in phase with no offset. That is, one gear's teeth are just stacked directly in line with the other gear's.  This is appropriate when, for instance, the output side annulus has three more teeth than the input side annulus, and we are using three compound planet gears. Every 1/3 of the way around, the compound planet will find a place where its teeth mesh both the input and output annulus. 
Gear boxes, however, can be made that have an output annulus differing in toothcount from the input annulus by only one tooth. Since it is desirable to have more than one compound planet in the box, the top and bottom gears of the planets in such a gear box must slip phase by 1/n  for each successive compound planet, where n is the total number of compound planets you choose to use. 

For instance, let's say you have an input annulus of 60 teeth and an output annulus of 61, and that you have compund planets with 20 teeth on the top and the bottom. If you choose to have three such compound planets, the phase offsets between the top and bottom gear for each planet is as follows:

Compound Planet #1:  0 teeth rotational offset
Compound Planet #2: 1/3 tooth rotational offset
Compound Planet #3: 2/3 tooth rotational offset

It is easy to set up offsets like this with 3D printer systems, just be sure to build a marker number into the top of each compound planet, because it can be difficult to determine which planet is which during assembly. 

Use this gear box together in peace and with joy to track stars, to move solar panels, to reprocess glass and plastic into recycled bricks, and to pump water for crops. Use it to make a windmill that pumps air for a remote shop tools or for a hospital needing to concentrate oxygen. Miniaturize it for small medical robots. Use it to direct antennas in your microsatellite projects. 

-David  :-)
