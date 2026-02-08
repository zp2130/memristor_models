# memristor_models
https://asic2.group/tools/memristor-models/

General Memristor Models
Here you can find models for memristors implemented in Verilog-A (compatible with SPICE) and MATLAB (including GUI).

The models are based on the papers:

S. Kvatinsky, E. G. Friedman, A. Kolodny, and U. C. Weiser, “TEAM: ThrEshold Adaptive Memristor Model,” IEEE Transactions on Circuits and Systems I: Regular Papers (also CCIT Technical Report #804), Vol. 60, No. 1, pp. 211-221, January 2013.

S. Kvatinsky, M. Ramadan, E. G. Friedman, A. Kolodny, and U. C. Weiser, “VTEAM – A General Model for Voltage Controlled Memristors,” Transactions on Circuits and Systems II: Express Briefs, Vol. 62, No. 8, pp. 786-790, August 2015. (also CCIT Technical Report #856)

They include the following models:

Linear ion drift model.

Nonlinear drift model.

Simmons tunneling barrier model.

TEAM – ThrEshold Adaptive Memristor Model.

VTEAM – Voltage ThrEshold Adaptive Memristor Model.

They wrote a short [manual](Manual.pdf) and [movie](https://www.youtube.com/watch?v=wFqL5yYUEw8) for these models. The Verilog-A model is also described in the following paper: S. Kvatinsky, K. Talisveyberg. D. Fliter, E. G. Friedman, A. Kolodny, and U. C. Weiser, “Models of Memristors for SPICE Simulations,” Proceedings of the IEEE Convention of Electrical and Electronics Engineers in Israel, pp. 1-5, November 2012.

For any Information contact them and note that for Virtuoso 6.1.5 there is a bug in some versions – use version 6.1.5-64b (IC06.15.500).

Downloads

[Verilog-A Model](memristor_original.model)

MATLAB Model – Including GUI: [memristor.m](memristor_original.m), [memristorGUI.m](MemristorGui_original.m), [memristorGUI.fig](MemristorGui_original.fig).

...
