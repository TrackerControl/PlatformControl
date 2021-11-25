# PlatformControl

**Download and privacy analysis of iOS and Android apps at scale**

This project has multiple parts:

1. <https://github.com/OxfordHCC/xray-archiver-android-ios> - To explore what iOS and Android apps are on the app stores, and also for the download of Android apps, as well as a high level analysis of iOS and Android apps (permissions, mainly).
2. <https://github.com/OxfordHCC/platformcontrol-token-dispenser> - Required for the downloading of Android apps at scale.
3. <https://github.com/OxfordHCC/platformcontrol-ios-downloader> - To download iOS apps at scale from the App Store.
4. <https://github.com/OxfordHCC/platformcontrol-android-ios-analysis> - For the analysis of tracking libraries and contacted tracking domains, for both iOS and Android
5. <https://github.com/OxfordHCC/JustTrustMe> - To disable certificate pinning in Android apps

## Data Access

If you're interested in getting access to the data that we used for our study, please get in touch with us directly.

We're currently in the process of making our data available.

We've already published:
- our dataset of iOS tracker libraries: <https://github.com/OxfordHCC/platformcontrol-analysis/blob/main/data/ios_signatures.json>
- our database of tracking domains, and the networks of companies and the jurisdictions behind: https://github.com/OxfordHCC/tracker-control-android/blob/master/app/src/main/assets/xray-blacklist.json

## Ready-to-use analysis with TrackerControl

As a sub project of PlatformControl, TrackerControl is an indepedent and somewhat popular Android app to privacy analysis and control. It contains some of the core analysis functionality of PlatformControl (though by far not all of it), conducting both network traffic and tracker library analysis.

You can find TrackerControl at <https://github.com/OxfordHCC/tracker-control-android>.

## Citation

If you use this project as part of your academic studies, please kindly cite the below articles:

```
@article{kollnig2021_iphone_android,
      title={Are iPhones Really Better for Privacy? A Comparative Study of iOS and Android Apps}, 
      author={Konrad Kollnig and Anastasia Shuba and Reuben Binns and Max {Van Kleek} and Nigel Shadbolt},
      year={2021},
      journal={arXiv preprint arXiv:2109.13722}
}

@inproceedings {kollnig2021_consent,
      author = {Konrad Kollnig and Pierre Dewitte and Max Van Kleek and Ge Wang and Daniel Omeiza and Helena Webb and Nigel Shadbolt},
      title = {A Fait Accompli? An Empirical Study into the Absence of Consent to Third-Party Tracking in Android Apps},
      booktitle = {Seventeenth Symposium on Usable Privacy and Security ({SOUPS} 2021)},
      year = {2021},
      isbn = {978-1-939133-25-0},
      pages = {181--196},
      url = {https://www.usenix.org/conference/soups2021/presentation/kollnig},
      publisher = {{USENIX Association}},
      month = aug,
}
```
