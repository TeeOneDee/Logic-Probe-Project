# Logic-Probe-Project
Free to Use - C Code - KiCad Files - Data Sheets and Notes - Drawings and Renderings

Complete Logic Probe Beginner Project with C Code, Schematic and Board Layout

I wanted to learn C code for PICs. The good people, here, and my brother were gracious enough to teach me.

I am releasing this project, in appreciation to them, and to “pay it forward.” It is my hope that it will give beginners a place to start C coding PICs, specifically, and something on which to practice soldering SMD components. It is to be used as a reference; it is not a tutorial.

For those that are just looking for a complete Logic Probe project, this is it. If you don’t want to work with SMD components, just change the component types, in the KiCad schematic, and layout a new board.
What you get:
- The C Code; it compiles well with MPLab X
- The KiCad schematic
- The KiCad board layout
- A Logic Probe that works with TTL and CMOS logic levels. The board is small enough to ride on the side of a 9 volt battery. This probe is unique, in that it is self-powered. This means that the probe does not have, or need, the voltage reference wire, that is typical of other logic probes. And, it has an LED for the indeterminate level state.
You need to know a few things:
- The project is built around a Microchip PIC12F683(I/SN footprint). It is powered with an Analog Devices voltage regulator; ADP7142AUJZ_5.0_R7. This is a cool, beefy, little regulator. Check out its amazing specs.
- I recommend that you route the common ground wire across the top of the button ground pad and solder it to the battery ground wire pin stub. Then, super-glue the wire insulation to the top of the button ground pin, for strain relief.
- The code is written, so as to teach the different aspects of coding. This means that the code may not be as concise, or elegant, as it might be, if written by a professional.
- The code is heavily commented. This method was used, so that a beginner can understand what is going on, even if they don’t understand the syntax. Again, a professional would not write the comments this way.
- I am not a teacher, I am a student. So, I am not able to answer your questions. But, I hope that experienced coders will help you.
- The project was not, and is not, intended to create a super-accurate probe. However, it works well, in testing.
- You will need to fashion your own probe pin. I used a long header pin (I cut off the plastic part) and covered it with heat shrink, except for the tip.

If you are not familiar with working with electricity, or soldering, seek help, before beginning; dangers exist.

Terms of Licensing and Release:
I hereby release the entirety of the project, for any, all and unlimited use, both private and public, including, but not limited to, commercial manufacture and sale, under the following terms and conditions:
1) You indemnify and hold harmless me, from any and all liability, including, but not limited to, actions, suits, claims, judgements, and the like, including costs of defense and/or collections, arising from, or occurring in connection with, your use of any portion of the project, or its entirety. Further, should you ever prevail against me, somehow, in any manner (such would be an utter contradiction to my complete release, which is required and intended herein,) you agree to accept liquidated damages in the amount of $10, as settlement in full, regardless of the amount of any award. You waive the right to civil hearings and agree to arbitration, should a disagreement require mediation.
2) You agree to use genuine/OEM parts for the Microchip PIC and Analog Devices voltage regulator.
3) You agree to cooperate immediately and fully, with any request I make, to verify your compliance with the licensing terms, including, but not limited to, the remittance of documents and records and the accommodation of physical inspection of facilities.
4) The definition of parties includes use of the singular tense for multiple individuals and entities and, likewise, the use of the plural, for the singular.
5) The project is intended as a learning tool. Suitability for any intended use, or purpose, is not warrantied, or guaranteed.
6) Your rights are not assignable, or transferable, whereas mine are.
7) Should any portion, of the above, fail to meet the standard of law, the remainder shall continue, in full force and effect.
Should you not agree to the aforesaid, you have no right to make use of the project, in part, or in whole. Without your agreement and full compliance to the Licensing Terms, I reserve any and all rights, including, but not limited to copyrights, slogan-marks and trademarks.

In making any comments, please give consideration to the intentions of the project and be kind.

Files Attached. Have fun!


