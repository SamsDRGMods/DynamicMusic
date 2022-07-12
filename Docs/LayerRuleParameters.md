Global

Global parameters are applied in the order listed here. Layer rule components will calculate a value, then feed it into

Booleanify: boolean, if true, then treat a nonzero value as one
ValueMultiplier: number, multiply value by this before returning it

DYM_LRL_C_Constant

Constant: float, the value to return

DYM_LRL_C_EnemyCounter

DistanceThreshold: number, default 1000 how close an enemy has to be (In centimeters) to be added to the value
EnemyValue: number, default 0.1 how much each enemy is "worth" when added to the total value

DYM_LRL_C_TimeTracker

UseBeats: boolean, default true whether we track beats or second with this Layer rule
Constant: number, default 1 how much to return over the course of a second or beat 