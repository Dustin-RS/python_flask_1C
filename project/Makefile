PIP := venv\Scripts\pip
PYTHON3 := venv\Scripts\python
TESTS := venv\Scripts\pytest -v test_controllers.py

clear:
	rmdir /S /Q venv

test:
	${TESTS}
	
venv:
	python -m venv venv

install_requirements:
	${PIP} install -r requirements.txt

run:
	${PYTHON3} server.py