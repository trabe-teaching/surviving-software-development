!SLIDE cover

# Software Development at Trabe

!SLIDE image

![Who we are](who_we_are.png)

!SLIDE image

![Trabe](trabe.png)

<!--
  a qué nos dedicamos, qué hacemos para quién, tecnologías, etc
-->

!SLIDE image

![Men at work](men_at_work.png)

!SLIDE

# Shiny happy opinionated people

!SLIDE bullets toc bullets-first

# Contents

* Ideas, Methodology & Tools
* Real life examples
* The many hells of Computer Science
* The "six" commandments

!SLIDE section

# Ideas

!SLIDE quote

# A good design is easy to change, rather than easy to configure
## someone, somewhere

!SLIDE

# There is no silver bullet

## Every architecture/design solution has pros & cons

!SLIDE

# Architecture & technology should fit the problem

!SLIDE

# Simple is better

!SLIDE bullets columns

# Simple solutions are easier to:

* grasp
* design
* code
* document
* mantain
* evolve

!SLIDE

## Architecture: the UNIX way

# Orchestrate simple components, each doing one thing, <br/>and doing it well

!SLIDE

# Design: SOLID rock

## KISS & DRY driven

<!--

son de OO pero aplicables a otro tipo de paradigmas


Single responsibility principle
  a class should have only a single responsibility.

Open/closed principle
  “software entities … should be open for extension, but closed for modification”.

Liskov substitution principle
  “objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program”. See also design by contract.

Interface segregation principle
  “many client-specific interfaces are better than one general-purpose interface.”[5]

Dependency inversion principle
  one should “Depend upon Abstractions. Do not depend upon concretions.”[5]
  Dependency injection is one method of following this principle.
-->


!SLIDE

# S for SRP
## Single Responsability Principle

!SLIDE

# SOLID leads to Design Patterns
## (Designs patterns are SOLID)

!SLIDE image

![Be OO, my friend](be_oo_my_friend.png)

<!--
  Sigue lo SOLID y encapuslación y todo esto en cualquier lenguaje/paradigma que te irá mejor :D
-->

!SLIDE bullets bullets-first

# Other useful buzzwords

* YAGNI
* CoC


!SLIDE code smallest

    @@@ xml
    <action path="/admin/ShowConfiguration"
      type="controller.admin.ShowConfigurationAction"
      scope="request">
      <forward name="success" 
               path=".admin.ShowConfiguration"/>
    </action>

!SLIDE image

![Y U NO admin.ShowConfiguration](yu_no_admin_showconfiguration.png)


!SLIDE bullets columns title-first

# TEST, TEST, TEST

* TDD, BDD
* Regresions
* Benchmarks
* DI
* Refactoring
* CI

<!--
  DI -> Dependency Injection
  Test complicado <-> código mal diseñado
  Test -> Definir el api desde el punto de vista del "cliente"
  Statist vs Mockist (Mock what you own)
-->

!SLIDE image

![Every time god kills a kitten](god_kitten.png)
