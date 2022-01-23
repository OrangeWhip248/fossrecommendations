# Intro
Phones are a very important part of our everyday lives and, sadly, a very trackable one as well. This guide will show you how to have a cheap phone with good specs and functionality that's untrackable. 

# MicroG
An implementation of the google play services without tracking

# Operating Systems

Calyx OS (Best choice!): Default Android without tracking. Runs everything, easy setup. Preinstalled MicroG.

Supports: https://calyxos.org/docs/guide/device-support

Graphene OS: Also based on android, supports less but more private. No MicroG.

Supports:
https://grapheneos.org/faq#device-support

Lineage OS: Based on android but with a different Linux kernel. Manual MicroG setup, more device support

Supports:
https://wiki.lineageos.org/devices/

# Hardware
Both Calyx and Graphene only support pixels. They are very cheap and a great choice. Please note:

NEVER BUY A PHONE FROM VERIZON!
They lock the bootloaders, making this all impossible

Here is a list of phones preinstalled with secure operating systems. This is not reccomended as they are more pricey and usually worse specs

Calyx OS:
https://members.calyxinstitute.org/enroll/membership/phone

Pine Phone Pro:
https://pine64.com/product/pinephone-pro-explorer-edition/

Librem 5:
https://shop.puri.sm/shop/librem-5/

# Setup
So, you just got a new phone.

If it is Calyx you plan to install:
https://calyxos.org/install/

If its Graphene:
https://grapheneos.org/install/

If its Lineage:
Due to how many devices are supported there is no single tutorial

If its Lineage with MicroG:
https://lineage.microg.org/

# Install applications
The prefered store to use is F-Droid, an open source app store.

From here you can install the Aurora Store, an anonymous play store client.

# Cellular and Networking
This is a major tracking tool, with only one way to get around.

We are not sponsored. This is just the only secure VPN that asks no user data and is fast:
https://mullvad.net/en/

Set the VPN in setting to "Always On", "Global", and "Block without VPN".

Now they cannot see your activity, but still your location. 

Purchase a Faraday case to put your phone in when not in use. Also if you use Verizon disable "Custom experience"

# Alternative apps:
Aliucord - A private discord client that supports themes and plugins

Infinity -  A private reddit client that is very pretty

Stealth - A more private reddit client that doesn't need a login

NewPipe - A private YouTube client that supports video downloading

Signal - A private messaging client. Note: SMS still isn't secure so both people must have signal for Tull security

There additionally is an open source app for about every utility app you could think of, from translation to notes.

# Sandboxing
Sometimes there isn't a client for something you want, a game for example. To combat this, install Insular.

Insular is an app that creates a new tab in your app menu that contains app that have no access to the rest of your phone. Anything in there will stay in there.

Use a firewall app to block internet from non-free apps that dont need it (Google's camera for example). Calyx comes preinstalled with a firewall

Disable background usage for certain apps in their battery settinga.

# Additional measures
Greentooth - Disables Bluetooth when not in use (stop Bluetooth tracking)

AirGuard - Scans for tracking devices near you

ImagePipe - Removes location data from images

ClassyShark - View installed apps and their internal trackers

# If rooted
Rooting a phone is a whole other adventure.

Most people use Magisk to do this. After you root, it does allow for the use of XPrivacyLua, an app that can restrict even built in permissions from other apps. 

More info will be here soon about rooting
