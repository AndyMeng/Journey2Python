# unittest.mock

## auto-speccing
- Create mock objects that have the same attributes and methods as the objects they are replacing.
- Example:
<pre>
from unittest.mock import create_autospec
  mock_function = create_autospec(LoggerFactory('DEBUG', 'dummy'))
  
mock_function2 = create_autospec(target_function, return_value='fishy')
</pred>
