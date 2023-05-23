Die Lifted-System-Darstellung ist eine Methode zur Zustandsraumdarstellung von linearen zeitinvarianten (LTI) Systemen. Sie wird oft verwendet, um diskrete Systeme zu modellieren, insbesondere solche, die aus einer kontinuierlichen Systembeschreibung diskretisiert wurden. #definition
----
-  In der Lifted-System-Darstellung wird das diskrete System als eine Kaskade von zwei LTI-Systemen dargestellt: 
    - einem diskreten Zustandsraummodell 
        -  beschreibt die Dynamik des Systems zwischen den diskreten Zeitpunkten
    - Lift-Operator
        - ist ein kontinuierliches System, das die Interpolation der Zustände zwischen den diskreten Zeitpunkten durchführt.

---- 
In der Regel wird die Lifted-System-Darstellung verwendet, wenn es erforderlich ist, kontinuierliche Systeme diskret zu modellieren, z. B. bei der Entwurfs- und Analyse von digitalen Regelungssystemen.