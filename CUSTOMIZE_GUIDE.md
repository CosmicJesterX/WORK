# Customization Guide

This is your honeypot scaffold. Follow these steps to make it your own.

## Step 1: Define Your Personas (30 min)

Edit `.hermes.md` → Personas section

Default 5 personas:
- TECHNICAL (Git, SSH, programming)
- AGGRESSIVE (Late-night, security tools)
- ARTISTIC (Creative hours, aesthetic)
- CURIOUS (Exploration, morning access)
- UNKNOWN (Neutral baseline)

Customize:
1. Replace with your user types
2. Update detection signals (what detects each persona)
3. Adjust messaging per persona

## Step 2: Design Your Trap Levels (1-2 hours)

Edit `.hermes.md` → Trap Levels section

Default 5 levels (Novice → Enlightened):
- Level 1: Silliness 6/10
- Level 2: Silliness 7/10
- Level 3: Silliness 8/10
- Level 4: Silliness 10/10
- Level 5: Silliness 12/10

Customize:
1. Choose your theme (graphics, logic, philosophy, etc.)
2. Design 15 trap variations per level
3. Create multiple escape routes per trap
4. Define learning payloads

## Step 3: Create Your Universe (1-2 hours)

Edit `lore/HONEYPOT_LORE.md`

Customize:
1. Write fictional setting/world
2. Create NPC trap characters (one per trap)
3. Design lore mechanics (how traps relate)
4. Define timeline/evolution

## Step 4: Build Portals (2-4 hours)

Update `portals/web_portal.html` and `portals/cli_portal.sh`

Customize:
1. Persona detection logic
2. Adaptive messaging
3. Visual/textual aesthetics
4. Lore reveal mechanics

## Step 5: Implement Traps (4-8 hours)

Create `traps/level_X/trap_name.sh` files

Customize:
1. Each trap: setup, escape routes, learning payload
2. Ensure graceful exits (Ctrl+C works)
3. 15-minute timeout default
4. Session tracking (anonymized UUID)

## Step 6: Set Up Automation (1 hour)

Edit `automation/evolution.sh` and schedule cron

Customize:
1. Cron schedule (default: Sundays 2 AM)
2. Evolution logic (session counting, ranking updates)
3. Lore update mechanics
4. Logging format

## Step 7: Test Everything (2-3 hours)

- [ ] Test all 3 portals
- [ ] Verify persona detection
- [ ] Check all 5 trap levels
- [ ] Test escape routes
- [ ] Verify session tracking
- [ ] Test Ctrl+C exits
- [ ] Confirm timeout works

## Step 8: Deploy (1 hour)

- [ ] Deploy web portal to server
- [ ] Make CLI accessible (git repo)
- [ ] Schedule cron job
- [ ] Document entry points
- [ ] Point users to CLI/web entry

---

Total estimated time: 12-25 hours
Can be parallelized (portals and traps built simultaneously)

