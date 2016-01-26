# vscode-extension-cybol

This Visual Studio Code extension provides syntax highlighting support and snippets for CYBOL specific file.


### Manual Installation:


1. Install Visual Studio Code from [https://code.visualstudio.com/](https://code.visualstudio.com/).
2. Locate your home folder. 
  - on **Windows**, your home folder is probably C:\Users\\*YourName*, 
  - on **Mac** it's probably /Users/*yourname* and 
  - on **Linux** it's probably /home/*yourname*
3. Place the 'vscode-extension-cybol' folder under *[your_home_folder]*/.vscode/extensions.
4. Restart Visual Studio Code

### Supported file extensions:

* .cybol

### Usage

Type the following commands and hit enter or tab.

[mnml] - Create Master Node with License Header

```xml
<!--
    Copyright (C) 1999-2016. Christian Heller.

    This knowledge model uses the Cybernetics Oriented Language (CYBOL).

    CYBOL is free software: you can redistribute it and/or modify it
    under the terms of the GNU General Public License as published
    by the Free Software Foundation, either version 3 of the License,
    or (at your option) any later version.

    CYBOL is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty
    of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
    See the GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with CYBOL. If not, see <http://www.gnu.org/licenses/>.

    Cybernetics Oriented Programming (CYBOP) <http://www.cybop.org/>
    CYBOP Developers <cybop-developers@nongnu.org>

    @version CYBOP 0.17.0 2015-04-20
    @author Christian Heller <christian.heller@tuxtax.de>
-->

<!--
    Program Description
-->

<node>

    <!-- Content -->

</node>
```

[mnol] - Create Master Node without License Header

```xml
<node>

    <!-- Content -->

</node>
```

[sn] - Create Node with Attributes

```xml
<node name="node_name" channel="channel" format="category/method" model="model" />
```

[mn] - Create Node with Sub Node and Attributes

```xml
<node name="node_name" channel="channel" format="category/method" model="model">
    <node name="sub_node_name" channel="sub_channel" format="category/method" model="sub_model" />
</node>

```