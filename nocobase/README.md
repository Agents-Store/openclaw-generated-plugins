# @agents-store/nocobase

DEPRECATED — superseded by nocobase-dev, which bundles the official nocobase/skills library and works through the nb CLI and REST API. The MCP server this plugin wires has no counterpart in nocobase-dev yet. NocoBase platform development plugin. Expert guidance on collections, fields, relations, workflows, UI blocks, plugin development, MCP-powered page management, data operations, and collection inspection for NocoBase applications.

## Installation

```bash
openclaw plugins install @agents-store/nocobase
```

## Configuration

Set values in your OpenClaw config:

```json
{
  "plugins": {
    "entries": {
      "nocobase": {
        "enabled": true,
        "config": {
          "nocobaseEmail": "...",
          "nocobasePassword": "...",
          "nocobaseUrl": "..."
        }
      }
    }
  }
}
```

## Skills

- `collections-design` — Collection design patterns — collection types, naming conventions, system fields, inheritance, tree structures. This skill should be used when the user asks to design a data model, create collections, plan entity relationships, or choose collection types.
- `data-operations` — Data CRUD operations — list, create, update, delete records. This skill should be used when the user asks to add records, query or filter data, update fields, delete entries, or bulk create records.
- `examples` — Application design scenarios and reference implementations. This skill should be used when the user needs complete application examples, tool call patterns, or end-to-end workflow references.
- `fields-relations` — Field types and relation configuration — basic, advanced, relation fields, foreign keys, through tables. This skill should be used when the user asks to configure fields, set up relations between collections, or manage foreign keys and through tables.
- `plugin-development` — Plugin scaffolding and development — lifecycle, server-side, client-side, migrations, testing. This skill should be used when the user asks to develop custom plugins, extend platform functionality, or scaffold plugin structure.
- `ui-configuration` — UI blocks, pages, actions, and field components. This skill should be used when the user asks to create a page, add a table or form block, build a dashboard, set up a kanban board, or configure menu structure.
- `workflows-automations` — Workflow engine — triggers, node types, conditions, variables, approval flows. This skill should be used when the user asks to create workflows, set up triggers, build approval flows, or automate business processes.

## Source

Canonical: https://github.com/agents-store/claude-public-plugins/tree/main/plugins/nocobase
