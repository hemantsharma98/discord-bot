# discord-bot
import discord
from discord.ext import commands
client=commands.Bot(command_prefix=">")
@client.event
async def on_ready():
    print("bot is ready")
@client.command()      
async def hello(ctx):
    await ctx.send("hi")
  
client.run("ODA2OTA2MTAxNDAzODc3Mzk4.YBwP3g.9dyIsXFTJRylBmvkY4t7Hv-5yRQ")    
