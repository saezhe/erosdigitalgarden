---
{"dg-publish":true,"permalink":"/2-zettels/phys-1450-equations/"}
---

up:: 
pred:: 
ts:: 2022.09.29:09.37.36:112
type:: #zettel
status:: #a
tags:: [[5 spaces/5.20 clemson/+class PHYS2450\|PHYS2450]]

# [[2 zettels/PHYS 1450 equations\|PHYS 1450 equations]]
____

## temperature
$$
\begin{align}
C&=\frac{5}{9}(F-32) \\
F&=\frac{9}{5}C+32 \\
K&=C+273.16 \\
C&=K-273.16 \\
\frac{5}{9}\Delta F&=\Delta C=\Delta K
\end{align}
$$

## power
$$
\begin{align}
\text{power}&=\frac{\text{energy}}{\text{time}} \\
\text{Watt}&=\frac{\text{Joule}}{\text{Second}}
\end{align}
$$

## intensity
or in-solation, specifically for incoming rays
$$
\begin{align}
\text{intensity}&=\frac{\text{power}}{\text{area}} \\
\frac{\text{Watt}}{\text{Meter}^2}&=\frac{\text{Joule}}{\text{Meter}^2\cdot\text{Second}}
\end{align}
$$

## kinetic energy / temperature
$$
\begin{align}
E_{kin}=\frac{1}{2}\text{mass}\cdot \text{velocity}^{2}=\text{constant}\cdot \text{temperature}
\end{align}
$$

## photons

### speed of light
$$
\begin{align}
c&=300,000,000 \left[ \frac{m}{s} \right]=3*10^8 \left[ \frac{m}{s} \right] \\
&= \text{wavelength} \cdot \text{wavefrequency} &= \frac{\text{wavelength}}{\text{waveperiod}}
\end{align}
$$
### wavelength / period / number / frequency
$$
\begin{align}
\text{wavelength}&:\text{ distance}:\text{m (Meter)}, & \text{waveperiod}&: \text{time}:\text{s (Second)}, \\
\text{wavenumber}&: \frac{1}{\text{distance}}:\text{...?, }m^{-1}, & \text{wavefrequency}&: \frac{1}{\text{time}}:\text{Hz (Hertz), } s^{-1}
\end{align}
$$

### photon energy
$$
\begin{align}
\text{photon energy}&=\hbar\cdot \text{frequency}, \\
\hbar&=6.62*10^{-34}[Js] \text{ (Planck's Constant)}, \\
Js&=\text{Joule}\cdot \text{Second}
\end{align}
$$

### inverse square law
$$
\begin{align}
\text{formula using distance from source}&: I=\frac{I_{0}}{d^2} \\
\text{general formula (ratio of distances)}&:I_{2}=I_{1}\cdot\left( \frac{d_{1}}{d_{2}} \right)^2 \\
\end{align}
$$

### Wein's law:

$$
\begin{align}
\text{photon temperature } (T)&=\frac{0.0029}{\text{wavelength}} \\
&=344.827586\cdot \text{frequency} \\
\text{peak emission wavelength } (\lambda_{max})&=\frac{2898}{T}
\end{align}
$$

### Stefan-Boltzmann law:
$$
\begin{align}
\text{intensity}:I&=\sigma\cdot T^4\left[ \frac{W}{A} \right] \\
\text{stefan-boltzmann constant}:\sigma&=5.67*10^{-8} \left[ \frac{W}{m^2K^4} \right]
\end{align}
$$

## climate equations

### photons captured by earth
$$
\begin{align}
\text{power hitting earth}&:P=S(1-\alpha)\pi R^2\ [W] =1.2*10^{27}\ [W]\\ \\
\text{insolation (intensity hitting earth)}&:I=\frac{S(1-\alpha)}{4}\left[ \frac{W}{m^2} \right] =238\left[ \frac{W}{m^2} \right] \\
\text{solar constant}&:S=1,360\left[ \frac{W}{m^2} \right] \\
\text{albedo of earth}&:\alpha\approx 0.3 \\
\text{radius of earth}&:R_{\text{Earth}}=6,400,000 [m]
\end{align}
$$

### temperature of earth with no atmoshpere:
$$
\begin{align}
T&=\left( \frac{S(1-\alpha)}{4\sigma} \right)^{ \frac{1}{4} } [K]=255[K]
\end{align}
$$

### temperature of earth with atmoshpere:
$$
\begin{align}
\text{temperature}&:T=\left( \frac{(N+1)S(1-\alpha)}{4\sigma} \right)^{ \frac{1}{4} } [K] \\
\text{atmospheric layers}&:N_{\text{Earth}}\approx 0.65
\end{align}
$$

## people equations

### IPAT / KAYA identity
$$
\begin{align}
I&=P\cdot A\cdot T,\\ \text{where } T&= E\cdot I_{C} \\ \\
\text{emissions}&= \\
&\text{population}[\text{person}] \\
&\cdot \text{economic activity/affluence}\left[ \frac{$}{\text{person}} \right] \\
&\cdot \left( \text{technology}:\text{efficiency}\left[ \frac{\text{Watt}}{$} \right] \cdot \text{carbon intensity}\left[ \frac{\text{Carbon}}{\text{Year}\cdot \text{Watt}} \right]\right)\left[ \frac{\text{Carbon}}{\text{Year}\cdot$} \right]
\end{align}
$$

____
template:: [[9 extras/9.100 hidden!/hidden! 8 templates/hidden! 8.01 templater/hidden! 8.01.01 zettels/hidden! 8.01.01 zettel\|hidden! 8.01.01 zettel]]
