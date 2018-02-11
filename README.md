# teensy36eurorackhelper
little board to help the teensy 3.6 boot in eurorack modules

---

Mount this little fellow underneath your Teensy 3.6 if you are having trouble booting when mounted in place of a Teensy 3.2 in a Eurorack module. The symptom is that the module never executes your code when booted without USB power.

![Teensy 3.6 on TXo](https://raw.githubusercontent.com/bpcmusic/teensy36eurorackhelper/master/telex_teensy.png)

This board adds a voltage supervisor that delays the start of the Teensy (via the Reset pin) until there is adequate power. It was designed to fit on the bottom of the board in an area that would not be populated for a Teensy 3.2.

![Top](https://raw.githubusercontent.com/bpcmusic/teensy36eurorackhelper/master/top.png) ![Botton](https://raw.githubusercontent.com/bpcmusic/teensy36eurorackhelper/master/bottom.png)

<a href="https://oshpark.com/shared_projects/2kwylotu"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>

More details are in this thread: 

https://forum.pjrc.com/threads/44704-Boot-on-Power-Up-Problem-with-three-T3-6s

Thanks to everyone there (especially neutron7) for finding the solution. All I did was panel the thing up. Saved my bacon on a project, though. :)