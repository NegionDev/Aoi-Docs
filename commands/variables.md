# Variables

## Pengenalan

Variables adalah teks yang diubah, variables selalu diawali dengan `{{` dan diakhiri dengan `}}`, jika variables tersebut tidak valid maka hasilnya akan tetap sama dengan yang ditulis\
\
**Contoh**: \{{message.guild.name\}} = Negion\
**Contoh**: \{{nothing\}} = \{{nothing\}}

## Default Variables

#### Message

\{{message\}} = Pesan yang dikirim\
\{{message.createdAt\}} = Tanggal pesan dikirim\
\{{message.member\}} = Mention member _atau_ [MemberVariables](variables.md#member)\
\{{message.author\}} = Mention user _atau_ [UserVariables](variables.md#user)\
\{{message.guild\}} = Nama server _atau_ [GuildVariables](variables.md#undefined)\
\{{message.channel\}} = Mention channel _atau_ [ChannelVariables](variables.md#undefined)

#### Member

\{{member\}} = Mention member\
\{{member.nickname\}} = Nickname member ( jika ada nickname )\
\{{member.joinedAt\}} = Tanggal member gabung server\
\{{member.premiumAt\}} = Tanggal member menjadi booster\
\{{member.guild\}} = Nama server _atau_ [GuildVariables](variables.md#undefined)\
\{{member.user\}} = Mention user _atau_ [UserVariables](variables.md#user)

#### User

\{{user\}} = Mention user\
\{{user.username\}} = Username user\
\{{user.discriminator\}} = Discriminator user ( #1399 )\
\{{user.tag\}} = Username#discriminator\
\{{user.createdAt\}} = Tanggal akun dibuat\
\{{user.displayAvatarURL\}} = Url avatar user

#### Guild

\{{guild\}} = Nama server\
\{{guild.memberCount\}} = Jumlah member\
\{{guild.vanityURLCode\}} = Kode invite vanity\
\{{guild.humanCount\}} = Jumlah manusia\
\{{guild.botCount\}} = Jumlah bot\
\{{guild.createdAt\}} = Tanggal server dibuat\
\{{guild.iconURL\}} = Url ikon server

#### Channel

\{{channel\}} = Mention channel\
\{{channel.name\}} = Nama channel\
\{{channel.type\}} = Tipe channel\
\{{channel.createdAt\}} = Tanggal channel dibuat\
\{{channel.guild\}} = Nama guild _atau_ [GuildVariables](variables.md#guild)

## Catatan

Saat menggunakan command kamu hanya bisa menggunakan yang [MessageVariables](variables.md#message), tapi kamu tetap bisa mengakses yang lainnya.

**Contoh**: \{{message.guild.createdAt\}}\
**Contoh**: \{{message.channel.type\}}\
**Contoh**: \{{message.author.displayAvatarURL\}}

Kamu hanya perlu menggabungkannya seperti itu.
