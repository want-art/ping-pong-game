# ping-pong-game
一个由C语言和java实现的乒乓小游戏 用鼠标操作即可
✅玩家操控：使用方向键（↑↓）移动左侧球拍，可选鼠标Y轴位置追踪
✅电脑AI：右侧球拍以逼真的难度追踪球的运动轨迹
✅球体物理特性：球会根据球拍位置旋转，并从墙壁和球拍上反弹
✅碰撞检测：精确检测球拍、墙壁和球的边界
✅记分板：实时追踪玩家和电脑的得分
✅响应式设计：精美的渐变背景，搭配霓虹灯风格
✅游戏说明：屏幕显示操控说明
# Pong Game

A classic Pong game built with HTML5, CSS3, and vanilla JavaScript. Play against the computer AI!

## Features

✅ **Player Controls** - Use Arrow Keys (↑↓) or mouse to control the left paddle  
✅ **Computer AI** - Smart computer opponent on the right  
✅ **Ball Physics** - Realistic bouncing with spin based on paddle position  
✅ **Collision Detection** - Accurate detection for paddles and walls  
✅ **Scoreboard** - Real-time score tracking  
✅ **Beautiful UI** - Modern neon-style design with gradient background  

## How to Play

1. Open `index.html` in your web browser
2. Move your paddle using:
   - **Arrow Keys** (↑ Up, ↓ Down)
   - **Mouse** (Move your mouse up and down)
3. Hit the ball to score points
4. Prevent the ball from passing your paddle
5. First to 11 points wins!

## Game Controls

| Control | Action |
|---------|--------|
| ⬆️ Arrow Up | Move paddle up |
| ⬇️ Arrow Down | Move paddle down |
| 🖱️ Mouse | Control paddle height automatically |

## Game Mechanics

- **Paddles**: 10px wide, 80px tall
- **Ball**: Bounces off paddles and walls
- **Spin**: Ball angle changes based on where it hits the paddle
- **Score**: 1 point per successful defense
- **AI Difficulty**: Adjustable computer speed (currently set to 4.5)

## Files

- `index.html` - Game HTML structure
- `styles.css` - Game styling and animations
- `script.js` - Game logic and physics
- `README.md` - This file

## Browser Compatibility

Works on all modern browsers that support:
- HTML5 Canvas
- ES6 JavaScript
- CSS3 Flexbox and Gradients

## Future Enhancements

- [ ] Add difficulty levels
- [ ] Add sound effects
- [ ] Add keyboard shortcut to reset game
- [ ] Add multiplayer mode (2 players)
- [ ] Add power-ups
- [ ] Track high scores

## License

Free to use and modify.

## Enjoy!

Have fun playing Pong! 🎮
