import requests
import telebot
import config
import random
from telebot import types
 
bot = telebot.TeleBot(config.token)
 
@bot.message_handler(commands=['start'])
def welcome(message):
    bot.send_message(message.chat.id, message.text)
bot.polling(none_stop=True) 
