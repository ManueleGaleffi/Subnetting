# Subnetting

# Obbiettivo

IP di rete : 192.168.0.0/24

L' obbiettivo era utilizzare le regole di subnetting per creare due sottoreti della stessa dimensione una per ufficio IT e un per ufficio marketing.

# Soluzione 
Abbiamo creato due sottoreti con subnetmask 255.255.255.128 in modo che ognuna sia grande 128.
Poi abbiamo assegnato gli indirizzi IP al router uno per ogniuna delle due sottoreti,
E infine abbiamo concluso la configurazione dai PC asseganandoli come default gateway l'indirizzo IP del router al quale sono collegati.
