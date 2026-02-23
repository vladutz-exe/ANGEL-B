# ANGEL-B

A 2D space shoot’em’up built in Love2D with procedurally generated waves, modular enemy behaviors, and a configurable upgrade system.

## Download & Play

- **Windows build:** go to *Releases* → download `ANGEL_B.zip`
- **Browser/Itch demo:** https://iamcatmeow.itch.io/angel-b

## About

ANGEL-B is a wave-based space shooter that becomes a bullet-hell challenge at later stages. You earn credits by defeating enemies, spend them on upgrades at a shady shop, and experiment with multiple playstyles like tank, demolitionist, or speedster.

## Gameplay Systems

### Player & Combat
- Cursor-based ship rotation and movement
- Configurable shooting patterns (spread, fire rate, etc.)
- Damage & health framework

### Enemy & AI
- Wave generator with escalating difficulty
- Modular boss behaviors with multiple attacks

### Shop & Upgrades
- Credit economy and upgrade storefront
- Equipable weapons and stat modifiers

## Technical Highlights

- `main.lua` — main game loop and state orchestration  
- `enemies.lua` — enemy definitions and spawning logic  
- `weapons.lua` — weapon and upgrade definitions  
- Object pooling with Lua tables for efficient bullet/enemy reuse

## What I Learned

This project strengthened my understanding of modular gameplay systems, data-driven design, and optimization via object pooling in Lua.

![angel](https://github.com/user-attachments/assets/8bb4f7d4-ebb7-4810-96d5-a197f26bdb38)

