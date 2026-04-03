# SwitchState.sol
SwitchState.sol2
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SwitchState {
    bool public status;

    function toggle() public {
        status = !status;
    }
}
