# Google Pixel Setup

This guide was written for the Pixel 11 series on Android 17. It should also apply generally to earlier Pixels on Android 17.

## First Boot

1. At the "Hi there" screen, tap **Next**, then choose your language.
2. At "Set up using another device," tap **Skip**, then **Skip** again at the confirmation.
3. At "Connect to Wi-Fi," tap **Skip**.
4. At "Connect to mobile network," tap **Set up offline**, then **Continue** at the confirmation.
5. PIN is optional. I would recommend setting one up now, or you may tap **Skip**.
   - If you set a PIN, you can optionally set up Fingerprint Unlock, or tap **No thanks**.
   - If you set a PIN, you can optionally set up Face Unlock, or tap **No thanks**.
6. At the "Google services" screen, toggle off **Use location** and **Send usage and diagnostic data**, then scroll down and tap **Accept**.
7. At the "Limited warranty" screen, tap **Next**.
8. At "Additional legal terms," tap **I accept**.
9. At "Get peace of mind," tap **Next**.
10. At "Learn how to navigate your phone," tap **Skip**.
11. At "Meet your new Pixel," tap **Choose how to navigate**, select **3-button navigation**, then tap the **Home** button.

You will now be at your home screen. There will be a few first-time notifications. Tap **Clear all** to dismiss them, then swipe away the "Finish setting up your device" persistent notification.

## Settings

Swipe down from the top of the screen twice and tap the gear icon to open **Settings**.

Tap the **Finish setting up** option at the top. Google will be insufferable about asking you to sign in and connect (this is all stuff we already skipped during first boot). At "Finish Pixel setup," tap **Start**, **Skip**, **Skip**, **Skip**, **Set up offline**, **Continue**. At "What next?" tap **Maybe later**. The persistent setup prompt will now disappear.

### Security & Privacy

1. Scroll down and tap **Security & privacy**.
2. You may dismiss the "Add Google Account" alert for now (tap the **X** at the top right), then **Dismiss** to confirm. We will do that later.

#### Device unlock

1. Within "Security & privacy," tap **Device unlock**.
2. Tap **Screen lock** and enter your PIN.
3. Toggle **Enhanced PIN privacy** to **On**.

#### Lost device protection

1. Within "Security & privacy," tap **Lost device protection**.
2. Tap **Theft protection** and toggle on both **Theft Detection Lock** and **Offline Device Lock** and "Ok" to confirm each.

#### Privacy controls

1. Within "Security & privacy," tap **Privacy controls**.
2. Under "Ads," tap **Delete advertising ID**. Tap **Delete advertising ID** again to confirm.

#### Advanced Protection
1. Within "Security & privacy," tap **Advanced Protection**.
2. Toggle **Device protection** to **On**, then tap **Turn on** to confirm. This will enable a variety of settings in one step to help strengthen your device security (inactivity reboot, USB protection, 2G disabled, spam filtering, etc.).

#### More security & privacy

1. Within "Security & privacy," tap **More security & privacy**.
2. Toggle **Personalize using app data** to **Off**.
3. Tap **Android System Intelligence**, then toggle off **Customize the experience using your Google Account data**.
4. Tap **App pinning**, then toggle **Use app pinning** to **On**, then **OK** to confirm.

### Passwords & passkeys

1. Back in Settings, tap **Passwords & passkeys**.
2. The default preferred service will be "Google." Tap the pencil icon next to Google, then set **Preferred service** to **None**. Tap **Turn off** to confirm.

### Network & internet

1. Back in Settings, tap **Network & internet**.
2. Tap **Private DNS**, change the setting to **Private DNS provider hostname**, enter `dns.quad9.net`, then tap **Save**.
3. Tap **Adaptive connectivity**, toggle **Auto-switch to mobile network** and **Optimize network for battery life** both to **Off**.

### Notifications

1. Back in Settings, tap **Notifications**.
2. Tap **Notification history**, then toggle **Use notification history** to **On**.
3. Tap **Bubbles**, then toggle **Allow apps to show bubbles** to **Off**.
4. Tap **Notifications on lock screen**, then toggle **Show sensitive content** to **Off**.

### Display & touch

1. Back in Settings, tap **Display & touch**.
2. Tap **Lock screen**, then **Notifications on lock screen**. Toggle **Show sensitive content** to **Off**.

> **Note:** The "Show sensitive content" toggle appears in both the Notifications and Display settings. They do not sync with each other, so make sure to turn it off in both places.

### System

1. Back in Settings, tap **System**.
2. Tap **Language & region**, then **Speech**, then **Text-to-speech output**.
3. Tap the settings gear next to **Preferred engine**.
4. Toggle **Anonymous usage reports** to **Off**.
5. Go back to **System**.
6. Under "Keyboard," tap **Keyboard apps**, then tap **Gboard**.
7. In Gboard settings, tap **Corrections & suggestions**, then toggle **Don't suggest offensive words** to **Off**.
8. In Gboard settings, tap **Privacy**, then toggle **Share usage statistics**, **Personalize for you**, and **Improve for everyone** all to **Off**.
9. Back in "Keyboard apps," tap **Google Voice Typing** to open its settings (not the toggle). Toggle **Block offensive words** to **Off**.
10. Back in **System**, tap **Gestures**, then **Press & hold power button**. Change it to **Power menu**.

## Connect to Wi-Fi

1. Back in Settings, tap **Network & internet**, then **Internet**.
2. Scroll down and tap **Network preferences**. Toggle **Notify for public networks** to **Off**.
3. Tap back to return to your list of Wi-Fi networks.
4. "Use Wi-Fi" should already be toggled on and a list of networks will appear. Tap your home Wi-Fi network.
5. Before connecting, tap **Advanced**, then under **Privacy**, change the setting to **Use device MAC**.
6. Enter your Wi-Fi password and tap **Connect**.

> **Note:** Using your device MAC on your home network allows for consistent identification (useful for static IPs, MAC filtering, etc.). The default randomized MAC is better for public networks where you don't want to be tracked.

## System Update

1. Open **Settings**. New notifications (such as "Get your Pixel ready") may appear at the top -- dismiss each by tapping the **X**.
2. Scroll down and tap **System**, then **Software updates**.
3. Tap **System update**, then **Check for update**. If a new update is available, install and reboot. If "Your system is up to date," proceed to add your Google account.

## Add your Google Account

1. Back in Settings, tap **Google services**.
2. Under "Recommended," there will be a "Sign in" tile. Tap the **Sign in** button.
3. Enter your PIN or password to verify your identity.
4. At the "Sign in" screen, sign in as normal. Enter your Google username, then your password, and security key (if applicable).
5. Tap **I agree** to agree to the terms of service. You may tap **Cancel** to add additional recovery options.
6. At "Google services: Back up your device," select **Don't back up**, then **Confirm**.

Now that you are signed in, additional tiles and options will appear. Tap **All services**.

7. Under "Autofill & passwords," tap **Phone number sharing** and toggle it to **Off**.

## Main Screen

1. On your home screen, it will say "Explore your Pixel" with the subheading "Learn the basics and find new features." Long-press it and tap **Dismiss**. It will now display today's date instead.
2. Pull down your notifications and swipe away any lingering first-setup notifications.

## Update Google Play Services

1. In **Settings**, tap **System**, then **Software updates**.
2. Tap **Google Play system update** (right under "System update"). It will automatically check for updates.
3. If an update is available, tap **Download & install**. Once the update completes, tap "Restart now".

## Add your SIM

1. In **Settings**, tap **Network & internet**, then **SIMs**.
2. If this is a brand new line, tap **Set up eSIM**. If you are moving an eSIM, tap **Transfer a SIM from another device**.
3. Follow the directions to get the SIM set up or transferred.

> **Note:** For transfers, if you have "SIM Protection" enabled on your carrier account you will need to turn it off first.

## Convenience (Optional)

1. In **Settings**, tap **Location** and toggle **Use location** to **On**.
2. In **Settings**, tap **Security & privacy**, then **Device unlock**.
3. Tap **Fingerprint Unlock** and follow the prompts to enroll a fingerprint.

> **Note:** If you have a screen protector applied, scan the QR code on the screen protector packaging to let the phone calibrate for it (Pixel 10 or later) and start the fingerprint enrollment.

## App Updates

1. Open the **Google Play Store** app.
2. It will ask you to choose **Use password** or **Use biometrics**. Select your preference.
3. Tap your profile icon in the top right, then tap **Manage apps & device**.
4. Under "Updates available," tap **Update all**. Wait for all apps to finish updating.

## App Settings

When opening apps for the first time (such as Camera or the Play Store), you may be prompted to enable optional features, sign up for newsletters, or grant permissions. Decline anything that isn't necessary for the app to function.

### Google Messages

1. Open the **Messages** app.
2. Tap **Show name and picture to** and select **No one**, then continue.
3. Tap your picture in the top right corner, then tap your profile, then tap **Use this app without an account** to sign out of Messages. Tap **Sign out** to confirm.
4. Tap the empty person icon in the top right corner (be careful not to tap your account at the top or it will auto sign-in again). Tap **Messages settings**.
5. Tap **Gemini in Messages**, then toggle **Show Gemini button** to **Off**.
6. Tap **Advanced**, then toggle **Get SMS delivery reports** to **On**.

### Phone

1. Open the **Phone** app.
2. Tap the hamburger menu (top left), then **Settings**.
3. Under "Call Assist," tap **Hold for Me** and toggle it to **On**.
4. Tap **Direct My Call** and toggle it to **On**.
5. Tap **Call Screen** and confirm that **Medium protection (recommended)** is turned on, along with **Save Call Screen audio**.
6. Tap **Call Notes** and download the model.

### Google Chrome

1. Open **Chrome**. Tap **Stay signed out**, then **No thanks** to notifications.
2. The new tab page will be busy. Tap the three-dot menu (top right), then **Customize new tab page**.
3. Tap **My shortcuts** and toggle it to **Off**.
4. Tap **New tab page cards** and toggle it to **Off**.
5. Tap **Discover feed** and toggle it to **Off**.
6. Tap the three-dot menu again, then **Settings**.
7. Under "You and Google":
   - Tap **Google services**. Toggle **Allow Chrome sign-in** to **Off**, **Help improve Chrome's features and performance** to **Off**, and **Improve search suggestions** to **Off**.
8. Under "Basics":
   - Tap **Search engine** and change it to **DuckDuckGo**.
   - Tap **Privacy and security**. Tap **Third-party cookies** and set to **Block third-party cookies**. Tap **Send a "Do Not Track" request** and toggle it to **On**. Toggle **Access payment methods** to **Off**.
9. Under "Passwords and Autofill":
   - In **Payment methods**, toggle **Save security codes** to **Off**, then toggle **Save and fill payment methods** to **Off**.
   - In **Addresses and more**, toggle **Save and fill addresses** to **Off**, then toggle **Automatically verify your email** to **Off**.
10. Under "Advanced":
    - Tap **Appearance**, then **Toolbar shortcut**, and change it to **New Tab**.

## Opt Out of Binding Arbitration

1. In **Settings**, tap **About phone**, then **Model** to find your **Serial number**. Long-press to copy it.
2. In Chrome, visit `g.co/devicearbitration/optout`.
3. Select your Pixel device from the dropdown, paste your serial number, and tap **Submit**.

> **Note:** You must do this within 30 days of first activating your device. This preserves your right to take legal action against Google rather than being forced into arbitration. It does not affect your warranty or your use of the device in any way.
