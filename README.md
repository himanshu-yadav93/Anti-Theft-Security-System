Anti-Theft Security Alarm
This is a simple infrared (IR) based security alarm designed to detect when a door or entryway is open. The alarm triggers a buzzer to sound when the IR light beam is broken.

Components
IR LED: Emits an infrared light beam.

IR Photodiode: Detects the IR light beam.

390 Ω Resistor: Protects the IR LED from excess current.

9V DC Battery: Provides power for the entire circuit.

Buzzer: The alarm component.

How the Circuit Works

circuit is designed to work in a way that the buzzer is on when the photodiode receives the IR light beam and off when the beam is broken.

1. When the IR Beam is Intact (Object is NOT Present)
The IR LED emits a beam of light that is detected by the IR photodiode.

When the IR photodiode is exposed to IR light, its internal resistance becomes very low.

This low resistance allows current to flow easily from the positive terminal of the buzzer, through the photodiode, and back to the negative terminal of the buzzer.

This flow of current completes the circuit for the buzzer, causing it to buzz.

2. When the IR Beam is Broken (Object IS Present)
An object placed between the IR LED and the photodiode blocks the IR light.

The IR photodiode's resistance becomes very high (acting as an open circuit).

This high resistance prevents current from flowing to the buzzer.

The buzzer circuit is effectively open, and the buzzer does not make any sound.

 circuit functions because of the parallel path created for the buzzer's current flow. When the photodiode's resistance is low, it essentially provides a "shortcut" for the current, allowing the buzzer to function. When the photodiode's resistance is high, that "shortcut" is blocked, and the buzzer remains silent.
