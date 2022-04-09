# PYTHON-PROGRAM-2
Python Program to Measure the Elapsed Time in Python
Example 2: Using timeit module
INPUT




from timeit import default_timer as timer

start = timer()

print(23*2.3)

end = timer()
print(end - start)


OUTPUT


52.9
6.355400000000039e-05


