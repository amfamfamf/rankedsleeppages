# RankedSleep Support

Welcome to the support page for **RankedSleep**, the sleep-tracking and wellness app that helps you understand, improve, and compare your sleep health with friends.

If you need help with anything, you're in the right place.

---

## Getting Started

### Sign in with Apple

RankedSleep uses **"Sign in with Apple"** for secure, private authentication. This means:

- No password to remember
- Your email is optional and private
- Secure authentication backed by Apple
- Easy to set up and use

Simply tap "Sign in with Apple" on the welcome screen and follow the prompts.

### Connect Apple Health

To calculate your Sleep Score, the app reads sleep and wellness data stored in the **Apple Health** app.

**First-Time Setup:**
1. During onboarding, you'll be prompted to grant Health permissions
2. Select the data categories you want to share (we recommend allowing all for the most accurate score)
3. Tap "Allow" to complete setup

**Managing Permissions Later:**

You can manage these permissions at any time in:
```
Settings → Health → Data Access & Devices → RankedSleep
```

**What We Read:**
- Sleep analysis (duration, stages, bedtime, wake time)
- Heart rate and Heart Rate Variability (HRV)
- Resting Heart Rate
- Respiratory rate
- Blood oxygen (SpO₂)

**Privacy Note:** Raw health data is never shared with friends. They only see your Sleep Score.

---

## Understanding Your Sleep Score

### Sleep Score Overview

Your **Sleep Score** is a comprehensive 0-100 rating of your sleep quality, calculated from multiple factors:

1. **Duration (20%)** - How much sleep you got vs. your target
2. **Consistency (15%)** - How regular your sleep schedule is
3. **Sleep Stages (15%)** - Quality of deep and REM sleep
4. **Recovery (15%)** - Heart Rate Variability and Resting Heart Rate vs. your baseline
5. **Interruptions (10%)** - Number of times you woke up during the night
6. **Oxygen/Respiratory (10%)** - Blood oxygen and breathing quality
7. **Sleep Debt (15%)** - How much sleep you owe or have banked

**Adaptive Scoring:**

The score adapts to the data available. If you don't have an Apple Watch or forget to wear it, the app will calculate a score using whatever data is available (duration, consistency, sleep debt) without penalizing you for missing metrics.

### Sleep Debt

**Sleep Debt** tracks how much rest you've missed or made up over time. It's calculated using a rolling model and updates daily.

- **Positive debt** (red) = You owe yourself sleep
- **Zero debt** (green) = Perfectly balanced
- **Negative debt** (blue) = Sleep banked

Sleep debt accumulates when you sleep less than your target and decreases when you sleep more. The app helps you understand long-term sleep patterns and recovery needs.

### Baselines and "Still Learning"

Some metrics require a **baseline** to calculate:

- **HRV & RHR Recovery**: Needs 7+ nights of data to establish a 14-day rolling baseline
- **Consistency**: Uses recent sleep patterns to determine your ideal bedtime

If you see **"Still Learning"** for a metric, it means the app is gathering enough data to give you accurate insights. This is normal for new users and takes about a week.

---

## Social Features

### Adding Friends

1. Tap the **Friends** tab (or **Profile → Friends**)
2. Tap **"Add Friend"**
3. Search by username
4. Send a friend request

**Note:** Both users must accept the friend request to connect.

### Leaderboards

Compare your Sleep Scores with friends on the leaderboard. Friendly competition can motivate better sleep habits!

**Privacy Controls:**
- Friends see only your **Sleep Score** and **username**
- Raw health metrics (HRV, RHR, SpO₂, etc.) are **never shared**
- You can hide yourself from leaderboards in **Settings → Privacy → Hide from Leaderboards**

### Removing Friends

1. Go to **Friends** or **Profile → Friends**
2. Tap on a friend
3. Select **"Remove Friend"**

---

## Common Questions

### I forgot to wear my Apple Watch — will I still get a score?

**Yes!** RankedSleep calculates a simplified score using any available data (e.g., sleep duration from iPhone, consistency, sleep debt). Missing sensors never penalize you. The app dynamically adjusts scoring weights based on what's available.

### Can friends see my personal health data?

**No.** Friends only see high-level information such as your **Sleep Score** and **ranking**. Raw health metrics (HRV, RHR, SpO₂, respiratory rate, etc.) are **never shared** with friends or displayed on leaderboards.

### How do I disconnect Apple Health?

To revoke RankedSleep's access to Apple Health:

1. Open iOS **Settings**
2. Go to **Health → Data Access & Devices**
3. Select **RankedSleep**
4. Tap **"Turn Off All"**

**Note:** The app will continue to work with limited functionality (no sleep score updates) until you re-enable permissions.

### Why isn't my score updating?

Your score may not update if:

- Apple Health permissions are disabled
- You haven't worn your Apple Watch overnight (if you rely on it for sleep tracking)
- Apple Health hasn't synced yet (can take a few minutes to hours)

**Troubleshooting Steps:**
1. Check Apple Health permissions (Settings → Health → Data Access & Devices → RankedSleep)
2. Ensure you have sleep data logged in Apple Health
3. Pull down to refresh the home screen
4. Fully close and reopen the app
5. Make sure your iPhone and Apple Watch are synced

### How is my data stored and protected?

All data is:
- **Encrypted in transit** using TLS 1.3
- **Encrypted at rest** using AES-256
- **Stored securely** on enterprise-grade infrastructure (Supabase)
- **Never sold** to third parties

For complete details, see our [Privacy Policy](https://amfamfamf.github.io/rankedsleeppages/privacy-policy).

### How do I delete my account or data?

To request account deletion:

1. Email us at **support@rankedsleep.app**
2. Include the **email or Apple ID** used with your account
3. We will delete all associated account data from our servers within **30 days**

**What gets deleted:**
- Your account and authentication data
- All sleep scores and historical data
- Friend connections and social data
- Profile information

**Note:** This action is permanent and cannot be undone.

---

## Troubleshooting

### Sleep Score not updating

**Check these things:**

1. ✅ Ensure **Apple Health permissions** are enabled
   - Go to Settings → Health → Data Access & Devices → RankedSleep
   - Make sure "Sleep," "Heart Rate," and other relevant categories are enabled

2. ✅ Make sure you **wore your Apple Watch overnight** (if you want HRV/RHR metrics)
   - iPhone-only users will still get a score, but it will be based on basic sleep data

3. ✅ **Fully close and reopen the app** to trigger a refresh
   - Swipe up from the bottom of the screen (or double-click home button)
   - Swipe up on RankedSleep to close it
   - Reopen the app

4. ✅ Check that you have **sleep data in Apple Health**
   - Open the Health app
   - Go to "Browse → Sleep"
   - Verify that sleep sessions are logged

### Health data missing or incomplete

Apple Health sometimes delays syncing, especially if:
- Your iPhone and Apple Watch weren't near each other after waking up
- Low battery or airplane mode interrupted sync
- You haven't opened the Health app recently

**Solution:** Your data may appear after a few minutes or hours depending on device conditions. Try:
- Opening the Apple Health app to trigger a sync
- Ensuring your devices are charged and connected
- Waiting a bit longer for sync to complete

### App crashes or freezes

If the app is crashing or freezing:

1. **Force close** the app and reopen it
2. **Restart your iPhone**
3. **Update to the latest version** of RankedSleep (check the App Store)
4. **Check for iOS updates** (Settings → General → Software Update)
5. **Reinstall the app** (delete and download again from App Store)

If problems persist after trying these steps, please contact support with details about when and how the crash occurs.

### "Still Learning" message for HRV/RHR

This is normal for new users. The app needs **7+ nights of valid sleep data** to establish your personal baseline for Heart Rate Variability and Resting Heart Rate.

**What to do:**
- Keep wearing your Apple Watch to bed
- Ensure Heart Rate permissions are enabled in Apple Health
- Wait for the baseline period to complete (usually 7-14 days)

Once enough data is collected, the "Still Learning" message will disappear and you'll see your recovery score.

### Can't find a friend by username

**Possible reasons:**
- The username is misspelled (usernames are case-sensitive)
- The user hasn't created a username yet
- The user has a privacy setting enabled

**Solution:** Double-check the spelling and ask your friend to confirm their exact username.

---

## Feature Requests & Feedback

We love hearing from our users! If you have:

- **Feature ideas** you'd like to see
- **Feedback** on existing features
- **General suggestions** for improvement

Please email us at **support@rankedsleep.app**. We read every message and use your feedback to improve RankedSleep.

---

## Contact Us

If you have issues, questions, or need help with anything else, reach us at:

📧 **support@rankedsleep.app**

**Response Time:** We typically respond within 1–2 business days.

**Include in your message:**
- Description of the issue
- Screenshots (if applicable)
- Device model and iOS version
- Any error messages you see

---

## Additional Resources

- **[Privacy Policy](https://amfamfamf.github.io/rankedsleeppages/privacy-policy)** - How we protect your data
- **[Terms of Service](https://amfamfamf.github.io/rankedsleeppages/terms-of-service)** - Terms and conditions
- **App Store** - Leave a review or check for updates
- **Social Media** - Follow us for tips and updates (coming soon)

---

**Thank you for using RankedSleep!** 😴💤

We're here to help you sleep better and understand your sleep health. Don't hesitate to reach out if you need anything.

*Sweet dreams!* 🌙✨

