# ardour-midi-map

Provides XSD V1.1 schema for validating the Ardour DAW midi mapping XML files that are 
distributed with the application.  It can also be used by users to validate their 
own midi mapping files.

See: http://manual.ardour.org/using-control-surfaces/generic-midi/midi-binding-maps/
      
Amendments: Please provide documented Pull Request

## Contents

Maps:
- M-Audio Oxygen 61 Mk 4 midi map

XSD:
 - midimap.xsd - Schema Validation XSD V1.1
 
test:
 - results of using midimap.xsd on Ardour V4 and V5 supplied maps. Showing errors only
