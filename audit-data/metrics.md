
[<img width="200" alt="get in touch with Consensys Diligence" src="https://user-images.githubusercontent.com/2865694/56826101-91dcf380-685b-11e9-937c-af49c2510aa0.png">](https://diligence.consensys.net)<br/>
<sup>
[[  🌐  ](https://diligence.consensys.net)  [  📩  ](mailto:diligence@consensys.net)  [  🔥  ](https://consensys.github.io/diligence/)]
</sup><br/><br/>



# Solidity Metrics for 'CLI'

## Table of contents

- [Scope](#t-scope)
    - [Source Units in Scope](#t-source-Units-in-Scope)
    - [Out of Scope](#t-out-of-scope)
        - [Excluded Source Units](#t-out-of-scope-excluded-source-units)
        - [Duplicate Source Units](#t-out-of-scope-duplicate-source-units)
        - [Doppelganger Contracts](#t-out-of-scope-doppelganger-contracts)
- [Report Overview](#t-report)
    - [Risk Summary](#t-risk)
    - [Source Lines](#t-source-lines)
    - [Inline Documentation](#t-inline-documentation)
    - [Components](#t-components)
    - [Exposed Functions](#t-exposed-functions)
    - [StateVariables](#t-statevariables)
    - [Capabilities](#t-capabilities)
    - [Dependencies](#t-package-imports)
    - [Totals](#t-totals)

## <span id=t-scope>Scope</span>

This section lists files that are in scope for the metrics report. 

- **Project:** `'CLI'`
- **Included Files:** 
    - ``
- **Excluded Paths:** 
    - ``
- **File Limit:** `undefined`
    - **Exclude File list Limit:** `undefined`

- **Workspace Repository:** `unknown` (`undefined`@`undefined`)

### <span id=t-source-Units-in-Scope>Source Units in Scope</span>

Source Units Analyzed: **`3`**<br>
Source Units in Scope: **`3`** (**100%**)

| Type | File   | Logic Contracts | Interfaces | Lines | nLines | nSLOC | Comment Lines | Complex. Score | Capabilities |
| ---- | ------ | --------------- | ---------- | ----- | ------ | ----- | ------------- | -------------- | ------------ | 
| 📝 | liquid-infrastructure/contracts/LiquidInfrastructureERC20.sol | 1 | **** | 477 | 458 | 251 | 158 | 201 | **<abbr title='Initiates ETH Value Transfer'>📤</abbr>** |
| 📝 | liquid-infrastructure/contracts/LiquidInfrastructureNFT.sol | 1 | **** | 206 | 192 | 74 | 107 | 68 | **<abbr title='Initiates ETH Value Transfer'>📤</abbr>** |
| 🎨 | liquid-infrastructure/contracts/OwnableApprovableERC721.sol | 1 | **** | 43 | 43 | 19 | 22 | 13 | **** |
| 📝🎨 | **Totals** | **3** | **** | **726**  | **693** | **344** | **287** | **282** | **<abbr title='Initiates ETH Value Transfer'>📤</abbr>** |

<sub>
Legend: <a onclick="toggleVisibility('table-legend', this)">[➕]</a>
<div id="table-legend" style="display:none">

<ul>
<li> <b>Lines</b>: total lines of the source unit </li>
<li> <b>nLines</b>: normalized lines of the source unit (e.g. normalizes functions spanning multiple lines) </li>
<li> <b>nSLOC</b>: normalized source lines of code (only source-code lines; no comments, no blank lines) </li>
<li> <b>Comment Lines</b>: lines containing single or block comments </li>
<li> <b>Complexity Score</b>: a custom complexity score derived from code statements that are known to introduce code complexity (branches, loops, calls, external interfaces, ...) </li>
</ul>

</div>
</sub>


#### <span id=t-out-of-scope>Out of Scope</span>

##### <span id=t-out-of-scope-excluded-source-units>Excluded Source Units</span>

Source Units Excluded: **`0`**

<a onclick="toggleVisibility('excluded-files', this)">[➕]</a>
<div id="excluded-files" style="display:none">
| File   |
| ------ |
| None |

</div>


##### <span id=t-out-of-scope-duplicate-source-units>Duplicate Source Units</span>

Duplicate Source Units Excluded: **`0`** 

<a onclick="toggleVisibility('duplicate-files', this)">[➕]</a>
<div id="duplicate-files" style="display:none">
| File   |
| ------ |
| None |

</div>

##### <span id=t-out-of-scope-doppelganger-contracts>Doppelganger Contracts</span>

Doppelganger Contracts: **`0`** 

<a onclick="toggleVisibility('doppelganger-contracts', this)">[➕]</a>
<div id="doppelganger-contracts" style="display:none">
| File   | Contract | Doppelganger | 
| ------ | -------- | ------------ |


</div>


## <span id=t-report>Report</span>

### Overview

The analysis finished with **`0`** errors and **`0`** duplicate files.





#### <span id=t-risk>Risk</span>

<div class="wrapper" style="max-width: 512px; margin: auto">
			<canvas id="chart-risk-summary"></canvas>
</div>

#### <span id=t-source-lines>Source Lines (sloc vs. nsloc)</span>

<div class="wrapper" style="max-width: 512px; margin: auto">
    <canvas id="chart-nsloc-total"></canvas>
</div>

#### <span id=t-inline-documentation>Inline Documentation</span>

- **Comment-to-Source Ratio:** On average there are`1.31` code lines per comment (lower=better).
- **ToDo's:** `0` 

#### <span id=t-components>Components</span>

| 📝Contracts   | 📚Libraries | 🔍Interfaces | 🎨Abstract |
| ------------- | ----------- | ------------ | ---------- |
| 2 | 0  | 0  | 1 |

#### <span id=t-exposed-functions>Exposed Functions</span>

This section lists functions that are explicitly declared public or payable. Please note that getter methods for public stateVars are not included.  

| 🌐Public   | 💰Payable |
| ---------- | --------- |
| 19 | 0  | 

| External   | Internal | Private | Pure | View |
| ---------- | -------- | ------- | ---- | ---- |
| 0 | 31  | 0 | 0 | 4 |

#### <span id=t-statevariables>StateVariables</span>

| Total      | 🌐Public  |
| ---------- | --------- |
| 15  | 8 |

#### <span id=t-capabilities>Capabilities</span>

| Solidity Versions observed | 🧪 Experimental Features | 💰 Can Receive Funds | 🖥 Uses Assembly | 💣 Has Destroyable Contracts | 
| -------------------------- | ------------------------ | -------------------- | ---------------- | ---------------------------- |
| `0.8.12` |  | **** | **** | **** | 

| 📤 Transfers ETH | ⚡ Low-Level Calls | 👥 DelegateCall | 🧮 Uses Hash Functions | 🔖 ECRecover | 🌀 New/Create/Create2 |
| ---------------- | ----------------- | --------------- | ---------------------- | ------------ | --------------------- |
| `yes` | **** | **** | **** | **** | **** | 

| ♻️ TryCatch | Σ Unchecked |
| ---------- | ----------- |
| **** | **** |

#### <span id=t-package-imports>Dependencies / External Imports</span>

| Dependency / Import Path | Count  | 
| ------------------------ | ------ |
| @openzeppelin/contracts/access/Ownable.sol | 1 |
| @openzeppelin/contracts/security/ReentrancyGuard.sol | 1 |
| @openzeppelin/contracts/token/ERC20/ERC20.sol | 1 |
| @openzeppelin/contracts/token/ERC20/IERC20.sol | 2 |
| @openzeppelin/contracts/token/ERC20/extensions/ERC20Burnable.sol | 1 |
| @openzeppelin/contracts/token/ERC721/ERC721.sol | 2 |
| @openzeppelin/contracts/token/ERC721/utils/ERC721Holder.sol | 1 |
| @openzeppelin/contracts/utils/Context.sol | 1 |
| @openzeppelin/contracts/utils/math/Math.sol | 1 |

#### <span id=t-totals>Totals</span>

##### Summary

<div class="wrapper" style="max-width: 90%; margin: auto">
    <canvas id="chart-num-bar"></canvas>
</div>

##### AST Node Statistics

###### Function Calls

<div class="wrapper" style="max-width: 90%; margin: auto">
    <canvas id="chart-num-bar-ast-funccalls"></canvas>
</div>

###### Assembly Calls

<div class="wrapper" style="max-width: 90%; margin: auto">
    <canvas id="chart-num-bar-ast-asmcalls"></canvas>
</div>

###### AST Total

<div class="wrapper" style="max-width: 90%; margin: auto">
    <canvas id="chart-num-bar-ast"></canvas>
</div>

##### Inheritance Graph

<a onclick="toggleVisibility('surya-inherit', this)">[➕]</a>
<div id="surya-inherit" style="display:none">
<div class="wrapper" style="max-width: 512px; margin: auto">
    <div id="surya-inheritance" style="text-align: center;"></div> 
</div>
</div>

##### CallGraph

<a onclick="toggleVisibility('surya-call', this)">[➕]</a>
<div id="surya-call" style="display:none">
<div class="wrapper" style="max-width: 512px; margin: auto">
    <div id="surya-callgraph" style="text-align: center;"></div>
</div>
</div>

###### Contract Summary

<a onclick="toggleVisibility('surya-mdreport', this)">[➕]</a>
<div id="surya-mdreport" style="display:none">
 Sūrya's Description Report

 Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| liquid-infrastructure/contracts/LiquidInfrastructureERC20.sol | [object Promise] |
| liquid-infrastructure/contracts/LiquidInfrastructureNFT.sol | [object Promise] |
| liquid-infrastructure/contracts/OwnableApprovableERC721.sol | [object Promise] |


 Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **LiquidInfrastructureERC20** | Implementation | ERC20, ERC20Burnable, Ownable, ERC721Holder, ReentrancyGuard |||
| └ | isApprovedHolder | Public ❗️ |   |NO❗️ |
| └ | approveHolder | Public ❗️ | 🛑  | onlyOwner |
| └ | disapproveHolder | Public ❗️ | 🛑  | onlyOwner |
| └ | _beforeTokenTransfer | Internal 🔒 | 🛑  | |
| └ | _beforeMintOrBurn | Internal 🔒 |   | |
| └ | _afterTokenTransfer | Internal 🔒 | 🛑  | |
| └ | distributeToAllHolders | Public ❗️ | 🛑  |NO❗️ |
| └ | distribute | Public ❗️ | 🛑  | nonReentrant |
| └ | _isPastMinDistributionPeriod | Internal 🔒 |   | |
| └ | _beginDistribution | Internal 🔒 | 🛑  | |
| └ | _endDistribution | Internal 🔒 | 🛑  | |
| └ | mintAndDistribute | Public ❗️ | 🛑  | onlyOwner |
| └ | mint | Public ❗️ | 🛑  | onlyOwner nonReentrant |
| └ | burnAndDistribute | Public ❗️ | 🛑  |NO❗️ |
| └ | burnFromAndDistribute | Public ❗️ | 🛑  |NO❗️ |
| └ | withdrawFromAllManagedNFTs | Public ❗️ | 🛑  |NO❗️ |
| └ | withdrawFromManagedNFTs | Public ❗️ | 🛑  |NO❗️ |
| └ | addManagedNFT | Public ❗️ | 🛑  | onlyOwner |
| └ | releaseManagedNFT | Public ❗️ | 🛑  | onlyOwner nonReentrant |
| └ | setDistributableERC20s | Public ❗️ | 🛑  | onlyOwner |
| └ | <Constructor> | Public ❗️ | 🛑  | ERC20 Ownable |
||||||
| **LiquidInfrastructureNFT** | Implementation | ERC721, OwnableApprovableERC721 |||
| └ | <Constructor> | Public ❗️ | 🛑  | ERC721 |
| └ | getThresholds | Public ❗️ |   |NO❗️ |
| └ | setThresholds | Public ❗️ | 🛑  | onlyOwnerOrApproved |
| └ | withdrawBalances | Public ❗️ | 🛑  |NO❗️ |
| └ | withdrawBalancesTo | Public ❗️ | 🛑  |NO❗️ |
| └ | _withdrawBalancesTo | Internal 🔒 | 🛑  | |
| └ | recoverAccount | Public ❗️ | 🛑  | onlyOwner |
||||||
| **OwnableApprovableERC721** | Implementation | Context, ERC721 |||


 Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    🛑    | Function can modify state |
|    💵    | Function is payable |
 

</div>
____
<sub>
Thinking about smart contract security? We can provide training, ongoing advice, and smart contract auditing. [Contact us](https://diligence.consensys.net/contact/).
</sub>


