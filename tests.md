import unittest
from src.main import analyze_brawlers, analyze_players

class TestBrawlStars(unittest.TestCase):
    """Тесты для BrawlStars анализатора"""
    
    def test_analyze_brawlers(self):
        """Тест анализа персонажей"""
        # Пока просто проверяем, что функция существует
        self.assertTrue(callable(analyze_brawlers))
    
    def test_analyze_players(self):
        """Тест анализа игроков"""
        self.assertTrue(callable(analyze_players))

if name == "__main__":
    unittest.main()
