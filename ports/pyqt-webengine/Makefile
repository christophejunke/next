PYTHON ?= python
PIP ?= pip


install:
	$(PIP) install -r requirements.txt

run:
	$(PYTHON) next-pyqt-webengine.py

build-webengine:
	pyinstaller next-pyqt-webengine.py

isort:
	isort -y --atomic

qa:
	flake8 *.py

clean:
	rm -rf build
	rm -rf dist
