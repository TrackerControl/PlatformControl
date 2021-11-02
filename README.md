# PlatformControl: Privacy Analysis of iOS and Android Apps at Scale
Download and analyse the privacy properties of Android and iOS apps at scale.

This project has multiple parts:

1. <https://github.com/OxfordHCC/xray-archiver-android-ios> - To explore what iOS and Android apps are on the app stores, and also for the download of Android apps, as well as a high level analysis of iOS and Android apps.
2. <https://github.com/OxfordHCC/platformcontrol-ios-downloader> - To download iOS apps at scale from the App Store.
3. <https://github.com/OxfordHCC/platformcontrol-analysis> - For the analysis of tracking libraries and contacted tracking domains, for both iOS and Android

## Data Access

If you're interested in getting access to the data that we used for our study, please get in touch with us directly.

We're currently in the process of making our data available.

We've already published:
- our dataset of iOS tracker libraries: <https://github.com/OxfordHCC/platformcontrol-analysis/blob/main/data/ios_signatures.json>
- our database of tracking domains, and the networks of companies and the jurisdictions behind: https://github.com/OxfordHCC/tracker-control-android/blob/master/app/src/main/assets/xray-blacklist.json

## Citation

If you use this project as part of your academic studies, please kindly cite the below article:

```
@article{kollnig2021,
      title={Are iPhones Really Better for Privacy? A Comparative Study of iOS and Android Apps}, 
      author={Konrad Kollnig and Anastasia Shuba and Reuben Binns and Max {Van Kleek} and Nigel Shadbolt},
      year={2021},
      journal={arXiv preprint arXiv:2109.13722}
}
```
