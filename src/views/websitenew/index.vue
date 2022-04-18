<template>
  <div>
    <div class="main-container">
      <full-page :options="options" id="fullpage" ref="fullpage">
        <div class="section">
          <div class="section-one">
            <div class="grid grid-cols-1 justify-between text-center">
              <img
                class="section-img desktop"
                alt="logo"
                src="../../assets/landing-page/petaland.png"
              />
              <img
                class="section-img-mb mobile"
                alt="logo"
                src="../../assets/landing-page/petaland.png"
              />
              <span
                class="
                  imposter
                  xs:text-sm
                  md:text-sm
                  lg:text-lg
                  xl:text-3xl
                  2xl:text-3xl
                  text-white
                  desktop
                "
                style="margin-top: -150px"
              >
                PLAY CRAFT EARN
              </span>
              <span
                class="
                  imposter
                  xs:text-sm
                  md:text-sm
                  lg:text-lg
                  xl:text-3xl
                  2xl:text-3xl
                  text-white
                  mobile
                "
              >
                PLAY CRAFT EARN
              </span>
            </div>
          </div>
          <!-- <kinesis-container event="move">
            <section class="cover cover-features imagebg height-100 text-start">
              <div class="background-image-holder">
                <img alt="background" src="../../assets/petaland.png" />
              </div>
            </section>
          </kinesis-container> -->
        </div>
        <div class="section" style="position: relative">
          <div class="section-two"></div>
          <div class="content desktop">
            <div class="grid grid-cols-1 justify-between">
              <div class="container text-uppercase">
                <div class="row" style="margin-top: 5%">
                  <h1
                    class="
                      imposter
                      xs:text-sm
                      md:text-sm
                      lg:text-lg
                      xl:text-3xl
                      2xl:text-3xl
                      text-white
                    "
                  >
                    game concept
                  </h1>
                </div>
                <div class="row" style="margin-top: 20%">
                  <div class="col-2">
                    <img
                      alt="gameplay1"
                      src="../../assets/landing-page/play.png"
                      style="max-height: 64px; margin: auto"
                    />
                  </div>
                  <div class="col-2">
                    <h1
                      class="
                        imposter
                        xs:text-sm
                        md:text-sm
                        lg:text-lg
                        xl:text-3xl
                        2xl:text-3xl
                        text-white
                      "
                    >
                      PLAY
                    </h1>
                  </div>
                  <div class="col-8">
                    <span
                      class="
                        imposter
                        xs:text-sm
                        md:text-sm
                        lg:text-lg
                        xl:text-2xl
                        2xl:text-2xl
                        text-white
                        desc-line
                      "
                    >
                      To play a real game and find a new community for cultural
                      exchange in the metaverse.
                    </span>
                  </div>
                </div>
                <div class="row mt-5">
                  <div class="col-2">
                    <img
                      alt="gameplay1"
                      src="../../assets/landing-page/craft.png"
                      style="max-height: 64px; margin: auto"
                    />
                  </div>
                  <div class="col-2">
                    <h1
                      class="
                        imposter
                        xs:text-sm
                        md:text-sm
                        lg:text-lg
                        xl:text-3xl
                        2xl:text-3xl
                        text-white
                      "
                    >
                      CRAFT
                    </h1>
                  </div>
                  <div class="col-8">
                    <span
                      class="
                        imposter
                        xs:text-sm
                        md:text-sm
                        lg:text-lg
                        xl:text-2xl
                        2xl:text-2xl
                        text-white
                        desc-line
                      "
                    >
                      The use of in-game materials to create exclusive items
                      that need users know-how & creativity.
                    </span>
                  </div>
                </div>
                <div class="row mt-5">
                  <div class="col-2">
                    <img
                      alt="gameplay1"
                      src="../../assets/landing-page/earn.png"
                      style="max-height: 64px; margin: auto"
                    />
                  </div>
                  <div class="col-2">
                    <h1
                      class="
                        imposter
                        xs:text-sm
                        md:text-sm
                        lg:text-lg
                        xl:text-3xl
                        2xl:text-3xl
                        text-white
                      "
                    >
                      EARN
                    </h1>
                  </div>
                  <div class="col-8">
                    <span
                      class="
                        imposter
                        xs:text-sm
                        md:text-sm
                        lg:text-lg
                        xl:text-2xl
                        2xl:text-2xl
                        text-white
                        desc-line
                      "
                    >
                      Users will be able to earn by selling crafted items,
                      farming, trading and etc.
                    </span>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="content mobile">
            <div class="grid grid-cols-1 justify-between">
              <div class="container text-uppercase">
                <div class="row" style="margin-top: 15%">
                  <h1
                    class="
                      imposter
                      xs:text-sm
                      md:text-sm
                      lg:text-lg
                      xl:text-3xl
                      2xl:text-3xl
                      text-white
                    "
                  >
                    game concept
                  </h1>
                </div>
                <div class="row" style="margin-top: 10%">
                  <div class="col-12">
                    <h1
                      class="
                        imposter
                        xs:text-sm
                        md:text-sm
                        lg:text-lg
                        xl:text-3xl
                        2xl:text-3xl
                        text-white
                      "
                    >
                      PLAY
                    </h1>
                  </div>
                  <div class="col-12">
                    <img
                      alt="gameplay1"
                      src="../../assets/landing-page/play.png"
                      style="max-height: 50px; margin: auto"
                    />
                  </div>
                  <div class="col-12">
                    <span
                      class="
                        imposter
                        xs:text-xs
                        md:text-xs
                        lg:text-lg
                        xl:text-2xl
                        2xl:text-2xl
                        text-white
                        desc-line
                      "
                    >
                      To play a real game and find a new community for cultural
                      exchange in the metaverse.
                    </span>
                  </div>
                </div>
                <div class="row mt-5">
                  <div class="col-12">
                    <h1
                      class="
                        imposter
                        xs:text-sm
                        md:text-sm
                        lg:text-lg
                        xl:text-3xl
                        2xl:text-3xl
                        text-white
                      "
                    >
                      craft
                    </h1>
                  </div>
                  <div class="col-12">
                    <img
                      alt="gameplay1"
                      src="../../assets/landing-page/craft.png"
                      style="max-height: 50px; margin: auto"
                    />
                  </div>
                  <div class="col-12">
                    <span
                      class="
                        imposter
                        xs:text-xs
                        md:text-xs
                        lg:text-lg
                        xl:text-2xl
                        2xl:text-2xl
                        text-white
                        desc-line
                      "
                    >
                      The use of in-game materials to create exclusive items
                      that need users know-how & creativity.
                    </span>
                  </div>
                </div>
                <div class="row mt-5">
                  <div class="col-12">
                    <h1
                      class="
                        imposter
                        xs:text-sm
                        md:text-sm
                        lg:text-lg
                        xl:text-3xl
                        2xl:text-3xl
                        text-white
                      "
                    >
                      EARN
                    </h1>
                  </div>
                  <div class="col-12">
                    <img
                      alt="gameplay1"
                      src="../../assets/landing-page/earn.png"
                      style="max-height: 50px; margin: auto"
                    />
                  </div>
                  <div class="col-12">
                    <span
                      class="
                        imposter
                        xs:text-xs
                        md:text-xs
                        lg:text-lg
                        xl:text-2xl
                        2xl:text-2xl
                        text-white
                        desc-line
                      "
                    >
                      Users will be able to earn by selling crafted items,
                      farming, trading and etc.
                    </span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="section" style="position: relative">
          <div class="section-six"></div>
          <div class="content desktop">
            <div class="grid grid-cols-1 justify-between">
              <div class="container text-uppercase">
                <div class="row">
                  <div class="col-6">
                    <img
                      alt="gameplay1"
                      src="../../assets/landing-page/gameplay1.png"
                      style="max-height: 456px; margin: auto; padding: 20px"
                    />
                  </div>
                  <div class="col-6">
                    <div style="padding: 20%">
                      <span
                        class="
                          imposter
                          xs:text-sm
                          md:text-sm
                          lg:text-lg
                          xl:text-xl
                          2xl:text-xl
                          text-white
                          desc-line
                        "
                      >
                        Use your NFTs Tools to gather the resources such as
                        stones, woods, fibers and ores for crafting other tools
                        and equipments.
                      </span>
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-6">
                    <div style="padding: 20%">
                      <span
                        class="
                          imposter
                          xs:text-sm
                          md:text-sm
                          lg:text-lg
                          xl:text-xl
                          2xl:text-xl
                          text-white
                          desc-line
                        "
                      >
                        In Petaland, there are millions of resources for
                        players. However, there are a ton of monsters in farming
                        as well and the amount of resources and monsters depend
                        on the landscape.
                      </span>
                    </div>
                  </div>
                  <div class="col-6">
                    <img
                      alt="gameplay2"
                      src="../../assets/landing-page/gameplay2.png"
                      style="max-height: 456px; margin: auto; padding: 20px"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="content mobile">
            <div class="grid grid-cols-1 justify-between">
              <div class="container text-uppercase">
                <div class="row">
                  <div class="col-12">
                    <img
                      alt="gameplay1"
                      src="../../assets/landing-page/gameplay1.png"
                      style="max-height: 456px; margin: auto; padding: 20px"
                    />
                  </div>
                  <div class="col-12">
                    <div style="padding: 10%">
                      <span
                        class="
                          imposter
                          xs:text-sm
                          md:text-sm
                          lg:text-lg
                          xl:text-xl
                          2xl:text-xl
                          text-white
                          desc-line
                        "
                      >
                        Use your NFTs Tools to gather the resources such as
                        stones, woods, fibers and ores for crafting other tools
                        and equipments.
                      </span>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="section" style="position: relative">
          <div class="section-seven"></div>
          <div class="content desktop">
            <div class="grid grid-cols-1 justify-between">
              <div class="container text-uppercase">
                <div class="row">
                  <div class="col-6">
                    <img
                      alt="gameplay1"
                      src="../../assets/landing-page/equipment.png"
                      style="max-height: 456px; margin: auto; padding: 20px"
                    />
                  </div>
                  <div class="col-6">
                    <div style="padding: 20%">
                      <span
                        class="
                          imposter
                          xs:text-sm
                          md:text-sm
                          lg:text-lg
                          xl:text-xl
                          2xl:text-xl
                          text-white
                          desc-line
                        "
                      >
                        We convince players to use materials from gathering and
                        PVE systems to craft NFTs tradable tools or equipment
                        that will make players stronger in competitive zone.
                      </span>
                    </div>
                  </div>
                </div>
                <div class="row">
                  <div class="col-6">
                    <div style="padding: 20%">
                      <span
                        class="
                          imposter
                          xs:text-sm
                          md:text-sm
                          lg:text-lg
                          xl:text-xl
                          2xl:text-xl
                          text-white
                          desc-line
                        "
                      >
                        In peta land other player can be friendly or enemies. So
                        you need to prepare yourself.
                      </span>
                      <span
                        class="
                          imposter
                          xs:text-sm
                          md:text-sm
                          lg:text-lg
                          xl:text-xl
                          2xl:text-xl
                          text-white
                          desc-line
                        "
                      >
                        The Red zone can PVP but items not drop when you died.
                        The Black zone items will drop when you died.
                      </span>
                    </div>
                  </div>
                  <div class="col-6">
                    <img
                      alt="gameplay2"
                      src="../../assets/landing-page/pvp.png"
                      style="max-height: 456px; margin: auto; padding: 20px"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="content mobile">
            <div class="grid grid-cols-1 justify-between">
              <div class="container text-uppercase">
                <div class="row">
                  <div class="col-12">
                    <img
                      alt="gameplay2"
                      src="../../assets/landing-page/pvp.png"
                      style="max-height: 456px; margin: auto; padding: 20px"
                    />
                  </div>
                  <div class="col-12">
                    <span
                      class="
                        imposter
                        xs:text-sm
                        md:text-sm
                        lg:text-lg
                        xl:text-xl
                        2xl:text-xl
                        text-white
                        desc-line
                      "
                    >
                      We convince players to use materials from gathering and
                      PVE systems to craft NFTs tradable tools or equipment that
                      will make players stronger in competitive zone. In peta
                      land other player can be friendly or enemies. So you need
                      to prepare yourself.
                    </span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="section" style="position: relative">
          <div class="section-four"></div>
          <div class="content desktop">
            <div class="grid grid-cols-1 justify-between">
              <div class="container text-uppercase">
                <div class="row">
                  <div class="col-6">
                    <div style="padding: 25%">
                      <span
                        class="
                          imposter
                          xs:text-md
                          md:text-lg
                          lg:text-xl
                          xl:text-xl
                          2xl:text-xl
                          text-white
                          desc-line
                        "
                      >
                        Equipments in Petaland are NFTs therefore each of them
                        are unique. After an equipment has been crafted, primary
                        and secondary status of it will be randomized but the
                        skill will be generated, depending on name of equipment.
                      </span>
                    </div>
                  </div>
                  <div class="col-6">
                    <img
                      alt="nft"
                      src="../../assets/landing-page/nfts.png"
                      style="max-height: 969px; margin-left: auto; opacity: 1"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="content mobile">
            <div class="grid grid-cols-1 justify-between">
              <div class="container text-uppercase">
                <div class="row">
                  <div class="col-12">
                    <img
                      alt="nft"
                      src="../../assets/landing-page/nfts.png"
                      style="max-height: 969px; margin-left: auto; opacity: 1"
                    />
                  </div>
                  <div class="col-12">
                    <span
                      class="
                        imposter
                        xs:text-md
                        md:text-lg
                        lg:text-xl
                        xl:text-xl
                        2xl:text-xl
                        text-white
                        desc-line
                      "
                    >
                      Equipments in Petaland are NFTs therefore each of them are
                      unique. After an equipment has been crafted, primary and
                      secondary status of it will be randomized but the skill
                      will be generated, depending on name of equipment.
                    </span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="section" style="position: relative">
          <div class="section-five"></div>
          <div class="content desktop">
            <div class="row">
              <div class="col-12">
                <img
                  style="width: 500px; margin: auto"
                  alt="logo"
                  src="../../assets/landing-page/Treasure.png"
                />
              </div>
            </div>
            <div class="row">
              <div class="col-4"></div>
              <div class="col-4 text-center">
                <span
                  class="
                    imposter
                    xs:text-md
                    md:text-lg
                    lg:text-xl
                    xl:text-xl
                    2xl:text-xl
                    text-white
                    desc-line
                  "
                >
                  Follow our community AIRDROP is COMING
                </span>
              </div>
              <div class="col-4"></div>
            </div>
            <div class="row mt-5">
              <div class="col-4"></div>
              <div class="col-4 text-center">
                <i class="pi pi-discord mr-2" style="font-size: 3rem; color: #fff;"></i>
                <i class="pi pi-telegram mr-2" style="font-size: 3rem; color: #fff;"></i>
                <i class="pi pi-twitter mr-2" style="font-size: 3rem; color: #fff;"></i>
                <i class="pi pi-youtube mr-2" style="font-size: 3rem; color: #fff;"></i>
                <i class="pi pi-facebook mr-2" style="font-size: 3rem; color: #fff;"></i>
              </div>
              <div class="col-4"></div>
            </div>
          </div>
          <div class="content mobile">
            <div class="row">
              <div class="col-12">
                <img
                  style="width: 500px; margin: auto"
                  alt="logo"
                  src="../../assets/landing-page/Treasure.png"
                />
              </div>
            </div>
            <div class="row">
              <div class="col-12 text-center">
                <span
                  class="
                    imposter
                    xs:text-md
                    md:text-lg
                    lg:text-xl
                    xl:text-xl
                    2xl:text-xl
                    text-white
                    desc-line
                  "
                >
                  Follow our community AIRDROP is COMING
                </span>
              </div>
            </div>
            <div class="row mt-5">
              <div class="col-12 text-center">
                <i class="pi pi-discord mr-2" style="font-size: 3rem; color: #fff;"></i>
                <i class="pi pi-telegram mr-2" style="font-size: 3rem; color: #fff;"></i>
                <i class="pi pi-twitter mr-2" style="font-size: 3rem; color: #fff;"></i>
                <i class="pi pi-youtube mr-2" style="font-size: 3rem; color: #fff;"></i>
                <i class="pi pi-facebook mr-2" style="font-size: 3rem; color: #fff;"></i>
              </div>
            </div>
          </div>
        </div>
      </full-page>
    </div>
  </div>
</template>

<script>
import Web3 from "web3";
import ERC20 from "@/contracts/ERC20.json";
import GreetABI from "@/contracts/Greet.json";

export default {
  data() {
    return {
      address: "",
      greetingWord: "...",
      greetContractAddress: "".concat(
        process.env.VUE_APP_GREET_CONTRACT_ADDRESS.substring(0, 6),
        "...",
        process.env.VUE_APP_GREET_CONTRACT_ADDRESS.slice(-4)
      ),
      greetingContract: undefined,
      milkTokenContract: undefined,
      walletAccount: "",
      greetChangeWord: "",
      onApproving: false,
    };
  },
  created() {
    const ref = this.$route.query.ref;
    if (ref != undefined) {
      const encryptedText = decodeURIComponent(ref);
      const decryptedText = this.CryptoJS.AES.decrypt(
        encryptedText,
        "mzHfUfUyyuFK9kJwxr9Qv"
      ).toString(this.CryptoJS.enc.Utf8);
      localStorage.setItem("ref", decryptedText);
    }
  },
  async mounted() {
    // window.web3 = new Web3(window.ethereum);
    // if (typeof window.ethereum == "undefined") {
    //   window.web3.setProvider(
    //     new Web3.providers.HttpProvider(process.env.VUE_APP_RPC_URL)
    //   );
    // }
    // this.connectWallet().then(() => {
    //   // this.loadContract();
    //   this.loadGreetingWord();
    //   this.loadAccountBalance();
    // });
  },
  methods: {
    async connectWallet() {
      if (this.validated()) {
        this.switchNetwork();

        await window.ethereum.request({
          method: "eth_requestAccounts",
        });

        this.walletAccount = window.ethereum.selectedAddress;
      }
    },
    validated() {
      if (typeof window.ethereum !== "undefined") {
        return true;
      }
      return false;
    },
    async switchNetwork() {
      await window.ethereum.request({
        method: "wallet_addEthereumChain",
        params: [
          {
            chainId: process.env.VUE_APP_CHAIN_ID,
            chainName: process.env.VUE_APP_CHAIN_NAME,
            rpcUrls: [process.env.VUE_APP_RPC_URL],
            nativeCurrency: {
              name: process.env.VUE_APP_CURRENCY_NAME,
              symbol: process.env.VUE_APP_CURRENCY_SYMBOL,
              decimals: 18,
            },
            blockExplorerUrls: [process.env.VUE_APP_BLOCK_EXPLORER],
          },
        ],
      });
    },
    async loadContract() {
      window.web3 = new Web3(window.ethereum);
      if (typeof window.ethereum == "undefined") {
        window.web3.setProvider(
          new Web3.providers.HttpProvider(process.env.VUE_APP_RPC_URL)
        );
      }
      this.greetingContract = await new window.web3.eth.Contract(
        GreetABI.abi,
        process.env.VUE_APP_GREET_CONTRACT_ADDRESS
      );

      console.log(this.greetingContract);

      this.milkTokenContract = await new window.web3.eth.Contract(
        ERC20.abi,
        process.env.VUE_APP_MILK_CONTRACT_ADDRESS
      );
    },
    async loadGreetingWord() {
      this.loadContract().then(() => {
        this.greetingContract.methods
          .greet()
          .call()
          .then((res) => {
            console.log(res);
            this.greetingWord = res;
          });
      });
    },
    async loadAccountBalance() {
      this.loadContract().then(() => {
        this.milkTokenContract.methods
          .balanceOf(window.ethereum.selectedAddress)
          .call()
          .then((results) => {
            console.log(results);
            // this.greetingWord = results;
          });
      });
    },
    submitWord() {
      this.loadContract().then(() => {
        this.greetingContract.methods
          .setGreeting(this.greetChangeWord)
          .send({ from: this.walletAccount })
          .on("sent", (data) => this.sendGreeting(data))
          .on("transactionHash", (tx) => this.transactionHash(tx))
          .on("receipt", (data) => this.receiptGreeting(data))
          // .on("confirmation", (data) => this.confirmApprove(data))
          .on("error", (error) => {
            this.showToastError(error);
            this.onApproving = false;
          });
      });
    },
    sendGreeting(data) {
      console.log("send Change to Blockchain", data);
      this.onApproving = true;
    },
    transactionHash(transaction) {
      console.log("transaction", transaction);
    },
    receiptGreeting(data) {
      console.log("Greeting Changed", data);
      this.onApproving = false;
      this.loadGreetingWord(this.active);
    },
  },
};
</script>

<style scoped>
.swiper {
  height: 300px;
  width: 100%;
}
.swiper-slide {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  font-weight: bold;
}
.agile .dots {
  bottom: 10px;
  left: 50%;
  position: absolute;
  transform: translateX(-50%);
}
.header-section {
  margin: 1% 0px 5% 0px;
}

.title-header-section {
  font-size: 2.14285714em;
  color: #e0fb16;
}
.title-ecio {
  font-size: 4rem;
  font-weight: bold;
}
.m-logo {
  /* padding-top: 60px !important; */
  /* margin: 0px 0px 0px 0px !important; */
}
.bg--purple {
  background: #410b53;
  padding-bottom: 0;
}

.btn-approve {
  font-size: 1.2rem;
  padding: 20px;
  text-align: center;
  background-color: #4804d9;
  color: #fff;
  height: 40px;
  width: 150px;
  border-radius: 10px;
  text-transform: uppercase;
  font-family: "Quantico" !important;
}

.imposter {
  font-family: "Imposter" !important;
}

.bg--purple [data-overlay]:before {
  background: #410b53 !important;
}
.slider.roadmap {
  margin-bottom: 0;
}
.bg--team {
  background-image: linear-gradient(
    to top,
    #000000 100%,
    #120457 100%,
    #44124e 100%
  );
}
/deep/ .roadmap .flickity-page-dots {
  bottom: 50px !important;
}
/deep/ .roadmap .flickity-page-dots .dot {
  background: #ffffff !important;
}
.project-thumb:not(.hover-element) > a {
  margin-bottom: 0px;
}

@media (max-width: 767.98px) {
  /deep/ .roadmap .flickity-page-dots {
    bottom: 10px !important;
  }
  .videobg {
    height: 100vh !important;
  }
}
section,
footer {
  padding-top: 5em;
  padding-bottom: 5em;
}

/deep/ .flickity-page-dots .dot {
  width: 12px;
  height: 12px;
}

.carousel {
  background: #fafafa;
}

.carousel-cell {
  width: 66%;
  height: 200px;
  margin-right: 10px;
  background: #8c8;
  border-radius: 5px;
  counter-increment: carousel-cell;
}

/* cell number */
.carousel-cell:before {
  display: block;
  /* text-align: center; */
  content: counter(carousel-cell);
  line-height: 200px;
  font-size: 80px;
  color: white;
}

.button {
  font-size: 22px;
}

.button-group {
  margin-bottom: 20px;
}
.mauticform-page-1 {
  display: flex !important;
  justify-content: center;
}
.btn-ecio-partner {
  background: #e0fb16;
  color: #000000;
  border-radius: 5px;
  margin-left: 20px;
  white-space: nowrap;
  padding: 6px 12px;
  position: relative;
  font-weight: bold;
  width: 100%;
  display: flex;
  align-items: center;
  font-family: "Quantico";
  justify-content: center;
}
.mauticform-button.btn-default {
  border-radius: 5px;
  color: #000000 !important;
  font-family: "Quantico";
  font-size: 14px !important;
  font-weight: bold !important;
}
.break-space {
  white-space: break-spaces;
}
.mauticform-input {
  height: 100%;
  padding: 14px;
}

.container.partner {
  background: rgb(0 0 0 / 20%);
  padding: 30px;
}
.desktop {
  display: block;
}
.mobile {
  display: none;
}
.desktop-header {
  display: flex;
}
.max-marketplace-text {
  font-size: 4rem;
  color: #ffffff;
}
.blueunion {
  display: flex;
}

.section-one {
  background-image: url("../../assets/landing-page/bgbanner.png");
  background-repeat: no-repeat;
  background-position: top center;
  background-size: cover;
  height: 100%;
}

.section-two {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background-image: url("../../assets/landing-page/bg2.png");
  background-color: rgba(255, 255, 255, 0.5);
  background-repeat: no-repeat;
  background-position: top center;
  background-size: cover;
  opacity: 0.3;
  height: 100%;
}

.section-three {
  background-color: #fff;
  /* position: absolute; */
  height: 100%;
}

.section-four {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background-image: url("../../assets/landing-page/bg3.png");
  background-color: rgba(255, 255, 255, 0.5);
  background-repeat: no-repeat;
  background-position: top center;
  background-size: cover;
  opacity: 0.3;
  height: 100%;
}

.section-six {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background-image: url("../../assets/landing-page/bg5.png");
  background-color: rgba(255, 255, 255, 0.5);
  background-repeat: no-repeat;
  background-position: top center;
  background-size: cover;
  opacity: 0.3;
  height: 100%;
}

.section-seven {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background-image: url("../../assets/landing-page/bg6.jpg");
  background-color: rgba(255, 255, 255, 0.5);
  background-repeat: no-repeat;
  background-position: top center;
  background-size: cover;
  opacity: 0.3;
  height: 100%;
}

.content {
  position: relative;
  z-index: 1;
}

.section-five {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background-image: url("../../assets/landing-page/bg4.png");
  background-color: #000;
  background-repeat: no-repeat;
  background-position: top center;
  background-size: cover;
  /* position: absolute; */
  opacity: 0.4;
  height: 100%;
}
.desc-line {
  line-height: 30px;
}

.home-nft {
  position: absolute;
  right: 3%;
  z-index: 5;
  margin-top: 50px;
}

.section-img {
  max-height: 968px;
  margin: auto;
  height: 50%;
}

.section-img-mb {
  max-height: 968px;
  margin: auto;
  width: 80%;
  margin-top: 250px;
}

.p-galleria-thumbnail-items-container {
  height: 520px !important;
}

@media (max-width: 600px) {
  .container {
    max-width: 100%;
  }
}

@media (max-width: 767px) {
  .desktop {
    display: none;
  }
  .mobile {
    display: block;
  }
  .desktop-header {
    display: none;
  }
  .blueunion {
    display: none;
  }
}

@media (max-width: 1100px) {
  .max-marketplace-text {
    font-size: 3.5rem;
    color: #ffffff;
  }
}

@media (max-width: 1000px) {
  .max-marketplace-text {
    font-size: 3rem;
    color: #ffffff;
  }
}

@media (max-width: 1600px) {
  .home-nft {
    margin-top: -25px;
  }
}
</style>
