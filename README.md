
# SerialLogger 
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

### What is this?
SerialLogger is a very lightweight and simple logging application, built as an extra feature of the
[Intelligent House](https://github.com/jaa2019/H3_Embedded_Intelligent__House) project.

The application is fairly straightforward and takes 5 (five) arguments in total:
| Argument name | Formatting | Description |
 |-|-|-|
| | (Default value) | |
 fileName | `eventlog.txt`| Filename of your log file. Any type is valid
 COM | `COM3` | The serial port on your computer connected to the device
 BAUD | `115200` | The speed of which your device is communicating
 PARITY | `0` | 0-4 (None, Odd, Even, Mark, Space)
 DATABIT | `8` | How many databits you're receiving
 STOPBIT | `1` | 0-3 (None, One, Two, OnePointFive)

If you launch the application without any arguments, it will fallback to default values. 
However, if you want to launch it with arguments the following is valid:
`SerialLog.exe eventlog.txt COM3 115200 0 8 1`
<p align="right">(<a href="#top">back to top</a>)</p>


### License
* Software: GPLv3
<p align="right">(<a href="#top">back to top</a>)</p>


### Contact

Jan Andreasen - [@andreasen_jan](https://twitter.com/andreasen_jan) - jan@tved.it

Project Link: [https://github.com/jaa2019/SerialLogger](https://github.com/jaa2019/SerialLogger)
<p align="right">(<a href="#top">back to top</a>)</p>
[![Contributors][contributors-shield]][]
[![Forks][forks-shield]][]
[![Stargazers][stars-shield]][]
[![Issues][issues-shield]][]

[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/jaa2019/SerialLogger/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/jaa2019/SerialLogger/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/jaa2019/SerialLogger/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/jaa2019/SerialLogger/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: 
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: 
[product-screenshot]: images/screenshot.png