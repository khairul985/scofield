# scofield
Yala 
Panduan Video Bantuan GitHubLogo Panduan GitHub
Menguasai Markdown
 3 minit membaca  Muat turun versi PDF
Markdown adalah sintaks yang ringan dan mudah digunakan untuk menggayakan semua bentuk penulisan di platform GitHub.

Apa yang anda akan pelajari:

Bagaimana format Markdown menjadikan penyuntingan kolaboratif bergaya menjadi mudah
Bagaimana Markdown berbeza dengan pendekatan pemformatan tradisional
Cara menggunakan Markdown untuk memformat teks
Cara memanfaatkan rendering Markdown automatik GitHub
Cara menggunakan peluasan Markdown unik GitHub

Apa itu Markdown?
Markdown adalah cara untuk menggayakan teks di web. Anda mengawal paparan dokumen; memformat perkataan sebagai tebal atau miring, menambah gambar, dan membuat senarai adalah beberapa perkara yang boleh kita lakukan dengan Markdown. Sebilangan besar, Markdown hanyalah teks biasa dengan beberapa watak bukan abjad dilemparkan, seperti #atau *.

Anda boleh menggunakan Markdown kebanyakan tempat di sekitar GitHub:

Bahagian
Komen dalam Isu dan Permintaan Tarik
Fail dengan .mdatau .markdownpelanjutan
Untuk maklumat lebih lanjut, lihat " Menulis di GitHub " di Bantuan GitHub .


Contoh
Teks Senarai Gambar Tajuk & Petikan Kod Tambahan
Sangat mudah untuk membuat beberapa perkataan ** tebal ** dan kata lain * miring * dengan Markdown. Anda bahkan boleh [pautan ke Google!] (Http://google.com)
Sangat mudah untuk menjadikan beberapa perkataan tebal dan perkataan lain miring dengan Markdown. Anda juga boleh membuat pautan ke Google!

Panduan sintaks
Berikut adalah gambaran umum sintaks Markdown yang boleh anda gunakan di mana sahaja di GitHub.com atau dalam fail teks anda sendiri.

Tajuk
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
Penekanan
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
Senarai
Tidak tersusun
* Item 1
* Item 2
  * Item 2a
  * Item 2b
Mengarahkan
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
Gambar
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
Pautan
http://github.com - automatic!
[GitHub](http://github.com)
Petikan blok
As Kanye West said:

> We're living the future so
> the present is our past.
Kod sebaris
I think you should use an
`<addr>` element here instead.

Penurunan Perisa GitHub
GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features, many of which make it easier to work with content on GitHub.com.

Note that some features of GitHub Flavored Markdown are only available in the descriptions and comments of Issues and Pull Requests. These include @mentions as well as references to SHA-1 hashes, Issues, and Pull Requests. Task Lists are also available in Gist comments and in Gist Markdown files.

Syntax highlighting
Here’s an example of how you can use syntax highlighting with GitHub Flavored Markdown:

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
You can also simply indent your code by four spaces:

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
Here’s an example of Python code without syntax highlighting:

def foo():
    if not bar:
        return True
Task Lists
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests!

Tables
You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
Would become:

First Header	Second Header
Content from cell 1	Content from cell 2
Content in the first column	Content in the second column
SHA references
Any reference to a commit’s SHA-1 hash will be automatically converted into a link to that commit on GitHub.

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac
Issue references within a repository
Any number that refers to an Issue or Pull Request will be automatically converted into a link.

#1
mojombo#1
mojombo/github-flavored-markdown#1
Username @mentions
Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

Automatic linking for URLs
Any URL (like http://www.github.com/) will be automatically converted into a clickable link.

Strikethrough
Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

Emoji
GitHub supports emoji!

To see a list of every image we support, check out the Emoji Cheat Sheet.

Last updated Jan 15, 2014

GitHub adalah kaedah terbaik untuk membina dan menghantar perisian.
Kerjasama yang kuat, tinjauan kod, dan pengurusan kod untuk projek sumber terbuka dan swasta.
