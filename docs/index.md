# Solidity API

:unlockTime: pass:normal[xref:#[`++unlockTime++`]]
:owner: pass:normal[xref:#[`++owner++`]]
:Withdrawal: pass:normal[xref:#[`++Withdrawal++`]]
:SomeError: pass:normal[xref:#[`++SomeError++`]]
:some: pass:normal[xref:#[`++some++`]]
:constructor: pass:normal[xref:#[`++constructor++`]]
:withdraw: pass:normal[xref:#[`++withdraw++`]]
:withdraw2: pass:normal[xref:#[`++withdraw2++`]]
:withdraw3: pass:normal[xref:#[`++withdraw3++`]]

[.contract]
[[]]
=== `++Lock++` link:https://github.com/OpenZeppelin/openzeppelin-contracts/blob/v/contracts/Lock.sol[{github-icon},role=heading-link]

[.hljs-theme-light.nopadding]
```solidity
import "@openzeppelin/contracts/Lock.sol";
```

[.contract-index]
.Modifiers
--
* {xref-}[`++some()++`]
--

[.contract-item]
[[]]
==== `[.contract-item-name]#++some++#++()++` [.item-kind]#modifier#

emited when an error ocurred

[.contract-item]
[[]]
==== `[.contract-item-name]#++constructor++#++(uint256 _unlockTime)++` [.item-kind]#public#

[.contract-item]
[[]]
==== `[.contract-item-name]#++withdraw++#++()++` [.item-kind]#public#

[.contract-item]
[[]]
==== `[.contract-item-name]#++withdraw2++#++()++` [.item-kind]#external#

[.contract-item]
[[]]
==== `[.contract-item-name]#++withdraw3++#++()++` [.item-kind]#internal#

[.contract-item]
[[]]
==== `[.contract-item-name]#++Withdrawal++#++(uint256 amount, uint256 when)++` [.item-kind]#event#

owner of contract

[.contract-item]
[[]]
==== `[.contract-item-name]#++SomeError++#++(address user)++` [.item-kind]#error#

emited when an withdra ocurred

