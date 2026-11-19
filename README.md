# Calculator lab project
## How to run it
Python 3

SCCM4910 environment activation command:
source /opt/python-venv/sccm-4910/bin/activate

Run: ./run.sh

Sample Test: Enter 6 for the first number
	     Enter * for the operator
             Enter 7 for the second number
expect Result: 42.0

Stop with Ctrl+C

Run: ./check.sh

Expected result: 5 tests passed

enter 'echo$?' right after running check.sh
what each exit status means
0: pytest succeeded
1: means some test(s) failed
5: means no tests were collected





