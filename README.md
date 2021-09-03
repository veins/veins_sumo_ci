<a href="https://veins.car2x.org"><img width=30% src="http://veins.car2x.org/media/logo_veins.png"></a>
<a href="https://sumo.dlr.de/"><img width=40% src="https://github.com/eclipse/sumo/blob/main/docs/web/docs/images/sumo-logo.svg"></a>

Veins - Eclipse SUMO - Continuous Integration Test
==================================================
[![Linux](https://github.com/veins/veins_sumo_ci/actions/workflows/linux.yml/badge.svg)](https://github.com/veins/veins_sumo_ci/actions/workflows/linux.yml)

This repository hosts the [GitHub Actions Workflow](https://github.com/veins/veins_sumo_ci/blob/main/.github/workflows/linux.yml) for testing interoperability between
[Eclipse SUMO](https://sumo.dlr.de/) and [Veins](https://veins.car2x.org/)
by building [Veins](https://github.com/sommer/veins), [OMNeT++](https://github.com/omnetpp/omnetpp) and [SUMO](https://github.com/eclipse/sumo) 
from their respective repositories or installing their latest releases / nightly builds.

The objective is to have the badge above green all the time.

The log from the runs can be found in the [GitHub Action](https://github.com/veins/veins_sumo_ci/actions) artifacts.
