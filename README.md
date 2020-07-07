# ABAP-ON-HANA
There are three different types of CDS views 
1) Basic
2) Composite
3) Consumption
1) The virtual data model is the fundamental data model for applications. 
For both transactional and analytical applications, plus APIs.
2) Basic View With Association, is to provide an adequate representation of a relationship between
 two entities in the data model in the ABAP Data Dictionary, The idea is to express these relationships as part
 of the data model capture them in the metadata stored behind the scenes and make them available for reuse.
3) Reusing associations includes an integration into the SQL-like query language as well as the availability 
of the association metadata to frameworks built on top of the ABAP Data Dictionary.  
4) Alternatively, the term $projection. can be used to directly refer to elements within the select list. 
In this case, the alias names can be referenced.
5) ABAP CDS provides a framework for defining and consuming semantic data models on the central database of 
the application server AS ABAP.
6) ABAP CDS provides a framework for defining and consuming semantic data models on the central database of the 
application server AS ABAP. The specified data models are based on the data definition language (DDL) and the 
data control language (DCL). So, a CDS entity or the enhancement of a CDS view is defined as source code in the 
CDS data definition.  
7) CDS is much more powerful than what it appears,simple view building but describes a DDL for building a 
meta-model repository involving database tables, database views, functions, and data types.
8) ABAP CDS is open and not restricted to SAP HANA (i.e. database independent).
9) Also, CDS Views can be categorized as of two types: 1.CDS Views without Parameters 2.CDS Views with Parameters
10) With CDS, data models are defined and consumed on the database rather than on the server. CDS also offers 
capabilities beyond the traditional data modeling tools, including support for conceptual modeling and relationship 
definitions, built-in functions, and extensions.
11) Now, the CDS concept is also fully implemented in SAP NetWeaver AS ABAP, enabling developers to work in the
 ABAP layer with ABAP development tools while the code execution is pushed down to the database.
12) CDS allows developers to define entity types (such as orders, business partners, or products)
 and the semantic relationships between them.
13) CDS is defined using an SQL-based data definition language (DDL) that is based on standard SQL 
with some additional concepts, such as associations, which define the relationships between CDS views and 
annotations, which direct the domain-specific use of CDS artifacts.
14) Another difference is the support for special operators such as UNION, which enables the combination 
of multiple select statements to return only one result set.
15) The subtle differences between CDS in native SAP HANA and CDS in ABAP lies in the view definition.
16)  In both the ABAP and HANA scenarios, views are created on top of existing database tables that are 
contained in the DDIC.
17) In the ABAP scenario, the CDS definitions are considered DDIC artifacts and need to be activated like
 any other DDIC artifact and when changes are made, their impact is propagated to dependent artifacts.
18) The standard ABAP CDS views, ERP tables and views can be reused in custom CDS views in ADT source editor.
19) CDS also define into Extended CDS view or Custom CDS view and CDS table function 
20) ABAP CDS entities are data models based on the data definition language (DDL) specification and are
 managed by ABAP Dictionary.
21) So, a CDS entity or the enhancement of a CDS view is defined as source code in the CDS data definition.
22)  
