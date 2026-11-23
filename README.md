## EXPERIMENT NO. 3 – STAIRCASE WIRING

| **Name:** | | **Reg. No.:** | |
|---|---|---|---|
| **Date:** | | **Batch / Section:** | |

---

## AIM

To control the status of the given lamp by using two-way switches.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range / Type | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Incandescent lamp | 60 W | 1 No. |
| 2 | Lamp holder | Pendant type | 1 No. |
| 3 | SPDT switch | 230 V, 5 A | 2 Nos. |
| 4 | Wires | 1/18" | As required |
| 5 | PVC pipe | 1/4" | As required |
| 6 | Wooden board | — | 1 No. |
| 7 | Round block | — | 1 No. |
| 8 | Simulation software | Proteus Design Suite | 1 |

## THEORY

- A two-way switch is installed near the first step of the stairs. The other two-way switch is installed at the upper part where the stairs end.
- The light point is provided between the first and last stair at an adequate location and height. If the light is switched on by the lower switch, it can be switched off by the switch at the top, or vice versa.
- The circuit can also be used in places like a bedroom, where the person need not walk back to the place from where the light was switched on in order to switch it off.
- Two numbers of two-way switches are used for this purpose. The supply is given to the switch at the short-circuited (common) terminal.
- The connection to the light point is taken from the similar short-circuited (common) terminal of the second switch. The other two independent terminals of each switch are connected through cables.

## PROCEDURE

1. Place the accessories on the wiring board as per the circuit diagram.
2. Place the PVC pipe and insert two wires into the PVC pipe.
3. Take one wire; connect one end to the phase side and the other end to the middle (common) point of SPDT switch 1.
4. The upper point of SPDT switch 1 is connected to the lower point of SPDT switch 2.
5. The lower point of SPDT switch 1 is connected to the upper point of SPDT switch 2.
6. Another wire is taken through the PVC pipe, and the middle (common) point of SPDT switch 2 is connected to one end of the lamp holder.
7. The other end of the lamp holder is connected to the neutral line.
8. Screw the accessories on the board and switch on the supply.
9. Test the circuit for all possible combinations of switch positions.

## A. DIRECT CONNECTION

### Circuit diagram

<img width="1007" height="835" alt="image" src="https://github.com/user-attachments/assets/e75911d9-ed02-4548-946b-587983fec15f" />


**Figure 1:** Staircase wiring – direct connection

### Tabulation 1: Truth table – direct connection

<img width="1062" height="532" alt="Screenshot 2026-11-23 103302" src="https://github.com/user-attachments/assets/f70362ad-9342-4826-a064-b0cf1bf8299f" />


## B. CROSS CONNECTION

### Circuit diagram

<img width="1001" height="777" alt="Screenshot 2026-11-23 103324" src="https://github.com/user-attachments/assets/3f305b86-eb87-445f-adc3-49e39067522a" />


**Figure 2:** Staircase wiring – cross connection

### Tabulation 2: Truth table – cross connection

<img width="1057" height="522" alt="Screenshot 2026-11-23 103342" src="https://github.com/user-attachments/assets/03876ba1-6e75-4eaa-8912-32906d4cc31b" />

## SIMULATION USING PROTEUS

Build both the direct and cross connection circuits in Proteus using an AC source, two SPDT switches and a lamp. Run the simulation for each switch combination and paste screenshots showing the lamp ON and OFF states.

### A. Direct connection – simulation

<img width="995" height="772" alt="Screenshot 2026-11-23 103405" src="https://github.com/user-attachments/assets/d32dfc07-098b-4d89-ab50-01321d66ca98" />


**Figure 3:** Proteus simulation – direct connection

### B. Cross connection – simulation

<img width="1062" height="77" alt="Screenshot 2026-11-23 103432" src="https://github.com/user-attachments/assets/1abfa6ab-31e7-4599-88e2-76b08c9ea761" />


**Figure 4:** Proteus simulation – cross connection

## RESULT

Thus, the staircase wiring was connected and tested for both direct and cross connections, and the lamp was controlled from two different places using two-way switches.
