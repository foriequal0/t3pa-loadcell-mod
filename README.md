# Thrustmaster T3PA pedal load cell mod without a dead zone

Several prior works[^prior-works-1][^prior-works-2] replaced the existing potentiometer with a load cell. So there should be a physical dead zone until the pedal conacts the load cell, or the pedal's travel distance should be sacrificed by removing the gap.

I've solved the dead zone problem by integrating the existing potentiometer and a load cell.

[^prior-works-1]: [Thrustmaster T3PA Load Cell Mod - Falcon's Tech](https://www.youtube.com/watch?v=KIldeuIU-jM)
[^prior-works-2]: [Thrustmaster t3pa pedal Load Cell Mod | Simonas G](https://slowlogicboy.github.io/electronics/sim%20racing/TM-T3PA-LoadCellMod/)

There are three versions of the load cell mod in this repository.
If you want to make one, you should check out `v2` first.

* [v0](./t3pa-loadcell-mod-v0/README.md) : First prototype that is built by hand-soldering on a prototype board.
* [v1](./t3pa-loadcell-mod-v1/README.md) : It requires PCB manufacturing, but still hand-solderable.
* [v2](./t3pa-loadcell-mod-v2/README.md) : Successor of v1, the final version. 