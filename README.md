
# SolanaKotlinComposeScaffold

A boilerplate example app for Solana Mobile dApps built using Jetpack Compose.
It provides an interface to connect to locally installed wallet apps (that are MWA-compatible), view your account balance on devnet, and request an airdrop of SOL.

## Featured Libarires

- [Mobile Wallet Adapter (`clientlib-ktx`)](https://github.com/solana-mobile/mobile-wallet-adapter/tree/main/js/packages/mobile-wallet-adapter-protocol) for connecting to wallets and signing transactions/messages
- [web3-solana](https://github.com/solana-mobile/web3-core) for Solana primitive types (`SolanaPublicKey`) and constructing messages/transactions.
- [rpc-core](https://github.com/solana-mobile/rpc-core) for constructing and sending [Solana RPC requests](https://docs.solana.com/api/http).

<table>
  <tr>
    <td align="center">
      <img src="/screenshots/screenshot1.png" alt="Scaffold dApp Screenshot 1" width=300 />
    </td>
    <td align="center">
      <img src="/screenshots/screenshot2.png" alt="Scaffold dApp Screenshot 2" width=300 />
    </td>
    <td align="center">
      <img src="/screenshots/screenshot3.png" alt="Scaffold dApp Screenshot 3" width=300 />
    </td>
  </tr>
</table>

## Prerequisites

You'll need to first setup your environment for Android development. Follow the [Prerequisite Setup Guide](https://docs.solanamobile.com/getting-started/development-setup).

Follow the guide to make sure you:

- setup your Android and React Native development environment.
- have an Android device or emulator.
- install an MWA compliant wallet app on your device/emulator.

## Usage

1. Initialize project template

```bash
git clone https://github.com/solana-mobile/solana-kotlin-compose-scaffold.git
```

2. Open the project on Android Studio > Open > "SolanaKotlinComposeScaffold/app/build.gradle.kts"

3. Start your emulator/device and build the app

## Troubleshooting

- `Compatible wallet not found.`
  - Make sure you install a compatible MWA wallet on your device, like Phantom, Solflare, Ultimate, or `fakewallet`. Follow
    the [setup guide](https://docs.solanamobile.com/getting-started/development-setup).
That sounds like an innovative project! Here's a step-by-step guide on how to achieve this:

### 1. **Create Advanced AI Filters**

You need to develop AI filters first. Tools and platforms to create such filters include:

- **Spark AR**: For Facebook and Instagram.
- **Lens Studio**: For Snapchat.

These platforms provide a robust set of tools for developing advanced AR filters.

### 2. **Integrate AI Models**

To make your filters more advanced, you can integrate machine learning models using libraries like TensorFlow.js or MediaPipe. You might need to export your models and integrate them into the AR platforms.

### 3. **Minting Filters as NFTs**

For minting your filters as NFTs on the blockchain, you can use platforms like OKX. Here's a general process:

#### a. **Prepare Your Digital Assets**

Export your filters and related files in a format that can be minted. Common formats include images, videos, or 3D models.

#### b. **Select an NFT Marketplace**

Choose an NFT marketplace that supports the OKX blockchain, such as OKX NFT Marketplace. Register and create a wallet if you don't already have one.

#### c. **Minting Process**

1. **Upload your Filter Assets**: Upload the assets you prepared.
2. **Metadata**: Provide metadata for your NFT. This includes the name, description, and any attributes of your filter.
3. **Mint**: Mint the NFT by following the platform’s process, which typically involves signing a transaction with your wallet.

### 4. **Deploy and Distribute Filters**

Once minted, distribute your filters across the platforms (Facebook, Instagram, Snapchat). You can share the filter links and NFT ownership details on these platforms to attract users.

### 5. **Start Free, Then Monetize**

Initially, offer your filters for free to build a user base. Once you gain traction, start charging for premium filters. Use the NFT smart contracts to manage ownership and royalties.

### Platform and Tools Summary

- **AR Filter Creation**: Spark AR (Instagram, Facebook), Lens Studio (Snapchat)
- **AI Integration**: TensorFlow.js, MediaPipe
- **Blockchain & NFT**: OKX NFT Marketplace

### Resources

1. **[Spark AR](https://sparkar.facebook.com/ar-studio/)**
2. **[Lens Studio](https://lensstudio.snapchat.com/)**
3. **[TensorFlow.js](https://www.tensorflow.org/js)**
4. **[MediaPipe](https://mediapipe.dev/)**
5. **[OKX NFT Marketplace](https://www.okx.com/nft)**
  
Using these platforms, you can create and mint your AI-powered filters as NFTs, then distribute them through popular social media apps.

Feel free to reach out if you have specific questions about any of these steps!
