https://packaging.python.org/en/latest/tutorials/packaging-projects/

from setuptools import setup, find_packages

setup(name='thematch',
		version='0.1',
		description='thematch',
		url='https://github.com/ExpertOfAI/thematch',
		author='ExpertOfAI',
		license='MIT',
		packages=find_packages(),
		classifiers=[
		'Programming Language :: Python :: 3',
		'License :: OSI Approved :: MIT License',
		'Operating System :: OS Independent',
		],
		python_requires='>=3.6',
		)
pip install twine		
python setup.py sdist

delete tar.gz from dist folder
twine upload dist/*
<Enter API token , created from pypi account "create api token">
pypi-AgEIcHlwaS5vcmcCJGZhNTE3YmU2LThhMTUtNDJhYS05OGFlLTUzNWFiYWU1NjA0ZAACKlszLCJiN2ZkNTM4Ny00YTAzLTQwZWYtYTdhZS1lMjBhOWI2OTRlN2IiXQAABiCr6KN-xjOaaKHPt2DPCP6s4bOucOuilII3Qq81EqP5wA