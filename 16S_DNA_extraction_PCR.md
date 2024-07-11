## DNA extraction and PCRs (16S) of bacteria associated to planulae and spat of _S. pistillata_

Using the [Zymo Quick-DNA/RNA Miniprep Plus Kit ](https://zymoresearch.eu/collections/quick-dna-rna-kits/products/quick-dna-rna-miniprep-plus-kit) on _Stylophora pistillata_ planulae and spat to extract associated bacterial DNA and further microbiome analysis. This post is based on  [fscucchia's](https://github.com/fscucchia) [protocol](https://github.com/fscucchia/FScucchia_Lab_Notebook-Mass_Lab/blob/master/_posts/2020-12-09-DNA-RNA-extraction-with-Zymo-kit.md).

### Reagents preparation
1. Add 96 mL 100% ethanol (104 mL 95% ethanol) to the 24 mL DNA/RNA Wash Buffer concentrate before use. DNA/RNA Wash Buffer included with D7003T (Mini Prep Plus Kit) is supplied ready-to-use and does not require the addition of ethanol prior to use. Check kit contents and instructions to confirm prep steps.
2. Reconstitute the lyophilized (freeze-dried) DNase I as indicated on the vial prior to use. Mix by inversion. Store frozen aliquots.
_Note: These steps were not required when I did my extraction, as everything was already reay in the kit I used. I also omitted the Tris steps for this protocol_.

### Sample preparation (planulae and spat)
For this protocol, cryo vials grouping 15 planulae or 11 spats were used. After collection, they had been frozen with liquid nitrogen and stored at -80°C. It is also possible to use n=10 for planulae and n=5 for spat.
1. Add 500μl of  DNA/RNA shield to a new 2 ml tube. 
2. Allow samples to de-freeze and transfer to the 2 ml tube. 
3. Put samples into a disruptor genie for 15 mins(notes say less than 1 minute, check with Nataly) at 2000 rpm. 
4. Proceed to DNA extraction steps. 

### DNA extraction
1. Set up and label yellow DNA spin colums and collection tubes. 
2.   Warm elution liquids to 70°C (RNAse free water) (actually not sure we warmed it... Ask Nataly). 
3.   Add a volume equal to the sample to (600μl here) of lysis buffer to each sample tube. (Did we change the samples of tube??).
4.   Finger flick to mix tubes. (We also added 30μl of proteinase K)...
5.   Add 700μl (total volume) of sample gently to the yellow DNA spin column. 
6.   Centrifuge at 16000 rcf (g) for 30 seconds. 
7.   **Important** Save the flow through from this step: transfer to a new 1.5 ml tube labelled for RNA. 
8.   Add 400μl DNA/RNA Prep Buffer gently to the yellow DNA spin column. 
9.   Centrifuge at 16000 rcf (g) for 30 seconds. 
10.   Discard flow through (Zymo kit waste).
11.   Add 700μl DNA/RNA wash buffer gently to the yellow DNA spin columns. 
12.   Centrifuge at 16,000 rcf (g) for 30 seconds
13. Discard flow through (Zymo kit waste)
14. Add 400 µl DNA/RNA Wash Buffer genetly to the yellow DNA spin columns
15. Centrifuge at 16,000 rcf (g) for 2 minutes
16. Discard flow through (Zymo kit waste)
17. Transfer yellow columns to new 1.5mL microcentrifuge tubes
18. Add 50 µl warmed H20 to each yellow DNA column by dripping slowly directly on the filter
19. Incubate at room temp for 5 minutes.
20. Centrifuge at 16,000 rcf (g) for 30 seconds.
21. Repeat steps 18-20 for a final elution volume of 100µl.
22. Label tubes, store at 4°C if quantifying the same day or the next (Nanodrop), if waiting longer store in -20°C.

### PCR

# Dilution of gDNA samples for PCR
1. Take out samples from -20°C
2. Put it on ice until it defreezes
3. Mark tubes "1:10 gDNA samples" (this was determined due to the concentration of the DNA in my samples)
4. Add 90µl H20-RNA free to new tubes. 
5. Add 10µl of gDNA from the sample to new tubes. 
6. Mix gently (didn't vortex).

# Make PCR Master list GoTaq® Green Master Mix

The utilized primers were: 
Forward: 926F for 16S
ACACTGACGACATGGTTCTCAAGTGYC
TM: 70.8°C.
MW: 12599.7
Reverse: 926F 
TACGGTAGCAGAGACTTGGTCTCCGY
TM: 65.3°C.
MW: 12.905.4

Prior to use, primers were diluted from their original concentration at 100µM / 240 µl to 10µM (10 µl of primer + 90µl of RNA-DNA free water).

Reverse: 926F for 16S

For a 50µl reaction volume:

| Component                   | 1X Rec. Volume | 7.5X Rec. Volume | Final Conc.   |
|-----------------------------|----------------|------------------|---------------|
| GoTaq® Green Master Mix, 2X | 25µl           | 187.5 µl         | 1X            |
| upstream primer, 10µM       | 5µl            | 37.5 µl          | 1.0µM         |
| downstream primer, 10µM     | 5µl            | 37.5 µl          | 1.0µM         |
| DNA template or H2O         | 10µl           |                  |               |
| BSA                         | 5µl            | 37.5 µl          |               |
| Total                       | 50µl           | 300 µl           | 40 µl +10 µl  |

1. Gather reagents and spin down gently before use. Make the 
2. Mark 7 (6 samples + NTC) 0.1 PCR tubes. 
3. Mix reagents for the master mix. Spin down. 
4. Add 40µl of master mix to every tube. 
5. Add 0.10µl of diluted gDNA from a particular sample to the corresponding marked tube. Repeat for all samples. 
6. Spin down PCR tubes.

# Run PCR

PCR program (now under Rhenium PCR machine at Mass Lab in folder Amalia/16S). Assemble PCR tubes. Distribution is not relevant. 

| ITC CS           | Temp | Time  | Cycles |
|------------------|------|-------|--------|
| Initial          | 95   | 3 min | 1      |
| Denaturation     | 95   | 30 s  | 28 t   |
| Annealing        | 55   | 45 s  | 28 t   |
| Elongation       | 72   | 45s   | 28 t   |
| Final extension  | 72   | 1 min | 1      |

# Gel running 
1% agarose gel (1 g agarose in 100 ml of 0.5XTBE) and 4µl Red Safe run for 1.5 hours in 110 V (10V/ cm gel). Samples compared to DNL04 Take5 HR DNA ladder (250 bp-25kb range) and EuRx Perfect 100 bp DNA ladder (100 bp-2500 bp).