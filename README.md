# EmojiPack
EmojiPack is a lightweight plugin that replaces unicode characters with 'emoji textures'. It is a modified fork.
EmojiPack allows you to add your own emojis in the config file and supports multiple unicode characters, random emoji selection, and regular expression capturing. EmojiPack comes with 46 default configured emojis designed to be used with the EmojiPack ResourcePack available on MCModel.net this can be found [here](https://mcmodels.net/vendors/twistedyetcreative/).

**Required Java Version:** Java 8+

# Commands
| Command | Description | Permission |
| ------  | ------ | ------ |
| `/emoji [list]` | Shows list of emojis | `chatemojis.list` |
| `/emoji help` | Shows list of commands | none |
| `/emoji reload` | Reloads all emojis | `chatemojis.reload` |
| `/emoji version` | Shows the plugin's version | none |
| `/emoji settings` | Shows list of emojis | `chatemojis.admin` |

# Permissions
| Permission Node | Default | Description
| ------ | ------ | ------ |
| chatemojis.list | Everyone | Allowes access to use /emoji [list] |
| chatemojis.use.* | OP | Permission to use all emojis |
| chatemojis.reload | OP | Allowes access to reload emojis |
| chatemojis.admin | OP | Allowes access to change plugin settings |
| chatemojis.* | OP | Permission to use all emojis and /emoji command |

**Emoji-Specific Permission**:
Ungrouped emojis permission is as easy as `chatemojis.use.<name>`
Grouped emojis permission needs to include the path to the group (ex. `chatemojis.use.<group-path>.<name>`)
If you still don't understand how to get emoji-specific permission- as a server operator you're able to hover over the emoji (in the `/emoji` list) to view the permission node for that specific emoji.

# Dependencies
EmojiPack does not have any hard-depencies on any other plugins.
**PlaceholderAPI** is a soft-dependency which means it is **NOT** required for EmojiPack to work. If you'd like to use placeholders in your emojis, you're able to do so by also installing PlaceholderAPI.

Please note that if you are using PlaceholderAPI, you must also install the PlaceholderAPI Extension corresponding to the placeholder you're trying to access, more about this can be found [here](https://github.com/PlaceholderAPI/PlaceholderAPI/wiki/Placeholders).

# License
This project is subject to the [GNU General Public License v3.0](https://github.com/Mxlvin/ChatEmojis/blob/main/LICENSE). This does only apply for source code located directly in this clean repository.
For those who are unfamiliar with the license, here is a summary of its main points. This is by no means legal advice nor legally binding.
You are allowed to
 - use
 - share
 - modify

this project entirely or partially for free and even commercially. However, please consider the following:

 - **You must disclose the source code of your modified work and the source code you took from this project. This means you are not allowed to use code from this project (even partially) in a closed-source (or even obfuscated) application.**
 - **Your modified application must also be licensed under the GPL**
 - **Under NO Circumstances can the resource pack intended to be used by this plugin be shared, distributed or commercially used**
