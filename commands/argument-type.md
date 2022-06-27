# Argument Type

{% hint style="info" %}
**Info:** ok
{% endhint %}

## String

tipe ini bisa menerima karakter apa saja, hasilnya akan dibaca sebagai **teks biasa**

**Contoh**: @funixxxxxxx\_97.com

## Number

tipe ini hanya bisa menerima angka

**Contoh**: 99999

## Boolean

tipe ini hanya ada pada [Flags](flags.md), tipe ini tidak harus memberikan _nilai_, hasilnya akan dibaca sebagai **iya (true)** atau **tidak (false)**

**Contoh:** $createinvite --temporary\
artinya invite akan disetting temporary\
\
**Contoh**: $createinvite --temporary false\
artinya invite tidak akan disetting temporary

## User

tipe ini hanya menerima user

**Contoh**: @Udin&#x20;

## Channel

tipe ini menerima semua channel

**Contoh**: #general\
**Contoh**: Voice Room

## TextChannel

tipe ini hanya menerima channel bertipe `text`

**Contoh**: #general

## VoiceChannel

tipe ini hanya menerima channel bertipe `voice`

**Contoh**: Voice Room

## CategoryChannel

tipe ini hanya menerima `category` channel

**Contoh**: LOBBY

## NewsChannel

tipe ini hanya menerima channel bertipe `news`

**Contoh**: #announcement

## StageChannel

tipe ini hanya menerima channel bertipe `stage`

**Contoh**: Podcast

## ThreadChannel

tipe ini hanya menerima thread

**Contoh**: #forum

## TextBasedChannel

tipe ini menerima semua channel yang dikategorikan sebagai `text`, seperti `text`, `voice (text in voice)`, `news`, `thread`

**Contoh**: #general

## VoiceBasedChannel

tipe ini menerima semua channel yang dikategorikan sebagai `voice`, seperti `voice`, `stage`

**Contoh**: Voice Room\
**Contoh**: Podcast

## Role

tipe ini hanya menerima role

**Contoh**: @Administrator&#x20;

## Mentionable

tipe ini menerima user dan role

**Contoh**: @Udin \
**Contoh**: @Administrator&#x20;

## Command

tipe ini hanya menerima command

**Contoh**: help

## Duration

tipe ini menerima mildetik dan juga durasi berformat:\
s = detik\
m = menit\
h = jam\
d = hari

**Contoh (mildetik)**: 60000\
60000 = 60 detik\
\
**Contoh (durasi)**: 60s\
60s = 60 detik

## Date

tipe ini hanya menerima tanggal berformat: `YYYY-MM-DD`&#x20;

**Contoh**: 2022-06-27

## Emoji

tipe ini hanya menerima emoji

**Contoh**: :lol:

## Iso6391

tipe ini menerima [iso code 639-1](https://en.wikipedia.org/wiki/List\_of\_ISO\_639-1\_codes), nama bahasa

**Contoh**: id\
**Contoh**: indonesia

## ImageUrl

tipe ini hanya menerima url gambar

**Contoh**: [https://cdn.discordapp.com/icons/716497012324958259/bf832fc1f51f117c477da001b9ea834a.png](https://cdn.discordapp.com/icons/716497012324958259/bf832fc1f51f117c477da001b9ea834a.png)

## Image

tipe ini menerima url gambar dan juga bisa dengan mengupload gambar tersebut

**Contoh**: [https://cdn.discordapp.com/icons/716497012324958259/bf832fc1f51f117c477da001b9ea834a.png](https://cdn.discordapp.com/icons/716497012324958259/bf832fc1f51f117c477da001b9ea834a.png)

## Color

tipe ini menerima hex color dan juga [warna dari discord](https://discord.com/branding)

\
**Contoh**: Blurple\
**Contoh (hex color)**: #2F3136
