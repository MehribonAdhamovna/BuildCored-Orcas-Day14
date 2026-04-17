# BuildCored-Orcas-Day14
DailyDebrief — BUILDCORED ORCAS Day 14

What it does. It transforms a Python script into a living silicon brain. This simulator builds a digital sandbox where assembly-style instructions are decoded in real-time—performing math and logic jumps exactly like a physical processor—while a local LLM acts as the "voice" of the hardware to explain every flip of a bit.

Hardware concept. It is Von Neumann Architecture in its purest form, specifically mimicking the Instruction Pipeline. Just like a real CPU, it follows a strict cycle of Fetch (grab the code), Decode (interpret the command), and Execute (run the math via the ALU). It proves that "computing" isn't magic; it’s just a controlled flow of data moving between temporary storage buckets called Registers.

Screen recording. https://drive.google.com/file/d/1RolSOkNhp8BCuwoRBm0KAM7-MZhedaVg/view?usp=sharing

What I would do differently. I would implement "Visual Memory Mapping." Currently, the data lives invisibly in the background until the table updates. I would modify the code to create a live grid representing a small block of RAM. This would allow the AI to narrate not just register swaps, but how data "travels" across the system bus, making the physical distance between storage and logic visible and intuitive.

Run it. python day14_starter.py
