https://packaging.python.org/en/latest/tutorials/packaging-projects/

from setuptools import setup, find_packages

setup(name='thematch_2.1',
		version='2.1',
		description='thematch_2.1',
		url='https://github.com/ExpertOfAI/thematch',
		author='ExpertOfAI1',
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
