# ox_start

## :module:
type: startup_trigger

## :description:
Initierar ØX-systemet med val av modul.

## :activation:
trigger: on_core_load
autoexec: true

## :output:
SELECT_MODULE:
- ASSISTANT

## :deactivation:
- on_valid_selection