# YManga - The Ultimate Manga Reading Experience

![Banner](https://github.com/Mdyeasinkhan4/y_manga_app/blob/fcb058d945a2cdb96de6e7076b08f8f276b41243/assets/images/app_logo.jpg?raw=1)

YManga is a modern, fast, and feature-rich manga reader application built with **Flutter**. It follows **Clean Architecture** principles and leverages the power of **Riverpod** for state management and **Drift (SQLite)** for a robust local database experience.

## ✨ Key Features

- **🚀 Multiple Sources:** Integrated with 7 popular manga & comic sources: **MangaDex**, **Asura Scans**, **MangaFreak**, **MangaPill**, **MangaRead**, **Batoto (xBato)**, and **Read Free Comics (DC/Marvel)**.
- **⚡ Concurrent Multi-Source Search:** Search all 7 sources simultaneously in under ~1.5s with debounced auto-search and infinite scrolling.
- **📖 Advanced Reader:** Supports both **Paged (Horizontal LTR/RTL)** and **Webtoon (Vertical)** reading modes with seamless auto-next chapter transitions.
- **📚 Personal Library:** Organize your manga into "Reading", "Completed", and "Downloaded" categories.
- **🕒 Reading History:** Never lose track of where you left off. Smart progress tracking across all chapters.
- **📥 Download Manager:** Download your favorite chapters for **Offline Reading**. Full control over your storage.
- **🌓 Dynamic Theming:** Beautiful Light and Dark mode support.
- **⚡ Performance:** Optimized for low-end devices with split APK builds.

---

## 📸 App Previews

<table style="width:100%">
  <tr>
    <td align="center"><b>Splash Screen</b></td>
    <td align="center"><b>Home Screen</b></td>
    <td align="center"><b>Manga Details</b></td>
  </tr>
  <tr>
    <td><img src="https://github.com/Mdyeasinkhan4/y_manga_app/blob/a8cdec160fabc9597157b4bca44a0e6e5c23a1a4/preview_image/01.splash_sc.png?raw=1" width="250"></td>
    <td><img src="https://github.com/Mdyeasinkhan4/y_manga_app/blob/a8cdec160fabc9597157b4bca44a0e6e5c23a1a4/preview_image/02.home_sc.png?raw=1" width="250"></td>
    <td><img src="https://github.com/Mdyeasinkhan4/y_manga_app/blob/a8cdec160fabc9597157b4bca44a0e6e5c23a1a4/preview_image/03.manga_detail_sc.png?raw=1" width="250"></td>
  </tr>
  <tr>
    <td align="center"><b>Reader Mode</b></td>
    <td align="center"><b>Chapter List</b></td>
    <td align="center"><b>Smart Search</b></td>
  </tr>
  <tr>
    <td><img src="https://github.com/Mdyeasinkhan4/y_manga_app/blob/a8cdec160fabc9597157b4bca44a0e6e5c23a1a4/preview_image/04.manga_read_sc.png?raw=1" width="250"></td>
    <td><img src="https://github.com/Mdyeasinkhan4/y_manga_app/blob/a8cdec160fabc9597157b4bca44a0e6e5c23a1a4/preview_image/05.manga_episodes_sc.png?raw=1" width="250"></td>
    <td><img src="https://github.com/Mdyeasinkhan4/y_manga_app/blob/a8cdec160fabc9597157b4bca44a0e6e5c23a1a4/preview_image/06.manga_search_sc.png?raw=1" width="250"></td>
  </tr>
  <tr>
    <td align="center"><b>My Library</b></td>
    <td align="center"><b>Reading History</b></td>
    <td align="center"><b>Download Queue</b></td>
  </tr>
  <tr>
    <td><img src="https://github.com/Mdyeasinkhan4/y_manga_app/blob/a8cdec160fabc9597157b4bca44a0e6e5c23a1a4/preview_image/07.manga_library_sc.png?raw=1" width="250"></td>
    <td><img src="https://github.com/Mdyeasinkhan4/y_manga_app/blob/a8cdec160fabc9597157b4bca44a0e6e5c23a1a4/preview_image/08.manga_history_sc.png?raw=1" width="250"></td>
    <td><img src="https://github.com/Mdyeasinkhan4/y_manga_app/blob/a8cdec160fabc9597157b4bca44a0e6e5c23a1a4/preview_image/09.download_sc.png?raw=1" width="250"></td>
  </tr>
  <tr>
    <td align="center"><b>Read Offline</b></td>
    <td align="center"><b>Offline Experience</b></td>
    <td align="center"><b>Dark Theme</b></td>
  </tr>
  <tr>
    <td><img src="https://github.com/Mdyeasinkhan4/y_manga_app/blob/a8cdec160fabc9597157b4bca44a0e6e5c23a1a4/preview_image/10.read_from_downloaded_section_sc.png?raw=1" width="250"></td>
    <td><img src="https://github.com/Mdyeasinkhan4/y_manga_app/blob/a8cdec160fabc9597157b4bca44a0e6e5c23a1a4/preview_image/11.readDownloadedChapterOffline_sc.png?raw=1" width="250"></td>
    <td><img src="https://github.com/Mdyeasinkhan4/y_manga_app/blob/061657e90f65aa571a9e546cbe10646e0717e4be/preview_image/12.darkTheme_sc.png?raw=1" width="250"></td>
  </tr>
</table>

---

## 🛠️ Technical Stack

- **Framework:** Flutter (Latest Stable)
- **Architecture:** Clean Architecture (Data, Domain, Presentation)
- **State Management:** Riverpod Generator & Providers
- **Database:** Drift (SQLite) for high-performance persistence
- **Networking:** Dio with custom interceptors
- **Navigation:** GoRouter
- **Image Caching:** CachedNetworkImage

---

## 🤝 Contribution

Contributions are always welcome! Feel free to open an issue or submit a pull request.

Developed with ❤️ by **Md. Yeasin Khan**
