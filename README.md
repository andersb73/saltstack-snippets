saltstack-snippets
==================

<h2>Install Windows:</h2>

Place files under:
	
	\AppData\Roaming\Sublime Text 2\Packages\User\YAML


<h2>My collection of SaltStack snippets:</h2>

<h4 id="256dark-features">Name:</h4>
 - salt-ssymlink

<h4 id="256dark-features">Shortcut/Command:</h4>
 - `ssymlink`

<h4 id="256dark-features">Description:</h4>
For making a file.symlink with parameters in pillar in salt.

<h4 id="256dark-features">Code</h4>
:

	ID
	  file.symlink:
	    - name: {{pillar['pillar_name']}}
	    - target: {{pillar['pillar_name']}}
