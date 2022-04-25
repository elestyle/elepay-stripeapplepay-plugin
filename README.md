# elepay-StripeApplePay-Plugin

## 日本語

elepay StripeApplePay Plugin for iOS は App Clips を開発する際に、アプリのサイズを小さくするための軽量化した SDK です。  
具体的な導入ガイドは以下の URLでご確認ください。  
[→ elepay iOS SDK 導入ガイド (App Clips)](https://developer.elepay.io/docs/app-clips)  

該当 SDK は必ず [elepay iOS SDK](https://github.com/elestyle/elepay-ios-sdk) と一緒に利用しないといけませんので、ご注意ください。  

## システム要件

* iOS 11.0 以上、Xcode 12.5.1 以上  
* StripeApplePay SDK は内蔵済みのため、Stripe SDK や StripeAppleSDK のインポートが不要です  
* App Clip の target に既に Stripe SDK をインポートしている場合は、こちらの plugin が機能的に重複になるため、同時にご利用しないてください  

## elepay StripeApplePay Plugin for iOS 履歴

* v0.1.0: 最初のリリース。 StripeApplePaySDK v21.13.0 が内蔵しています  

## English

The elepay StripeApplePay Plugin for iOS provides a lightweight plugin for offering Apple Pay in an App Clip.  
You can now remove Stripe SDK when making App Clips to reduce the binary size.  

 For more details, please access the link below.  
[→ Import Guide for elepay iOS SDK (App Clips)](https://developer.elepay.io/docs/app-clips)

**NOTE:** This SDK dose NOT work by itself. You should always install this SDK with [elepay iOS SDK](https://github.com/elestyle/elepay-ios-sdk).

## System Requirement

* iOS 11.0 and above, Xcode 12.5.1 and above  
* The `Elepay-StripeApplePay-Plugin` already has StripeApplePay SDK embedded, so you need to import only `ElepaySDK` and `Elepay-StripeApplePay-Plugin` when buiding your App Clip.  
* Do not import Stripe SDK or StripeApplePaySDK in the same App Clip target with this plugin.  

## elepay SDK Chinese Payments Plugin Update History

* v0.1.0: The first release. Has StripeApplePaySDK v21.13.0 embedded.
