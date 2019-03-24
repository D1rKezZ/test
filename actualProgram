from kivy.app import App
from kivy.lang import Builder
# from kivy.uix.screenmanager import Screen
# from kivy.properties import ObjectProperty
from kivy.factory import Factory
from kivy.config import Config

Config.set('graphics', 'height', 1000)
Config.set('graphics', 'width', 650)
Config.set('graphics', 'resizable', 0)
Builder.load_file('123.kv')

class MenuScreen(App):
    def __init__(self):
        super(MenuScreen, self).__init__()

        self.screen_manager = Factory.ManagerScreens()
    def build(self):
        return self.screen_manager

if __name__=='__main__':
    MenuScreen().run()
