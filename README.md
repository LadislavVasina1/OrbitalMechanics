# OrbitalMechanics - 2 Sun orbiting bodies calculator
[![EXAMPLE 1](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1KQyFUAqPE5UJtbTiM_o2FjUsTC-nyhoc?usp=sharing)

The objective is to prepare an orbital calculator capable to calculate relative distance and velocity between two heliocentric bodies at a given time. Use of MS Excel or Matlab is preferred, but not strictly required.

User will select two heliocentric bodies and will enter their orbital elements into the calculator. Then (s)he will specify the requested time moment. The calculator shall return the distance between the bodies and their relative velocity.

If one of the bodies is Earth, use the following orbital elements:

Semi-major axis: a=1 AU

Eccentricity: e=0.0167

Inclination: i=0°

Longitude of the ascending node: Omega=-11.26064°

Argument of perihelion: omega=114.20783°

Time of perihelion passage: T0=2451547.5191

LV2021 (https://ssd.jpl.nasa.gov/tools/sbdb_lookup.html#/?sstr=2021%20LV) (https://www.spacereference.org/asteroid/2021-lv) asteroid is chosen as default 2nd body.



Time can be set as Julian date in all cases. For better understanding of Julian date and other issues related to orbital problems in 3D, please check the “Examples” section (or consult with your teacher).

The program can be limited to elliptical orbits only (then the maximum number of point for this homework is 5). However, if it will be able to compute also parabolic or hyperbolic orbits, it will be appreciated by one extra point for each additional orbit type (thus, at maximum, you can get 7 points).

You can use https://cneos.jpl.nasa.gov/ca/ webpage to validate your calculator. Select any bodies to see their orbital elements.

### To validate hyperbolic orbits, temporary data are:

Asteroid: A/2017 U1 (Oumuamua)
Semi-major axis: a=1.272345 AU

Eccentricity: e=1.20113

Inclination: i=122.7417°

Longitude of the ascending node: Omega=24.59691°

Argument of perihelion: omega=241.81054°

Time of perihelion passage: T0=2458006.007321

Distance from Earth:

30.10.2021 0:00:00: d=25.573967 AU

30.10.2022 0:00:00: d=31.3749 AU

30.10.2023 0:00:00: d=37.1359 AU

30.10.2024 0:00:00: d=42.8679 AU
