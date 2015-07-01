PostgreSQL
----------
Add to ``~/.bash_profile``

.. code-block::

	export PATH="/Applications/Postgres.app/Contents/Versions/9.4/bin:${PATH}"
	export PGHOST=localhost

Run in command line to link

.. code-block::

	sudo mv /usr/lib/libpq.5.dylib /usr/lib/libpq.5.dylib.old
	sudo ln -s /Applications/Postgres.app/Contents/Versions/9.4/lib/libpq.5.dylib /usr/lib