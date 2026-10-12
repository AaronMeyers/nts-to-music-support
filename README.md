# NTS to Music

An independent iPhone and iPad utility that adds tracks shared from NTS to a chosen Apple Music playlist.

## Support

Contact [me@aaron-meyers.com](mailto:me@aaron-meyers.com) for help. Include your iOS version, the artist/title you shared, and the error you saw. Please do not send passwords or Apple account credentials.

### Getting started

1. Open NTS to Music and allow Apple Music access.
2. Choose an existing editable playlist. An Apple Music subscription with Sync Library enabled is required.
3. Share a track from NTS and choose **Add to Apple Music**. Enable the action under **More** in the share sheet if necessary.

High-confidence matches are added automatically. Uncertain recordings show a candidate picker inside the extension. Failed searches are saved under **Unmatched tracks** for later reference. The app does not play or download audio.

### Common questions

- **Playlist missing:** Check Apple Music authorization and Sync Library, then refresh the playlist picker. Only editable playlists can be selected.
- **Previously added:** The app remembers its own confirmed additions. Choose **Add again** if you removed that track externally and want to restore it. Tracks added outside this app may be duplicated.
- **No match:** Catalogue availability varies by region. Copy the artist/title from Unmatched tracks to investigate elsewhere.
- **Network or interrupted addition:** Check the playlist before retrying an uncertain write. The app retains a pending record and checks uncertain outcomes before another write.

## Privacy policy

Effective October 11, 2026.

### Developer data collection

NTS to Music has no developer-operated backend, advertising, analytics SDK, or tracking. The developer does not receive your shared tracks, Apple Music library, or playlist contents through the app.

### Apple Music access

With your permission, the app uses Apple's MusicKit framework and Apple Music APIs to check subscription/library capabilities, retrieve editable playlists, search the catalogue, and add the selected recording to your chosen playlist. These requests send the information needed for those operations, including search terms and song/playlist identifiers, directly to Apple. Apple's handling of its services is governed by [Apple's privacy policy](https://www.apple.com/legal/privacy/).

The app does not ask for or store your Apple account password. It does not play, copy, or download audio. Catalogue searches are initiated when you share a track.

### Information stored on your device

The app and its share extension share local storage for your destination playlist, its artwork URL, matching preferences, confirmed-addition history, unresolved addition records, unmatched searches, and workflow reports. Reports may include shared artist/title text, candidate metadata, errors, and elapsed timings. Detailed share-payload capture is disabled in the distributed Release build. None of these reports is automatically sent to the developer.

Apple Music playlist artwork is loaded from artwork URLs supplied by Apple. Local app data may be included in device backups according to your device settings and Apple's backup services.

### Your controls

You can change the destination playlist and matching preferences in the app, copy or delete entries in Unmatched tracks, and revoke Apple Music permission in iOS Settings. Clipboard copying happens only when you tap **Copy artist and title**; the app does not silently read the clipboard. Removing the app removes its local app storage; it does not remove songs already added to Apple Music playlists. You can remove those tracks using Apple Music.

If you email support, the developer receives the email and information you choose to include and uses it to respond to your request. Do not include sensitive information that is unnecessary for support.

### Contact and changes

Privacy questions: [me@aaron-meyers.com](mailto:me@aaron-meyers.com). Changes to this policy will be published here with an updated effective date.

NTS to Music is not affiliated with or endorsed by NTS or Apple. Apple and Apple Music are trademarks of Apple Inc., registered in the U.S. and other countries.
