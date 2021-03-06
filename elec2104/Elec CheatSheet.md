
## Semiconductor
ntrinsic carrier density ni
p = hole concentration $holes/cm^3$
n = electrons concentration $electron/cm^3$
$pn= n_i^2$

-------------------------
intrinsic carrier density
### $n_i^2=BT^3e^{-\frac{E_g}{kT}}$
Eg= semiconductor bandgap energy (eV)
k = Boltzmann’s constant, $8.62×10^{−5}𝑒𝑉/𝐾$
T = absolute temperature, K
B = material-dependent parameter, $1.08×10^{31}𝐾^{−3}.𝑐𝑚^{−6}$for Si
it the unit of $E_g$ is eV
-1 eV = 1.6 ×10−19 J
----------------------

hole and electrons concentration
$n_i\approx10^{10}$ in sillicon when T = 300k
![[Pasted image 20201127010750.png]]

$𝑣_𝑛$=−$𝜇_𝑛$𝐸
$𝑣_𝑝$=$𝜇_𝑝$𝐸
![[Pasted image 20201127010920.png]]
q = $1.602*10^{-19}$
drift current density
![[Pasted image 20201127120127.png]]


resistivity and conductivity
![[Pasted image 20201127122000.png]]

Diffusion current density
![[Pasted image 20201127123712.png]]

![[Pasted image 20201127123726.png]]

Einstein relation
![[Pasted image 20201127123741.png]]
$V_T$ = 26mV
Current
I = J*A

------------------
## PN Junction
![[Pasted image 20201127132719.png]]


Vbi build in votage
![[Pasted image 20201127132808.png]]
Build in voltage without w
![[Pasted image 20201127133259.png]]
![[Pasted image 20201127132958.png]]
the w after reverse bias
![[Pasted image 20201127133858.png]]

Capacitance
![[Pasted image 20201127134222.png]]![[Pasted image 20201127134232.png]]

diode current
![[Pasted image 20201127135650.png]]
![[Pasted image 20201127134317.png]]


## Rectifier
Vdc = sqrt(2)*Vp
![[Pasted image 20201127174121.png]]

## BJT
Qpoint(Ic,Vce)
![[Pasted image 20201127175755.png]]
$I_C \approx I_Sexp(\frac{V_{BE}}{V_T})$

$\frac{I_C}{I_B} = \beta_F$

$I_E = (\beta_F + 1)I_B$

$I_E = \frac{\beta+1}{\beta}I_C$

$\frac{I_C}{I_E} = \alpha_F$

$\beta_F = \frac{\alpha_F}{1-\alpha_F}$

Early effect
when $V_A != \infty$
![[Pasted image 20201127222411.png]]

Small signal
![[Pasted image 20201128123054.png]]
voltage gain
![[Pasted image 20201128123305.png]]

impedance
Common- emmiter
![[Pasted image 20201128214641.png]]
$R_{in} = R_𝜋$
$R_{out} = R_c || R_o$
$A_V = -g_m*(R_{out})$
Common-Base
![[Pasted image 20201128214649.png]]
$A_V = g_m*(R_{out})$
$𝑅_{𝑖𝑛}=𝑟_𝜋$
$R_{out} = R_c || R_o$
Emitter-Follower
![[Pasted image 20201128214655.png]]


## MOSFET
#### Cutoff
$V_{GS} < V_{TN}$


#### Linear (Triode region)
$V_{GS} - V_{TN} >= V_{DS}$
$I_d =μ_nC_{ox}{\frac{W}{L}}(V_{GS}-V_{TN})V_{DS}$
#### saturation
$V_{GS} - V_{TN} < V_{DS}$
$I_d = {\frac{1}{2}}μ_nC_{ox}{\frac{W}{L}}(V_{GS}-V_{TN})^2$


small signal
$\lambda  != 0$
