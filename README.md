# ReverseBool.sol
ReverseBool.sol
pragma solidity ^0.8.20;
contract ReverseBool {
    bool public flag;

    function flip() public {
        flag = !flag;
    }
}
