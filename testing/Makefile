install_deps:
	# Install Poetry
	curl -sSL https://install.python-poetry.org | python3 -
	export PATH=$PATH:$HOME/.local/bin

run: install_deps
	poetry install --no-root
	poetry run pytest 
