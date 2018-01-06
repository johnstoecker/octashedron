# octa(s/he)dron

<i>Light up your partner's face!</i>

Arduino-based physical octahedrons, with each face representing an activity. You and your partner each control your own polyhedron, and when you press a button corresponding to your current activity, the light on your partner's polyhedron face lights up.

The core of each octashedron uses a photon spark to communicate over wifi. To get it setup, plug in to a USB port and enter in your wifi details.

Each face of the octahedron contains 2 LED's -- red and blue, for you and your partner. As the spark receives information, it tells a specific LED to illuminate a face of the octashedron. Additionally, each face contains a button for you to control your activity as well (and light up your partner's face).

<h3>The Octashedron Kit</h3>
- photo spark
- USB cable for power/setting up wi-fi
- 16 LEDs + wires
- cage to hold faces, separate light from LEDs
- 8 laser-cut activity faces

<h3>DB Entities</h3>

Users - sign up in pairs
- name
- user_id of partner
- email
- current_activity (may be nil)

Activity
- user_id_1
- user_id_2
- svg (?) of activity
