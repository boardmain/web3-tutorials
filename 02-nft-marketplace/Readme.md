Solidity Visibility

public - anyone can call
private - only this contract
internal - only this contract and inheriting contracts
external - only external call



struct Gallery {
	uint256 id,
	uint256 fee,
	address address
}

mapping (uint256 => Gallery) public galleries;
