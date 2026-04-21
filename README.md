

https://github.com/user-attachments/assets/9c4035c9-033c-4d40-bbc7-81894d83d88e


    ================================================================================
    |                               SLEEK FRAMEWORK                                |
    |                                Version 1.1.0                                 |
    |                           Developed by Energyidev                            |
    ================================================================================

    DESCRIPTION:
    A high-performance UI effects library for Roblox. Powered by Janitor for 
    "Zero-Leak" memory management and UIScale to maintain Layout integrity.

    CORE FEATURES:
    - Memory-Safe: Automatic cleanup via Janitor to prevent memory leaks.
    - Layout Integrity: Uses UIScale to avoid breaking UIListLayouts/Constraints.
    - Type Support: Native Luau type-checking for Studio autocompletion.

    API DOCUMENTATION:
    Sleek:BindButton(Instance, Effects)
        -> Instance (GuiButton) : Target UI element (ImageButton or TextButton).
        -> Effects  (table)     : Configuration dictionary (Rotation, Sound, etc).

    EFFECT PARAMETERS (TABLE):
    - rotateOnHover (boolean) : Enables/Disables rotation when hovering.
    - soundOnClick  (string)  : Sound ID to play on click (e.g., "rbxassetid://...").
	
	
	EXAMPLE OF A SCRIPT:
	local Sleek = require(ReplicatedStorage.Sleek)
	Sleek:BindButton(myButton, "Simple", {rotateOnHover = true})
	
  ================================================================================
