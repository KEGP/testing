# testing

## with pyownunit
run test suite with -s
`python pyowlunit/pyowlunit.py -s https://raw.githubusercontent.com/KEGP/testing/main/artist/suite.ttl -f turtle`

## with owl-unit
run test case with -c:  
`java -jar OWLUnit-0.3.2.jar -c https://raw.githubusercontent.com/KEGP/testing/main/artist/artistcq.ttl`

run test suite with -s:  
`java -jar OWLUnit-0.3.2.jar -s https://raw.githubusercontent.com/KEGP/testing/main/artist/artist-suite.ttl`


