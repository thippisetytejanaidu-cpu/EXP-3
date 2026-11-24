# EXPERIMENT NO. 3 - STAIRCASE WIRING

**Name:SAI CHARAN TEJA THIPPIETTY 
**Reg. No.:26006629 
**Date: 24\11\26
**Batch / Section:3

#AIM
To control the status of the given lamp by using two-way switches.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range / Type | Quantity |
| --- | --- | --- | --- |
| 1 | Incandescent lamp | 60 W | 1 No. |
| 2 | Lamp holder | Pendant type | 1 No. |
| 3 | SPDT switch | 230 V, 5 A | 2 Nos. |
| 4 | Wires | 1/18" | As required |
| 5 | PVC pipe | 1/4" | As required |
| 6 | Wooden board | — | 1 No. |
| 7 | Round block | — | 1 No. |
| 8 | Simulation software | Proteus Design Suite | 1 |

## THEORY
A two-way switch is installed near the first step of the stairs. The other two-way switch is installed at the upper part where the stairs end. If the light is switched on by the lower switch, it can be switched off by the switch at the top, or vice versa.

## PROCEDURE
1. Place the accessories on the wiring board as per the circuit diagram.
2. Connect phase to common point of SPDT switch 1.
3. Connect upper point of switch 1 to lower point of switch 2.
4. Connect lower point of switch 1 to upper point of switch 2.
5. Connect common point of switch 2 to one end of lamp holder.
6. Connect other end of lamp holder to neutral line.
7. Switch on the supply and test for all combinations.

## A. DIRECT CONNECTION

**Figure 1: Staircase wiring - direct connection**
<img width="1087" height="557" alt="Screenshot 2026-11-24 151713" src="https://github.com/user-attachments/assets/6e196451-ff89-40bf-845b-9808109ff673" />

### Tabulation 1: Truth Table - Direct Connection

| S. No. | Switch S1 Position | Switch S2 Position | Lamp Status |
| --- | --- | --- | --- |
| 1 | UP (1) | UP (1) | ON |
| 2 | UP (1) | DOWN (0) | OFF |
| 3 | DOWN (0) | UP (1) | OFF |
| 4 | DOWN (0) | DOWN (0) | ON |

## B. CROSS CONNECTION
<img width="1920" height="1080" alt="Screenshot 2026-10-25 101304" src="https://github.com/user-attachments/assets/dc0087c6-6f0a-4882-ab5e-57cb48ca6d91" />
[ Cross Connection Circuit Diagram - Ikkada nee book lo diagram photo pettu ]

Tabulation 2: Truth Table - Cross Connection
| S. No. | Switch S1 Position | Switch S2 Position | Lamp Status |
| --- | --- | --- | --- |
| 1 | UP (1) | UP (1) | OFF |
| 2 | UP (1) | DOWN (0) | ON |
| 3 | DOWN (0) | UP (1) | ON |
| 4 | DOWN (0) | DOWN (0) | OFF |

## SIMULATION USING PROTEUS

### A. Direct Connection - Simulation

**Lamp ON Condition:**
![Proteus Direct ON](images/proteus-on.png)

**Lamp OFF Condition:**
![Proteus Direct OFF](images/proteus-off.png)

**Figure 3: Proteus simulation - direct connection**

### B. Cross Connection - Simulation

**Figure 4: Proteus simulation - cross connection**
[ Cross connection simulation screenshot ikkada paste cheyali ]

## RESULT
Thus, the staircase wiring was connected and tested for both direct and cross connections, and the lamp was controlled from two different places using two-way switches.
