OnToHow Lua 
*Author : wolenek1* 
(-asby-) 1 : 22-2 (local switch = menu.Switch("Neverlose", "Switch", false, "Tooltip")
(hitboxes_lua)
 0. head
    1. neck 
    2. pelvis 
    3. stomach 
    4. lower chest 
    5. chest 
    6. upper chest 
    7. right thigh 
    8. DELETE
    12. left foot 
    13. right hand 
    14. left hand 
    15. right upper arm 
    16. right forearm 
    17. left upper arm 
    18. left forearm
    19. [button - Start Lua+_crate] Anti-Aim
    20. &- Option AA
    21. &- Option Inventer AA
    22. )goin(
    23. local game_movement = utils.CreateInterface("client.dll", "GameMovement001")
    24. antiaim.OverrideLimit(40)
    25. antiaim.OverridePitch(90) -- UP AA)
    26. local inverter_state = antiaim.GetInverterState(1)
    27. Local : AA super (gave - state_antia
