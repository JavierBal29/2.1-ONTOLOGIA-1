# 2.1-ONTOLOGIA-1
PRIMERA ONTOLOGIA DE 2
ONTOLOGÍA DE PELICULA
<?xml version="1.0"?>
<rdf:RDF xmlns="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#"
     xml:base="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12"
     xmlns:owl="http://www.w3.org/2002/07/owl#"
     xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
     xmlns:xml="http://www.w3.org/XML/1998/namespace"
     xmlns:xsd="http://www.w3.org/2001/XMLSchema#"
     xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#"
     xmlns:untitled-ontology-12="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#">
    <owl:Ontology rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12"/>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Object Properties
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#EsContratadoPor -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#EsContratadoPor">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Estudio_de_grabación"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Director_de_cine"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#EsDesarrolladoPor -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#EsDesarrolladoPor">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Idea/Historia"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Director_de_cine"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guionista"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#EsNecesarioParaGrabar -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#EsNecesarioParaGrabar">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Idea/Historia"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Presupuesto/Inversión"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#SonSeleccionadosPor -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#SonSeleccionadosPor">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Reparto"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Director_de_cine"/>
    </owl:ObjectProperty>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Data properties
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Descripción -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Descripción">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Camara_de_grabación"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Editor_de_video"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Estudio_de_grabación"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guión_Literario"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guión_grafico"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Iluminación"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Maquillista"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Microfonos"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Soporte_tecnico"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Vestuario"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Idea/Historia"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Edad -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Edad">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Actores"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Director_de_cine"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Editor_de_video"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Extras"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guionista"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Maquillista"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Soporte_tecnico"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Id -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Id">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Camara_de_grabación"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Editor_de_video"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Iluminación"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Maquillista"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Microfonos"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Soporte_tecnico"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#int"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Nombre -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Nombre">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Capital_Humano"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Director_de_cine"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Equipo_tecnico"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Estudio_de_grabación"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guionista"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Reparto"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Classes
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Actores -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Actores">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Reparto"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Camara_de_grabación -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Camara_de_grabación">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Equipo_tecnico"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Capital_Humano -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Capital_Humano">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Estudio_de_grabación"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Director_de_cine -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Director_de_cine">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Idea/Historia"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Diseño_de_escenario -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Diseño_de_escenario">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Estudio_de_grabación"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Editor_de_video -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Editor_de_video">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Capital_Humano"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Equipo_tecnico -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Equipo_tecnico">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Estudio_de_grabación"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Estudio_de_grabación -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Estudio_de_grabación">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Director_de_cine"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Extras -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Extras">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Reparto"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guionista -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guionista">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Presupuesto/Inversión"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guión_Literario -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guión_Literario">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guionista"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guión_grafico -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guión_grafico">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guionista"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Iluminación -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Iluminación">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Equipo_tecnico"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Maquillista -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Maquillista">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Capital_Humano"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Microfonos -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Microfonos">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Equipo_tecnico"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Pelicula -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Pelicula"/>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Reparto -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Reparto">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Director_de_cine"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Soporte_tecnico -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Soporte_tecnico">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Capital_Humano"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Vestuario -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Vestuario">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Estudio_de_grabación"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Idea/Historia -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Idea/Historia">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Presupuesto/Inversión"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Presupuesto/Inversión -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Presupuesto/Inversión">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Pelicula"/>
    </owl:Class>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Individuals
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Act1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Act1">
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Actores"/>
        <EsContratadoPor rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Dir1"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Actor principal</Descripción>
        <Edad rdf:datatype="http://www.w3.org/2001/XMLSchema#int">22</Edad>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Hector</Nombre>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Camara1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Camara1">
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Camara_de_grabación"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Dir1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Dir1">
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Director_de_cine"/>
        <Descripción rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Encarhado de grabación</Descripción>
        <Edad rdf:datatype="http://www.w3.org/2001/XMLSchema#int">21</Edad>
        <Nombre rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Josue</Nombre>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guionista1 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guionista1">
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-12#Guionista"/>
    </owl:NamedIndividual>
</rdf:RDF>



<!-- Generated by the OWL API (version 4.5.9.2019-02-01T07:24:44Z) https://github.com/owlcs/owlapi -->
