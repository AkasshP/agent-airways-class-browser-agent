# Agent Airways Part 2 Team Report

## Team information

- Team: Team 05
- Team members: Akassh Paramasivan and Ramya Karuthappandian
- Assigned tool: `list_flights`
- Tool file: `team_tools/list_flights.py`
- Test file: `team_tests/test_list_flights.py`
- Model: Ollama `qwen3:8b`
- Commit tested: `f532b71`

## Tool purpose

The `list_flights` tool is a read-only browser tool. It reads the visible flight cards from the Agent Airways results screen and returns each flight's ID, stop description, and displayed price.

The tool requires an empty argument:

```json
{
  "action": "list_flights",
  "argument": {}
}