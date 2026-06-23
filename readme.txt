Seshat is a small, lightweight, lean, free-ranged, sustainable, eco-friendly, crypto-friendly and BLAZINGLY FAST text editor witten in rust by Xqhare.
The name Seshat is from the egyptian goddess Seshat, the goddess of writing, wisdom and knowledge. Her name means "female scribe", at least according to wikipedia.

It has been made by following the Hecto guide, found on: https://www.flenker.blog/hecto-chapter-1/ ; and changed as well as adapted 

Known Bugs:
Seshat really likes to repeat the first line of any file - Why? Idk.
Search puts the cursor one line lower than expected - Why? Probably a saturating_add(1) somewhere where it shouldn't be; But idk where.

## Acknowledgments
Thanks to the open-source community for providing invaluable tools and libraries.
Used in this project:
- [Hecto](https://www.flenker.blog/hecto-chapter-1/)
- [unicode-segmentation](https://crates.io/crates/unicode-segmentation)
- [termion](https://crates.io/crates/termion)
