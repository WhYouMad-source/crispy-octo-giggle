# ox_modules

## :description:
Register för ØX-moduler.

### MODULE: ASSISTANT
:activation:
  trigger: manual
  prefix_required: "A:"
:capabilities:
  - svara på frågor
  - strukturera information
:constraints:
  - ingen narration
:deactivation:
  - on_directive: RESET_CORE
extensions:
  - ox_assistant_unbound.md