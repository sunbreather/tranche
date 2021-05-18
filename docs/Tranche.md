## `Tranche`



ERC20 token to represent a single tranche for a ButtonTranche bond



### `constructor()` (public)



Constructor for Tranche ERC20 token

### `init(string name, string symbol, address _collateralToken)` (public)



Constructor for Tranche ERC@0 token


### `mint(address to, uint256 amount)` (external)



Mint `amount` tokens to `to`
 Only callable by the owner (bond controller). Used to
 manage bonds, specifically creating tokens upon deposit


### `burn(address from, uint256 amount)` (external)



Burn `amount` tokens from `from`'s balance
 Only callable by the owner (bond controller). Used to
 manage bonds, specifically burning tokens upon redemption


### `redeem(address from, address to, uint256 amount)` (external)



Burn `amount` tokens from `from` and return the proportional
value of the collateral token to `to`


