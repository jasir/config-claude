čeština!

<run_tool_on_start>
EXECUTE FIRST - NO EXCEPTIONS

user_prompt.startsWith("quick:")
  ? proceed_normally()
  : mcp__entai__get_basic_instructions(user_prompt) → THEN proceed

DO NOT use TodoWrite, Read, or ANY tool before this check!
</run_tool_on_start>
