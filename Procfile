import datetime

import discord
import asyncio
import random
import time

client = discord.Client()

@client.event
async def on_ready():
    print('Em funcionamento')
    print(client.user.name)
    print(client.user.id)
    print('--serverconfig--')



@client.event
async def on_message(message):
    if message.content.lower().startswith('.test'):
        await client.send_message(message.channel, "Olá Mundo!! Bot online.")

@client.event
async def on_message(message):
    if message.channel == client.get_channel('431871102030184448'):
        await client.add_reaction(message, "👍")
    if message.channel == client.get_channel('431871102030184448'):
        await client.add_reaction(message, "👎")

client.run('NDMxODc0NTMwNzc2OTczMzQz.Dap4fg.P_-8l947yu9_Ia-0xsOSuWu1rF4')
