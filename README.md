# Modelica_QuasiStationary

Free library for the analysis of electrical circuits with purely sinusoidal voltages and currents. With this library single and multi phase circuits can be modelled. (Still uses Modelica Standard Library 2.2.2!) This library is included in the MSL starting from version 3.2.

## Library description

The Modelica_QuasiStationary library addresses the analysis of electrical circuits with purely sinusoidal voltages and currents.

The main characteristics of the library are:
  * Only pure sinusoidal voltages and currents are taken into account. Higher harmonic voltages and currents are not considered.
  * Any electrical transient effects are negelcted.
  * The electrical components of this library are strictly linear.
  * The angular frequency omega of the voltages and currents of a circuit are determined from a reference angle gamma by means of `omega = der(gamma)`.
  * The reference angle gamma is not a global quantity since it propagated through the connector. Therefore, independent circuits of different frequencies can be modeled in one model.
  * The connectors contain the real and the imaginary part of the voltage and the current RMS phasors

## Last release

Download [Modelica_QuasiStationary v0.9.3 (2009-12-08)](../../archive/v0.9.3.zip)

## License

This Modelica package is free software and the use is completely at your own risk;
it can be redistributed and/or modified under the terms of the [Modelica License 2](https://modelica.org/licenses/ModelicaLicense2).

## Development and contribution

This library is deprecated and therefore no longer actively developed.
An improved version was incorporated into the Modelica Standard Library and is maintained there.
