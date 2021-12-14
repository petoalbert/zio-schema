# ZIO-Schema Examples


Example usages of ZIO-Schema, mainly used as a cheatsheet and making sure the examples work
when putting them into the documentation.

## Example 1
Basic domain model and showing how to create a schema by hand and by macro derivation.
Showing how to transform a JSON-String to a domain object using a codec.


## Example 2
Schema definitions in companion objects. 

## Example 3
In this example we'll take a look on how to use ZIO-Schema to
transform the JSON of a PersonDTO (e.g. from a REST API) into a Person (e.g. for a database) in a single step.

To do this, we'll transform the Schema of the PersonDTO into a Schema of the Person.


## Example 4 (not working at the moment)
In this example we'll take a look on how to use ZIO-Schema to migrate between different objects, 
e.g. a `WebPerson` to a `DomainPerson`

## Example 5
In this example we'll see how we can use ZIO-Schema to create Diffs between two objects. This is helpful 
e.g. to only persist changes to objects, e.g. when using EventSourcing.

## Example 6 (not yet available in 0.1.1)
In this example we'll see how we can use optics generated by ZIO-Schema to manipulate nested data structures.
 - use lenses to change simple values (lenstest1)
 - use lenses to change values in nested classes (lenstest2)
 - use traversable to add elements to a list in a nested class (traversabletest1)

## Example 7
Example based on John DeGoes Spartan Training on ZIO-Schema from 2021-11-04. 
We're building a QueryString-Codec.