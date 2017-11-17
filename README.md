# Bots
discord Bot by KFE iAnimeZ
Hello my name is iAmineZ if u want make ur own bot u sould follow this : 

import discord

import discord

from discord.ext import commands

prefix = 'd.'

des = 'Ur own Desc'
client = commands.Bot(description=des, command_prefix=prefix)


@client.event
async def on_ready():
    print("[]I'm in")
    print('[] Name: {}'.format(client.user.name))
    
    client.run('Insert_Token')
