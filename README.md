Wellspring
===========

A fork of paper with some minor tweaks to allow for additional content, modification of internal Minecraft features and better access to the Minecraft Registry for plugins.
No breaking changes will be made to existing features. Wellspring's sole aim is to provide more accessibilty.

Current additional features:
-----
 * Attachment system to allow for custom fields, methods and utilities to be added to entities and other 'Attachable' objects.
 * Extended potion registry allowing for custom potion types to be registered.
 * Custom entities can now be saved properly over restarts, and displayed correctly to the client.
 * Conversion of attributes from an enum to a field to allow for custom attribute types to work properly with Bukkit.
 * Entity default attribute map is now mutable, allowing for more freedom to customise and edit entity types, and to add new ones.
 * Code changes to allow for the proper creation, storage and viewing of custom entity types.

Planned future features:
-----
 * Interface layer with Bukkit for creating attributes, goals, custom entities, potions and enchantments.
 * Replacement of all of the idiotic Bukkit enums - allowing for mod content, items, APIs, etc. to be added easily.
 * Interface layer with Bukkit for a simple packet-sending system.
 * Interface layer with Bukkit for managing basic client-side entities.

This project forms part of the base for KenzieServer. Additions may be inconsistent, but it will generally be maintained as it is used in live production servers.

See [Paper](https://github.com/PaperMC/Paper) for more information about the parent fork, and for compiling instructions.
