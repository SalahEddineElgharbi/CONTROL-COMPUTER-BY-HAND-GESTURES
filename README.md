# control-pc-par-geste

Le principe du contrôle des gestes de la main basé sur Arduino est en réalité très simple.  L'idée derrière  est d'utiliser  deux capteurs à ultrasons (HC-SR04) avec Arduino. Nous placerons les deux capteurs sur le dessus d'un écran d'ordinateur portable et calculerons la distance entre la main et le capteur. Compte  tenu des informations d’Arduino envoyé au python via le port série, ces informations de distance depuis Arduino sont collectées par un programme Python et une bibliothèque spéciale appelée PyAutoGUI convertira les données en actions par clic au clavier.

