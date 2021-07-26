---
description: Learn how Minehut's Server Version works.
name: faq/other-questions/server-version
---

# Server Version

## Overview

Currently, Minehut allows support for regular Spigot and PaperSpigot 1.16 and 1.17 servers. You can change the server version anytime in the server panel settings in the **Appearance** tab in the server dashboard.

<Hint severity="warning">NOTE: Spigot may cause plugins not to work, so we recommend choosing PaperSpigot.</Hint>
<Hint severity="error">If you use a 1.16 server, you can't use 1.17 features.</Hint>

## ALLOWING OLDER CLIENTS TO JOIN

There are currently two different methods of allowing older clients to join. Read below.

### Method One

Install the plugin `ProtocolSupport`, and this will allow clients 1.8-1.16 to join.

### Method Two

Install the plugins `ViaVersion`, `ViaBackwards` and `ViaRewind`. These three combined will allow 1.8-1.16 clients to join.

## 1.8 COMBAT

Most PvP servers will want the original combat system, this is how.

To allow 1.8 combat _\(no hit delay\)_, install the plugin `OldCombatMechanics`.
