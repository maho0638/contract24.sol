# contract24.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

// Simple Web3 wallet mock contract
contract Contract24 {
    address public lastSender;

    function ping() public {
        lastSender = msg.sender;
    }
}
