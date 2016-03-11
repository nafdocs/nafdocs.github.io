---
title: Cr – Capability Roadmap
layout: page
id: cr
legacy: "NAF v3: NCV-3 MODAF: StV-3"
---


The Cr provides a representation of the actual or estimated availability
of capabilities over a period of time (derived from capability delivery
milestones in acquisition projects).

## Background

Cr Views support the Capability Audit process and similar processes used
across different communities of interest by providing a method to
identify gaps or duplication in capability provision.

The view indicates capability increments, which are derived from
delivery milestones within acquisition projects.

## Usage

-   Capability planning (capability phasing).
-   Capability integration planning.
-   Capability gap analysis.
-   High-level dashboard for acquisition management.

## Representation

Cr is usually shown as a timeline with rows for each capability. The
timescale is measured horizontally. Resources that provide those
capabilities are shown as bars within the rows. The width of the bar
depends on the service life of the resources.

## Detailed View Description

The Cr provides a representation of the available capability levels at
different points in time or during specific periods of time (associated
with the Enterprise Phases – see [C2](c2.html)).

The Cr view is presented as a timing chart showing capabilities on the
vertical axis and time on the horizontal axis. Active capability
configurations are shown as bars against the capabilities they provide,
with the start and end of the bars corresponding to the capability
configuration coming into and going out of service. Where nothing meets
a particular capability at a particular time, whitespace is shown so as
to highlight capability gaps.

![cr-example-1](http://nafdocs.org/wp-content/uploads/2013/06/cr-example-1.png)

The view is created by analysing project data to determine when projects
acquiring resources that provide military capability are to be
delivered, upgraded and/or withdrawn (this data may be provided in part
by a [Lines of Development View (Lr)](lr.html), and the mappings from
capability to resources that is provided in [P2](p2.html) and [Pr](pr.html)).

The output from this iterative approach is a tabular view that
represents the required capability phasing. However, there is a variant
view in which the table is overlaid with the names of the projects that
will deliver the capability increments:

![cr-example-2](http://nafdocs.org/wp-content/uploads/2013/06/cr-example-2.png)


The essence of this variant view is the relationship between projects,
capabilities and time (normally, an StV-3 will hide the project). The
view may be used to determine the need for interventions in projects (to
fulfil a capability gap) or to represent current plans (the availability
of capability according to their delivery timescales).

A Cr can be used to assist in the identification of capability
gaps/shortfalls (no capability configurations that fulfil a particular
capability) or capability duplication/overlap (multiple fielded
capabilities for a single capability function).

*Note that [C2](c2.html) specifies the requirement for capability at each
Enterprise Phase, whereas Cr reflects the output of capability
programmes (e.g. acquisition, training, etc.) over time. The requirement
specified in [C2](c2.html) may or may not be met by those programmes.*

## Key Elements and Their Relationships


![cr-hlmm](http://nafdocs.org/wp-content/uploads/2013/06/cr-hlmm.png)

-   Capability
-   Resource Package
-   Capability Configuration
-   Project
-   Project Milestone


