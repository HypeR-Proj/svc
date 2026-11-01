<!-- SPDX-FileCopyrightText: 2026 roolrz -->
<!-- SPDX-License-Identifier: Apache-2.0 -->

# HypeR services

This repository owns the category include lists. Each included project owns its
implementation, dependency lockfiles, configuration and delivered artifacts.
Repository locations belong to the manifest. Includes do not inherit configuration
or implicitly select programs for an image.

Add a project to the manifest and its category here to register a new component.
The manifest checks this catalog out at `build/svc/`. Implementations are
separate repositories under `svc/`, outside this catalog checkout.

Run `make -C build/svc` from the workspace root to build the group.
