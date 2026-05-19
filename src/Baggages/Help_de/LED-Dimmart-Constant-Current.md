### Dimmart Constant Current

Hier wird festgelegt, wie ein Constant-Current-Ausgang dimmt.

- Hybrides Dimmen: Oberhalb von 12,5 % wird der Strom analog angepasst, darunter per PWM. Das ist in den meisten Faellen die ausgewogene Standardwahl.
- Reines PWM-Dimmen: Nutzt den gesamten Bereich per PWM. Das kann sinnvoll sein, wenn der Anwendungsfall im unteren Bereich von einer feineren Abstufung profitiert.

Praxis:
- Hybrides Dimmen ist normalerweise die beste Wahl fuer ruhiges Dimmverhalten.
- Reines PWM-Dimmen nur dann verwenden, wenn die Last oder der gewuenschte Dimmverlauf davon sichtbar profitiert.

