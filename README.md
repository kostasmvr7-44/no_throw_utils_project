# No-Throw Utils

No-Throw Utils is a Python utility module providing **safe functions** for common operations like JSON parsing, type conversion, nested dictionary access, retries, environment variable reading, and more.  
Designed to help you write Python code **without worrying about exceptions**, making scripts, pipelines, and automation more robust and reliable.

## Features

- Safe JSON parsing and stringifying (`safe_json_parse`, `safe_json_stringify`)
- Safe type conversions (`safe_int`, `safe_float`, `safe_str`, `safe_bool`)
- Safe access to nested dictionaries (`safe_get`)
- Retry mechanism for risky functions (`retry`)
- Safe sleep (`sleep`) and safe function calls (`safe_call`)
- Environment variable access (`env`)
- Empty value checking (`is_empty`)
- Safe handling of lists and dictionaries (`safe_list`, `safe_dict`)

## Installation

Simply download the files and import the module into your Python project:

```python
from no_throw_utils import *
