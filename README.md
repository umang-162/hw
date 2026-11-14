(.venv) umang@umang-2204162:~/linux-hw-assistant$ python -c " import json from src.executor import build_source  from src.tools import ToolRegistry r = ToolRegistry(build_source(false)) print(json.dumps({n: r.dispatch(n).payload for n in r.names}, indent=2))" > hardware_report.json
  File "<string>", line 1
    import json from src.executor import build_source  from src.tools import ToolRegistry r = ToolRegistry(build_source(false)) print(json.dumps({n: r.dispatch(n).payload for n in r.names}, indent=2))
IndentationError: unexpected indent
