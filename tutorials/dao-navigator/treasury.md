# Treasury

The main treasury of a DAO is what backs the meme tokens with underlying value. Meme tokens can be burned at any time for a proportional claim of the main treasury. This is know as RageQuit.&#x20;

A siloDAO's main treasury is a [Safe](https://safe.global/). So anything a Safe can do, a siloDAO treasury can do also.

siloDAOs can also create as many additional Safes as needed that act as side vaults. These side vaults can be used for managing assets that meme token holders shouldn't have access to. For instance, a side vault comes with a siloDAO by default to manage the DAO's uncirculated meme token supply.

_<mark style="color:red;">A siloDAO's meme tokens should never be transferred into the main treasury.</mark>_

Doing so create a RageQuit loop. So for example, if there are other assets within the treasury, a meme token holder could burn their tokens, collect their portion of assets in the treasury, meme tokens included, and then RageQuit again. While the returns do diminish each time, it still isn't an ideal situation.
