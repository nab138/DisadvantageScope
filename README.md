# DisadvantageScope

[Advantage scope](https://github.com/Mechanical-Advantage/AdvantageScope), but in the terminal. (This project is not affiliated with team 6328 Mechanical Advantage).

If for some weird reason you want to use this, it is fully usable. Clone it, run `yarn`/`npm install`, run `yarn compile`/`npm run compile`, and then `yarn start`/`npm start` (or you can build with `yarn build`/`npm run build` to get a packaged executable, just make sure to run through command line). No advantagescope window will appear and everything you need will be in the terminal. Help is available with -h or at the bottom of the README. Just one warning: There's no security at all. Say bye to your precious context isolation, it was inconvenient for me.

![demo](/demo.gif)

## Command-Line Args:

- `--lineGraphNT`/`-l` [NT Key] - Add an nt value to the line graph, be sure to preface with NT:/
- `--robotNT`/`-r` [NT Key] - Set the robot with the given nt key, be sure to preface with NT:/
  In-app usage:
- K - Connect to sim
- 1 - Switch to Line Graph Tab
- 2 - Switch to 3D Field Tab
- 3 - Switch to Joysticks Tab
- Q - Exit the app
