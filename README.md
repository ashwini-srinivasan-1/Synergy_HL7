Here are the SW requirement for HL7 and BDD Test step is created for the same:
- [SW1]: WHILE the system is connected to Device Observation Consumer 
  WHEN the reporting interval is reached 
  THEN the system shall send an ORU^R01 message to the Device Observation Consumer
- [SW2]: The system shall send out ORU^R01 messages with the following patient demographics in the PID segment: Patient Identifier List, Patient Name, Date/Time of Birth, Administrative Sex, Patient Alias.
