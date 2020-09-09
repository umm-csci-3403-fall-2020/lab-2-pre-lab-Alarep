# Leak report

_The leak came from the cleaned variable inside of the is cleaned function. We can
free the memory by inserting free(cleaned) before the return call in the is cleanedfunction. We do not need the cleaned memory assignment anymore because we have already used the information in the result assignment before returning. _
