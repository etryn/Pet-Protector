# Pet-Protector
This userscript protects your favorite Neopets and Petpets from misclicks that could cause accidental color/species changes, conversion, and abandonment. It's not a security feature; it just helps to prevent user error! :)

Just edit the PETNAME fields in the script to reflect the names of the **pets and petpets** you want to protect. Names can be added or removed as necessary.

**This script:**

1. Hides your favorite pets at the Lab Ray, Rainbow Fountain, Pound, and Item Use Screen Dropdown Menu (only when a potentially dangerous item is being used).
2. Hides your favorite petpets at the Petpet Lab Ray.
3. Removes the Unconverted Pet Notice from the Quick Reference page.

The script will auto-update (in Tampermonkey, at least) if the Update URL is set to the "Raw" link on GitHub. This means if changes are made to the source file, your list of pet names will be cleared. If you notice the script is no longer working, check the source in Grease/Tampermonkey to see if the "pets" list has been reset to default! If you want to avoid this, you'll need to turn off the auto-update feature or clear the Update URL field in your browser extension of choice.

**Note:** This script will hide pets from the item use screen whenever *any* item with the word "Magical" in its name is being used. If you want to use a non-dangerous "Magical" item on one of your favorite pets, you will have to disable the script. This is just so the script doesn't have to list every single Magical Plushie and Magical Chia Pop!

Thanks! Feel free to PM me at http://www.reddit.com/user/Etryn with any issues or requests.
