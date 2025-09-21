CONNECT TO REMOTE

- add clickhouse database
- connect to postgre

Exercise

- to push data to remote
- identify dlt (should ingest in clickhouse) and dbt (pull data)

1. run auto_mpg
   - compose.yaml dlt replace to remote
   - modify dlt pipeline add ur name para maidentify whose. dlt>extract loads>staging>dlt-mpg-pipipeline
   - modify to correct naming convention then run dbt targeting remote: dependent si mart sa clean (clean rename with mpg_standardized_maryam>replace inside the name in raw>in maart rename the mpg standaaridizew with aname)

Introduction
Chinook- database that simulates digi media store (like iTunes)
PKs- unique identifiers (batlk id)
FKS- links bet tables
schema- models set of data

    entity-relationship model
    - tables= entities
    - atributes= properties of entities
    -relationship= bizz rule on how an entity relates

KEYS IN RELATIONAL DATABASES

-

Database Normalization

- use for online system
- transaction syetems to be high integrity
  oltp ; trnasaction side (high iteg)
  olap; analytics, written down.

why normalize? one truth. easy to maintain

normalization= series of system check

- transactional
- under design phase not transform
- create good foundation
  oltp
- normlaized for intergrity and writes
  OLAP
- optimize for answ qs, and speed

data modeling level

1. normalization
2. data warehouse modeling

data modeling layers
conceptual-> logical-> physical

- importance to be aligned otherwise more reworks

dimensional modeling and sql will last longer

WORKFLOW of dim modeling
idea: dividing data into two; facts and dimension
also called star schema

build the fact
facts: verbs/measure
dim: nouns/descriptions

EXERCISE: MODEL DIMENSIONALLY THE CHINOOKS

1. before anything, ingest first the data
