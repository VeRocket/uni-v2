# ZumoSwap (Uniswap V2 Fork)

## Credits
This is a fork of several repositories from VeChain Community public source code.
https://github.com/VeChainDEXCode/uni-v2

All tests passed.

# For Developers
```bash
/uniswap-lib            # util libraries
/uniswap-v2-core        # core contracts for assets
/uniswap-v2-periphery   # surrounding contract for user interface
```

```bash
make install # install dependencies.
make compile # Compile all contracts.
make test # Run all the tests.
```

# Branches in this repo:

## `main` branch

What is changed:
- Change variable names of LP token `symbol` and `name`. (uniswap-v2-core/contracts/UniswapV2ERC20.sol)
- `CREATE2` hash. (uniswap-v2-periphery/contracts/libraries/UniswapV2Library.sol)

What remains:
- `chainId()` call remains the same.
- Compiler option `istanbul` remains the same.

This is compatible with VeChain after update of thor code `1.5.1`

# Disclaimer (I)

- This repo keeps the upstream license of GPL-3.0.
- Neither the name of ZumoSwap nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

# Disclaimer (II)
Redistributions of source code must retain this list of conditions and the following disclaimer.

Neither the name of VeChain (VeChain Foundation) nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS “AS IS” AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.