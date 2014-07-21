# jQuery SPARQL Plugin
===============
*A jQuery plugin developed to be a flexible interface with any SPARQL database.*

## Overview

**Example Query**

     $.query("SELECT distinct ?v where { ?o ?v ?s. }");

## Functions

**$.query**

Calls a SPARQL query on your database.

### Parameters

- *query* - SPARQL query string.

## Problems

**Warning**: There is no defense against injection based attacks. This is not meant for public distribution due to javascript's very public nature. This is not a problem if you create apps not meant for public consumption or if through some other means you disable modification privilages.