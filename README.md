# ComputerArchitecture-BinaryLock
Built on LogicWorks 5. The purpose of this project is to create a circuit that would serve as a lock for a certain code. The password to the binary lock is 11101111.

BinaryLockCircuit.cct - this file simulates a binary-styled lock to open based off of our given codes. For this circuit, we used the code 11101111
to build our circuit around. In order to achieve this, we drew out the state diagrams and state tables to derive our k-map and our equations.

FullBinaryLockCircuitDiagram.cct - this file utilizes the device symbol to recreate the lock. It will theoretically output a 1 if we input 11101111 in
sequence.

SaveStateLockCircuit.cct - this file simulates a save-state styled lock to open based off of a user's input. We can save a password by using a hex
keyboard then toggling the save switch on.

FullSaveStateLockCircuitDiagram.cct - this file utilizes the device symbol to recreate the lock. We can enter a password using the hex keyboard and
save that password using the switch.
