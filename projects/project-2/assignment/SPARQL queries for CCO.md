# Title: 
#    No Extra Annotation Whitespace
# Constraint Description: 
#    No annotation value may have leading or trailing whitespace.    
# Severity:
#    Error 
# Difficulty: 


# example of BIND
# BIND (concat("ERROR: The following annotation value has leading or trailing whitespace ", str(?element)) AS ?error)
}



# LIST OF QUERIES IN NATURAL LANGUAGE and DIFFICULTY:

identify classes that have object properties but do not have any cardinality restrictions (e.g., owl:minCardinality, owl:maxCardinality (3)

find all ICE classes that do not have a textual definition (e.g., missing rdfs:comment or skos:definition). (3)

check if all datatype properties have consistent rdfs:range definitions. (4)

detect cases where owl:hasValue is used incorrectly, such as applying it to situations where other constraints like owl:someValuesFrom would be more appropriate. (4)

find object properties that have overlapping domains defined across different classes. (3)

identify all Event classes that do not have any defined temporal relationships (before, after, during)  (3)

identify all object properties in the Extended Relation Ontology that do not have a defined domain (rdfs:domain) or range (rdfs:range) (6)

detect any deprecated annotation properties that are still being used across classes, individuals, or properties. (6)

list all subclasses that add no new axioms compared to their superclass  (7)

list all classes that do not have any subclasses  (8)




