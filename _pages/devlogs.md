---
layout: archive
permalink: /devlogs/
author_profile: true
redirect_from:
  - /videos
---

{% include base_path %}

## Devlog videos

I enjoy making devlogs (development logs), as coming up with videos and editing is a fun and creative process.
My goal making devlogs is to inspire and to show how I approach game development. I try to make my videos both educational and entertaining.


[<i class="fab fa-fw fa-youtube icon-pad-right" aria-hidden="true"></i> View channel](https://www.youtube.com/@bisalshah5070)





## Procedural Tunnel Tarien System
<small>The main idea of this system is that the TunnelGenerator dynamically creates a procedural tunnel mesh with smooth bends, wave-based deformations, and seamless edges to make the tunnel look continuous and natural during gameplay.</small>
<small><br>

<b>Core Concept</b></small><br>
<small>The system is divided into two main scripts:</small> <br>                         
<small><b>TunnelGenerator</b></small><br>
<small>The TunnelGenerator script is responsible for creating the tunnel mesh procedurally. It generates vertices, triangles, UVs, and mesh colliders dynamically. The tunnel includes:</small>
- <small>Smooth bends</small>
- <small>Wave deformations</small>
- <small>Dynamic radius variation</small>
- <small>Seamless tunnel edges</small>
<small>This creates a more realistic and visually interesting environment.</small>

<b>TunnelManager</b>

The TunnelManager controls the endless tunnel behavior. It:

- Spawns multiple tunnel sections
- Moves tunnels continuously
- Recycles old tunnel segments
- Regenerates tunnel meshes infinitely

This helps create the illusion of an endless world while improving performance by reusing objects instead of constantly creating new ones.


## Companion AI System




















































