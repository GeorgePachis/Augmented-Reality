# Lesson: Interaction Design

### First and Last Name: Γιώργος Παχής
### University Registration Number: dpsd17084
### GitHub Personal Profile: https://github.com/GeorgePachis
### Augmented Reality Personal Repository: https://georgepachis.github.io/Augmented-Reality/

# Introduction
 
# Summary


# 1st Deliverable
Αρχικά έκανα fork το repository του Augmented Reality στο δικό μου github repository και άλλαξα το link του repository από τα settings.Στη συνέχεια έκανα εγκατάσταση στον υπολογιστή μου το Github Desktop για να ανεβαίνουν οι αλλαγές του κώδικα που κάνω τοπικά στον υπολογιστή μου στο προσωπικό μου repository στο GitHub και το Visual Studio Code για να μπορώ να κάνω αλλαγές στον html κώδικα. Έκανα set up έναν τοπικό server ώστε να μπορώ να ελέγχω τοπικά στον υπολογιστή μου τις αλλαγές που κάνω στον κώδικα πριν το ανεβάσω μέσω του github desktop στο repository μου. Τελικά μέσω έρευνας και αναζήτησης σε διάφορες πηγές προστέθηκε κώδικας και έγιναν κάποιες αλλαγες στο html αρχείο ώστενα γίνουν τα παρακάτω:

-Να εμφανιστούν στην οθόνη ένας κύλινδρος και μια σφαίρα.

-Να χιονίζει στην σκηνή μου.

-Να σταματάει και να ξεκινάει να χιονίζει στη σκηνή με φωνητικές εντολές "stop" και "start" αντίστοιχα. 

Στα sources φαίνονται οι πηγές αναζήτησης.

# 2nd Deliverable
Για το δεύτερο παραδοτέο ρίχνοντας αρχικά μια ματιά [εδώ](https://ar-js-org.github.io/AR.js-Docs/marker-based/) και [εδώ](https://medium.com/chialab-open-source/ar-js-the-simpliest-way-to-get-cross-browser-ar-on-the-web-8f670dd45462) [κώδικας](https://aframe.io/docs/1.3.0/primitives/a-image.html) για εισαγωγή εικόνας  [κώδικας](https://aframe.io/docs/1.3.0/components/text.html) για κείμενο, χρησιμοποιώντας αυτό το [εργαλείο](https://ar-js-org.github.io/AR.js/three.js/examples/marker-training/examples/generator.html), δημιούργησα τον δικό μου marker με το registration number μου  το οποίο οταν σκαναριστεί από την κάμερα εμφανίζει μια εικόνα του εαυτού μου και το ονοματεπώνυμό μου από κάτω με αγγλικούς χαρακτήρες με μωβ γραμματοσειρά.

![This is an image](https://github.com/GeorgePachis/Augmented-Reality/blob/main/marker_based/assets/DPSD17084_marker.png)

Στη συνέχεια, παίρνοντας τις εικόνες του υδρογόνου και του οξυγόνου δημιούργησα χρησιμοποιώντας ξανά το ιδιο [εργαλείο](https://ar-js-org.github.io/AR.js/three.js/examples/marker-training/examples/generator.html) δυο markers με τα pattern τους αντίστοιχα. Στηρίχτηκα σε [αυτό](https://aframe.io/docs/1.3.0/components/gltf-model.html) και [αυτό](https://aframe.io/docs/1.3.0/core/asset-management-system.html) για να γράψω τον κώδικα ο οποίος ήταν παρόμοιας μορφής με τον παραπανω μόνο που έπρεπε να προστεθεί ένα αρχείο gltf αντί για μια εικόνα ή ενα text. 
Χρησιμοποιώντας το blender και βλέποντας πρώτα κάποια tutorials οπως [αυτό](https://www.youtube.com/watch?v=pNA8ujgtogM) και [αυτό](https://www.youtube.com/watch?v=E42OxbroToM) και [αυτό](https://www.youtube.com/watch?v=YD6_6WG0dIA), δημιούργησα δυο 3d models τα οποία αποθηκεύτηκαν ως gltf αρχεία. Έπειτα με κώδικα που στηρίχτηκε από [εδώ](https://aframe.io/docs/1.3.0/components/animation.html) δημιουργησα το animation και όταν φέρεις τα αντιστοιχα markers μπροστά απ την κάμερα δημιουργείται η ψευδαίσθηση ότι οι μικρές σφαίρες εκτελούν κυκλική κίνηση γύρω από το κύριο σώμα.

### Εικόνα οξυγόνου 
![This is an image](https://github.com/GeorgePachis/Augmented-Reality/blob/main/marker_based/assets/oxygen_creation.jpg)

### Εικόνα υδρογόνου 
![This is an image](https://github.com/GeorgePachis/Augmented-Reality/blob/main/marker_based/assets/hydrogen_creation.jpg)

# 3rd Deliverable 
Για το τρίτο παραδοτέο έκανα μια αναζήτηση και βρήκα ένα 3d μοντέλο μιας γοργόνας [εδω]() και το πρόσθεσα στον κώδικα. Στις συντεταγμενες του gps-camera πρόσθεσα τις συντεταγμένες του μνημείου της γοργόνας που βρίσκεται στην περιοχή του Κινιού, ενός χωριού λίγο πιο έξω από την ερμουπολη της Σύρου. Στη συνέχεια πρόσθεσα ένα text με μια μικρή περιγραφή του μνημείου το οποίο εμφανίζεται όταν πατήσεις κλικ πάνω στο 3δ μοντέλο της γοργόνας. Ο κώδικας προέκυψε από την  μελέτη [αυτής] της ιστοσελίδας.
Για το τρίτο κομμάτι του παραδοτέου αναζήτησα ένα ακόμη 3δ μοντέλο που αναπαριστά την μορφή ενός ψαριού και παραπέμπει σε ένα ενυδρείο που βρίσκεται και αυτό στο χωριο Κίνι. Στο gps-camera αλλά καισ το ίδιο το enity προσαρμόστηκαν οι συντεταγμένες τους. Όλες οι συντεταγμένες ορίστηκαν μέσα από το [Google Maps]. Τέλος προσθεσα με παρόμοιο τρόπο ένα κειμενο που δίνει πληροφορίες για το ενυδρείο και εμφανίζεται κάνοντας κλικ πάνω στο κινούμενο ψάρι. 

# Conclusions


# Sources

https://github.com/aframevr/aframe

https://www.npmjs.com/package/aframe-speech-command-component

https://github.com/IdeaSpaceVR/aframe-particle-system-component#readme
