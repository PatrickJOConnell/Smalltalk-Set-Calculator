# Smalltalk-Set-Calculator
a Set Calculator, an application for performing simple set operations, in Cincom Smalltalk. Set Calculator defines a Graphical User Interface (GUI) for user interaction. The application implements two representations for sets, an array-based and a tree-based representation. Users are given the option of choosing one or the other implementation depending on the circumstances. Set Calculator manages two set instances called X and Y. The implementation consists of an abstract class called DoubleSet and two concrete subclasses, namely BranchingSet and ArrayedSet. Subclass ArrayedSet implements a set as a Smalltalk OrderedCollection, whereas class BranchingSet implements a set as a Binary Search Tree (BST). Both sets X and Y can be either a BranchingSet or an ArrayedSet; however, it is possible for X and Y to be instances of different subclasses.