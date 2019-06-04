# [NetVLAD-Example-on-Colab](https://github.com/socome/NetVLAD-Example-on-Colab/blob/master/NetVLAD_manual.ipynb)

## Description

<p align="center">
<img src="https://user-images.githubusercontent.com/44772344/58701146-24cdf800-83dd-11e9-924d-4e5e247bfec3.png">
</p>


## Dataset

### Train : 
0 : AI Center in Sejong Univ(169장,15장) </br>
1 : Clock tower in Sejong Univ(98장,15장)</br>
2 : Children's Grand Park Entrance(160장,17장)</br>
3 : Sejong university Entrance(89장,33장)</br>
4 : Sejong university Museum(110,17장)</br>
5 : stone statue (95장,15장)</br>

### Test :
NAVER ROAD VIEW + crawling </br>

## Results

The result of image retrieval based on SejongUniv Landmark dataset

[data](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAWYAAAD7CAYAAABZqT4/AAAABHNCSVQICAgIfAhkiAAAAAlwSFlz%0AAAALEgAACxIB0t1+/AAAADl0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uIDMuMC4zLCBo%0AdHRwOi8vbWF0cGxvdGxpYi5vcmcvnQurowAAIABJREFUeJzsnXd4VFX6xz9nWmZSSSUQAqF3ASkC%0ANhAFUde6Itixrmtb26prQXTd1d+6im1ddUVUsIN1dcEG0kuk95JASO/JTKbf+/vjztzMJJMQkISA%0A5/M8eZy599xzz53gd9685y1CVVUkEolE0n4wHOsFSCQSiSQcKcwSiUTSzpDCLJFIJO0MKcwSiUTS%0AzpDCLJFIJO0MKcwSiUTSzpDCfAIhhLALIXoc63W0BkKIcUKIg214vzlCiL8e4bVPCCHmHu01SX47%0ASGFuZwghThNCrBBCVAshKoQQy4UQI1tyraqqsaqq7mvtNYbS1oJ5ovFrvgB+5X0XCyFuauv7SlqG%0A6VgvQFKPECIe+Bq4DfgYsACnA+5jua7fGkII47Feg+S3jbSY2xd9AFRV/UBVVb+qqk5VVRepqrop%0AOEAIcYMQYrsQolIIsVAI0S3knCqE6BV4nSCEeFcIUSqE2C+EeFQIYQicu14IsUwI8VxgnhwhxOSQ%0AeboLIX4WQtQKIb4XQrx6JH+aCyHOF0KsF0LUCCHyhBBPhJzLCqz3OiHEASFEmRDikZDztoA1WSmE%0A2AaMbDB3rhDiASHEJiGEQwjxlhCioxDi25B1J4aM/0QIURT4S+RnIcTAkHNzhBCvCSG+EUI4gPEN%0A7hUnhPhJCPGSEEJEeM7uQoglgft+B6Q0OB/x3kKIW4CrgD8H3FBfBY4/JITYG5hvmxDikmY+41FC%0AiHWBz7hYCPF8yLnRgb++qoQQG4UQ4wLHn0b7wn8lcN9XmppfcoxQVVX+tJMfIB4oB94BJgOJDc5f%0ABOwB+qP9tfMosCLkvAr0Crx+F/gCiAOygF3AjYFz1wNe4GbAiGahFwAicH4l8ByaxX4aUAPMbWLN%0A44CDzZwbjGYAnAQUAxcHzmUF1vsmYAOGoP1l0D9w/hlgKZAEZAJbQu8D5AKrgI5ABlAC/AIMA6zA%0Aj8CMkPE3BD6LKGAWsCHk3BygGjg1sFZr4NhfgWRgDfDXZn5vK4HnA3OfAdSGfl4tuPdfG8x3OdA5%0AsJYrAAfQqZl7XxN4HQuMDrzOQPu3dF5gnnMC71MD5xcDNx3rf/Pyp4l/U8d6AfKnwS9EE905wEHA%0AB3wJdAyc+zYoroH3BqAO6BZ4rwK90MTWAwwIGXsrsDjw+npgT8i56MC16UDXwH2jQ87P5QiEOcLY%0AWcALgddZgXt2CTm/BpgaeL0PODfk3C00FuarQt7PB14LeX8n8HkT6+gQuHdC4P0c4N0GY+YAs9G+%0AEB5o5pmCn1dMyLH3m/m8It27SdEPjNkAXNTEuZ+BmUBKg+MPAu81OLYQuC7wWgpzO/6Rrox2hqqq%0A21VVvV5V1S7AIDTLaVbgdDfgxcCfplVABSDQrKNQUgAzsD/k2P4G44pC7lkXeBkbuF9FyDGAvCN5%0AFiHEKQEXQKkQohr4Aw3+zA9dB9qXTGzgdecG9w19liDFIa+dEd7HBtZhFEI8E3AP1KCJOg3WEukZ%0Az0ez5v8d4VyQzkClqqqOSGtt4b3DEEJcK4TYEPJ7HtTM+BvRXGA7hBBrhRAXBI53Ay4PzhGY5zSg%0AUzPPImknSGFux6iqugPNohoUOJQH3KqqaoeQH5uqqisaXFqG5qroFnKsK5DfgtsWAklCiOiQY5lH%0A9ACa5fglkKmqagKawDXy0TazjtD7dj3CNQBcieYGOhtIQLPWabCWSGUW3wT+B3wjhIhpZp2JDc6H%0ArvVQ9w67b2DP4E3gDiBZVdUOaFZ7xM9NVdXdqqpOA9KAZ4FPA2vJQ7OYQ/+txKiq+kwzzytpJ0hh%0AbkcIIfoJIe4TQnQJvM8EpqH5UkETtodDNo8ShBCXN5xHVVU/WlTH04GNq27AvWguiWZRVXU/sA54%0AQghhEUKMAX7XgrVbG/wINL9qhaqqLiHEKDSRaikfB541MfB53HkY1zYkDs1/XY7mtvnbYVx7B7AT%0A+EoIYWt4MuTzmhn4vE4j/PM61L2LgdDY8xg00SwFEEJMp/6LuRFCiKuFEKmqqipAVeCwgva7/p0Q%0AYlLAarcKLbSxSxP3lbQjpDC3L2qBU4DVgeiAVWjW0n0Aqqp+hmYVfRj4s3gLMHn0jIW/Gz1joRNg%0AyB1v7Ro9Y+EaNCFzoPlql6FZr7NbuI6rgDFoYvJX4COaD9nLQHMdhP70BP4IPCmEqAUeRxPbljIT%0AzSWQAywC3juMaxvybmCufGAb9V90h0RVVZWAfxv4QghhjTDsSrTfWwUwI3C/lt77LWBAwN3wuaqq%0A24B/om3qFaNtni5vZonnAluFEHbgRTQfvVNV1Tw0S/0vaCKfBzxA/f/zLwK/D0S9vHToT0LSlgR3%0A4SXHMaNnLLxSVfxXrPnr+RcOuWP2LmtS5z7AfatmTnr+kBe3ACHER8AOVVVnHI35JBJJ88gEkxOA%0AVTMnvS+E2AJMNMcmfY3mtuh8pPMJLdOwAs1anYhmeT3T7EUSieSoIYX5BEAIcRnwRlSH9L8bLdaH%0A0Tb+/t7U+NEzFv4Oza1gRfNnrls1c9KokCHpwAK0GN6DwG2qqq5vrfVLJJJwpCvjBGH0jIWZwHa0%0A8K6zV82c9FMzY69ES1z4D5qAD+Qouj4kEsmvQwrzCcDoGQsz0CIHotHcGMuAwlUzJx0yPG70jIX/%0AAO4H/rlq5qT7W3WhEomkRUhXxonB5WhhVgAvBP67BC0rj9EzFv4ReIX6WNiiVTMndQpY2XdwaNfH%0AALSojj5oSSBvr5o56YGj/AwSiSTAYVnMKSkpalZWVuutRqLRdRTGQRfWv3fb8f/wK/beepyJIWMI%0Ayv5VGPueg7BE489bj6HTADCa8a+aDRU5TV8f3xmR3B3V78U48AKEwail+Fbn41/+2pGvSyL5jZCd%0AnV2mqmpqS8cfljCPGDFCXbdu3REtTNJyZi/ey3dbCrlsZCav/7iHWpePi4d34aELB4aNyymx8/j8%0ATRwod2A1G7lgaAZ3Turb7Nz3v5/Nsp1lGAQoKtw9qS9DuiaSEhdFWkKkEN16/rexgHeW7iOntD77%0AeFi3RF67YVQzV0kkEiFEtqqqI1o6Xroy2iE3jOvJDeN6ArBqbxnLdpZRWutqNM7tU5g8pDNjeqXw%0AyZoDzFuRy5jeKYzokRxx3r3FtSzfWQZoogzw4sKdQMsE9rS+qfxn8R4SbGbG9Ermf5uLWL+/ktEz%0AFupjkmIsfPPn8c3MIpFIDoUU5nZMqJBOHd2Na15b0cg67tc5HoARPZJYsDaPGqdXvz7UojYbwO5W%0AAJhxySAmD21Y96h57C4vd72bjdur8MzUodz9XrZudafFR3Htad15/cc9VDg8PPPl1kbWvUQiaTlS%0AmNspe4trufq1FahAcqyFu97NRgXMRgNp8VbdOk6OjeKRTzaSU2LHIGDj/krOGpgO1FvUmUk2Hvhg%0AAwCn900hzmomt8ROVlps0wsIweHycde76zhYUccD5w/gnrnZeP0KnRKsGAwG5t42FqvF2Kx1L5FI%0AWo4U5nZIboldE2UVzhrQEa9foUO0BafXz/dbithdVAvAwk0FfLW+QL/ObBB8tPoAvdLjmLsslwPl%0AjkYlxJbuLGPpzjLSE6x8fu+ZTa5h6Y4SHvlkIx6fEnb8sU+1ZioxFiN1bj/PThuM1WIMs+4fOH/A%0AUfgUJJLfLlKY2xlLd5Tw4IfrCe7J/rhNKzGcnmDlrnP78v0WrXxxUqyFBJsFi8mAQWhxcE6vJqL/%0A/mE3VXVeTEZBTJSJqrp698bzV53M2D6H3hx2uH2M6pnMRSd34V/f7yKn1MFpfVJYtksTX4fHD/h5%0AaeEu7jm3HzfPXo2K5iZJ79CoCJtEIjkMpDC3M7Jzyxsdu3NiHy4a3oWb3lyNAISAl68dQVWdl7kr%0AcsPGGgRMGd2NM/qm8cmaAyxYG17/3eX1t2gd5w7pzLlDtHIb6/dXkFPqIDM5hkcvTuevn2/Rx23N%0Ar+amt1YDcNnIzIhukiOJHpFIfstIYW4nNHQddEmyUev0Uu30sXh7Mf/bWEhumQMBPH7JYOKsZtIT%0AbKyaOYnNByq5+a01ALx6/QiGZWlRGb07xunzGwSkxVsZ0jWx0b2bo6jKyadr8jAZBNed3oOiahd3%0ATeqrR4KECv/8tXnMX5uHEHD+kM7sLKrVNh6NBvqkxzHnljEtih6RSH7ryHrM7YSg6+Af04bRPTWG%0AgxVOapw+AA6UO9hbovmVVeCJBZu58PklvL8yly0HqnRRvva0LDISY3C4fBRVOXn+2+36/IoKRdUu%0AFqxreZeooionU19Zjs+vMOua4XSIsdCvczxXjs2ie1osI3okAZDewYrJKBBoXwBmo4GvNxQwqEsC%0Ac24Zw8TBnfglt5Jyu1u/JjR6RCKRhCMt5nZCqOtg2a4Sckq1jTuDgOo6X6PxN47ryTkD05n2an0N%0A9XeX5fLuslwsRoFfBX8gWNlqFtx//kAGZSSQGt98EkmQkmoXU15eisenzXHHO+swGwVTTunGnZP6%0AYnd5+ff3uzEZBKXVLqLMRqKjTZTVuumRFsuOghqSYiy6gC9Ym0dJtYv3V+bSJSmasb1bnAQlkfzm%0AkMLczth6oIovsutrD913Xn9O75tGWoI1zFf76ZoD/Ly9uFHURVKMBY9fwe6qF3OXV9X9wjeO68nN%0A43sdch0/bC3SRTmI168yb0UuQ7t14O2fc6iq8xBnM2N3e/H4FepqtSYnOwpqAPhmYwHTxmYxe/Fe%0AOnew8cmaA1TXeXnthlFYLcYj+Xgkkt8EMiW7jWjJBlhRlZPfv7gUnxL+OxmYkcBbt4zmx61F/P3L%0ArdSGiK5BwLQxWfpcc5bs5d8/7gm7/pxB6ewpriWn1MGdE/tw1andD3v9P24r4i8fbdTfC2BkjyQG%0AZnbgtD6pPPff7WwPCHIoafFW/IpCYoyFkhoXf79iGJlJ0cREmYixSrtA8ttApmS3U3JK7VQ6PCiq%0AitPjb7QBVlLtYuoryxqJMoDFpG0FBM8Iob1R0XzHoXMlxliIthixWYxahESZg36d40mNjyKn1EFZ%0AwKrNKbHz0IcbwmKdLSYDl4/qGvaF8enq/Tz3zY5Ga1KBNfsqWLOvggVr8qhuwmdcVefmtgl99NTv%0A2+esBVpuuUskv0WkMLcRnROjuXJsFmN6pTDrfztYvbec9bkVujD/sLUIlzc8maNh/YqMxGimn9mT%0AIV07cMc763B66kPfnv5iCxV2Dz5FxWI08PqNp7Bg7QFyyxy8szRH32wLRn24fQpj+qQwoC6ePcV2%0AdhfV4vEpjb4wymrdmI0Cr7/+C6NXWiw3jO/JXz7ayHWnZzFv+f4mn9vjU3VRlmIskbQMKcxtRL/O%0A8fTrHI/d5WVvsRZh8c6yHD5dm6e7NaaNzTrkHF2SbNwxJ1yUE6LNuL0KHp+CCjgVP6t2l/LpmjwE%0AUOf2IdCKEM1fm8f4AR0Z0SNZr7PR0E0RFHGHy8fKPeX4FRWzQZCRZCO3rI49JXYe/0TLAHx3WS5N%0AecOGdevAazecckSfl0TyW0YKcxtid3m5Y846yu2e+my9CG6NhjSVHh2kuq6xGyHU/RB0j6zYXQrA%0An97LxqeoCKB3ehw+RcVkFKCqpCXY9IiJHYU17CzU/MaKqpJbVqfPaTQIpp/RgzcX7424pliriWtO%0A60FJteuQ5UQlEkk4Mo65jXC4fNw+Zy27imqJiTJx6chM/n3DKIZ10xI+1udWNH1tIMZ5+hk9Gp3r%0AGB/FuSd1Ylz/tEbnhnXrEPbeH9D1vp3i+Me0YXRNjmZXUS25pXZURcVqNlFa42Lc098zZsZCXlm0%0Ak1UzJzHvj2M1vzZgEtqG4zNTh5KV2nQRJLvLx73zfmHG/E2H+mgkEkkDpMXcRmzYX8nOQs2FYXf7%0AAtl0BvaXaUXnM5NjGl0TaikLIDekQH2Q4ho3/9tUyBn9GscFr99fBcBJmR2ocHg4WKFZvFed2p2T%0As5KoCUR3KKoW6zxhUEfyyuu4ZEQms5fsZXtBDS8v3MH7K/ejqpqFH4ygu2fuLwAkRpuxu/1EmQ1Y%0AzQbKaj1cc1p3Lh/VVUZeSCRHiPy/phUIDY0zCoHb68cfwQ/73ZZCquq8pCdYGde/Y6PzkQoJNeTG%0AcT258OQMfj/rZ0CzZl+8ZjgDMjoQYzXhcPn445w1FFTWYTQIUuOiGNI1kRW7S6l0ePR5XF5Vj58e%0AlpXEmN4p5JQ6WL23XPchBx/Bajbg8ip0S4mhyuHB61fw+hXsgWqf7y3L4b1lOXKzTyI5QqQwtwKr%0A9pSxt7iW0Mi3wZkJ2F0+ckod3Dq+F4t3FLO7yE6c1cTMy07Ss/RCiZQNCPDKdSN0f7Td5eW611YS%0ADOhQVLjz3WyuOa07t5/Th/X7K3RLHVWlqNrFu8v28UV2PgYBL107opFvu6jKyZSXl2EyCF65biR7%0AS+x6mBugR4+U1Dh57srhJMVYmLlgM+V2N6/dMIouSdFH5XOUSH6rSGFuBRJjLJzUtQNdkmJYsauE%0ACoeXzXnVnDWwIzmljsCmmiaW1U4vt85ew7WndeeP5/SJON/WvPpswJvH9yTaYqKk2kVMlInb56yl%0AsNrZ6BqLyYDD5ePNn/Zi0Pb1dIv3o1UHAK3fX3Cu4AZdaH2Ml64dQYcYC8O7J7Fq5iQg8EXw75Xk%0AVzpxehRdsC0mAy9cPRyLUbuvdGFIJEeO/L+nFQhaunaXl2U7S/TjP28vwWQQDO+exJIdJWHXrN8f%0AefOvqMrJrW+v0d+/+dNe3vxpL8O6JXLT+F711nAIN47rSb9O8Ux69seICStBgvHF0RYjPz5ytp7k%0A4vIqEUU72F7K41P49O7T6ZIUTXZOBbfPWYvHp8jkEYnkKCFTslsJu8vLH2avZU8gZjlYR/mla0cQ%0AazXz0apclu0sDUuvnjCwI09PGaq/DxYSCgplS7tZg9bR+vutRWH+6Tsn9qFTok2PWb761CyW7yol%0Ap9TBVWO7sXBTIWV2T9g8wSQXh8vHne+u5WBFnUyrlkgOE5mS3Q6Yt2wfL3+3O+yYCtw1UbNCk2Is%0AXDE6i4RoC7uLasjOqQTgh63F8PEGXZxDswEP1c26YQRHv87xvH3rGKC+0H1hlZP/bijAbBSkxlu5%0AaVwvFFXVUrXtHq48tXtYneVQX/aOwhq25WsxzdIylkhaFynMrcC2/OqIxxuKa5ckG9e9thIR8AGD%0AJs6X7CtnRI9kpo3NapQNuHRHCac/+R3eQFBysIiRoip4AwkoKrC9oIbbZq9hxqWD+XRNHkaDYMP+%0ASg6UOYi3mXnp2hFU1Xn4ZLXmb/5xayGr9pRRXuuO2HE71M8skUhaFynMrcCgzER+2FbS6HiohWl3%0Aebl9zjqKa1wYEAiDSrzNTIXD22wReYfbx8AuCXRJsrFhfyUHK5zMW5HLhSdnEGU24PYq+ibf+v2V%0AXP7SMnyKQkZiNPtK7FjNBu49rz9FlXXc/8F6fIrK6F7JZOdUUF3nZV6gVZUAnvlqK1sPVss2UBJJ%0AGyN9zK3I3uJarv7XClTg83vO0JuUBmOLg92uUSHGaqSDzYIqBHNvG9uiesUvLdzB+yu0AkK3n9Mb%0Ao8FA746x3Pludti4y0ZmMn9t5M4lRgEDMhKIshjomRbPR6u0+S48uTMmo7GRS0MikRw+h+tjlinZ%0ArcTe4lqufm1FxM7RwXA5RdXijhWg1uUnr9KJ2SBaJMrBXnygtXa6fFQ3zhrQkfvf/6XR2KAoiwjz%0A+FXYfLCasho3n4e0nRIIBmUmALINlETS1khhbgVyS+yaKKvhnaODDO+exKvXj4x4bU6Zg7ebKAwU%0ARIs1XobHp5BgM/PKdSOpcXq54uWluEO6jrx07XBWzZzEqpmTeOLSwZzaN1XvKQgweUgnfazd7ccd%0AUiTpi1/yeXnhTtkGSiI5BkhhbgU+WXNA38ybvzaP+z9Yz5/mau6FnBI717y2gnvnZZMQbWbCwPRG%0A17/+0x6mv74y4tyhscZRJsEtZ/WiJrCJ527QCuqVRbtwBMLxzh3SmeeuPJnT+6UxpncKACt2lWIy%0ACsxGgdPtw2w0IICnfj+YARkJmAwGZl0zXLaBkkjaGOljbmN2FNTwS25Fo7C0vcW1zFq4E6FCZnI0%0A+8vrIraB+mBFrh7dEcrwrESycysbHW8Y0lZU5eTyl5bi9auYDAKbxRgWSw2a39lmMfHsNBmvLJEc%0ADWQcczshp8TOgx+tJ6+sDhWIMhn4faBtU7BAfTAs7UCZg9d+2IMAXrpuBCt2l7J/xX69DVQokULo%0AALJzKsgOqWcBkUX5ipeX4fWrGISWRv3Q7wbyzYaDLN9dro/zq1oFPBmvLJEcG6TF3ErsKKjhf5sK%0AMBkERdUuvt9SBNQXINIyA9fgcPupsLtw+1TuntSXLkk2/vLxJlRV5ev7x9EhxnJU1hOaRRiJoPgG%0AIz2mjenG3ef2Oyr3lkh+60iLuZ0QbCUFWuumoDDXOL16zYnqOi/nDe3MO0tzAMJcFK9cN+KoiTK0%0ArKdgMNLDZBBcd3rjovwSSVtjnzMH+6uvoXq9xFx1JXH334cQkeKLTiykMB9FQuswW81GLhiawfQz%0Ae/Dmj3swGwVp8VYSoy2c/9xi3F6FmCgTNXVefnh4Ag63T7dorzk1i2e+2kpxtZPoKLPeE/DX0JQL%0AJEikqnISybHEs2kT1Y88hnXSRNyr11A760W8e/aQ9O/XTnhxlq6Mo0ikjb3MpGgKq5xYzUbcPkVP%0ApQ4lzmqizuOj4an+nePpn5HQ6kkev6ZYkkTSWtQ8909qX5gFQNxfHqb2uX+Cx0PSm2/gLyk+rixp%0AmWByDOnXOZ4rA1bp8l1a49O8ijoQMLZPCiYDmAxafQuA0/tqYWsOtw+bxUTvjnGA5sZYNXMSb986%0AhhE9koDWTfJoWCzphjdXyV59kmOOv7RMfx0zbSqGhAQwGHB8+BHVjzyGSIhHKSujdtaLlIw/C0WJ%0AvH/yaygcMYr8jEztp19/fD7foS86CkhXRitQVefB6an/Bfr8Kos2az7my0ZmsulAJbuL7azLqSQh%0A2syLVw/ny/X5LAhk6AVF2O7yMnvx3lZP8jiUm0MiaW3K/3Abrm++BUXBMmokyZ9+gjE1RT8voqNR%0AqqpAUXD/9BMAvu07sIwfh+fnpfh276H2b38n4dFHjtqaKh58GKWwEJGUhCE5Gf/u3VRcdDFp//36%0AqN2jKaTFfJSxu7y8vGgXRiHISonBbNTM49P7prJq5iTG9U9jd7GWBej0+DmzXxr9MhIY1EVLf06O%0AtTC2d2rYBqFM8pCcyDjmz8f11ddEnXkG0VdfhWf1Gmr/9nesZ0/Qx9Q+/wJ4vWA0Ykiud+l5NmxE%0AREUB4Pzm21+9lvI/3EZ+1yzyu3TF+f77ACS+NIuU7xcB4N2y9VffoyVIYT6KOFw+7np3HQcrHNwy%0AoTen9U2lY4KNmCgTS3eWsmhTAffO02pZCGBs7xS+/CWfL7PzeParbRiE4KVrR+BXVH2eJy47SW/X%0AJJGciNTN+wCAhCdmkPC3pwFNZC1Dh2LsoUUH2V/9lzbY78fUJ6QFW2Ulap3W/V2pqflV62j4BUHA%0ANWLu2xeTyaTfP5RQIS+99LKj5k6RwnwUCRaTr3H6eParbcxdnkuF3c1tE3oD8Pj8zXgD7bJVYMVu%0AzYf2zFfb8PgUHr90EHFWMxv2V+rz3D5nLRc+v4T3V+Yek2eSSFqT8j/chmf1agAq7rlXOygESk0N%0Ajvnz8e/bh6l3bzBqfzGahgxBVULE0Vj/l6QhPv5XrSXSFwSAd9u2et9yyP2asvSPBjIqoxUItmHa%0AX1ZHvM1EUZWLpj5lg4BIbfn6h3QgkUhORBzz51N1158QCQmo1Vpziehbb6Hu9TcwduuGMT0dz+rV%0ApP28mLoFn2Gf9SKGLl1Q7HaoqtImMRp1Kzb2lptJmPH4Ea+neNxZ+HbvptP2rRji48nPyARAJCWh%0Aejxgry9EhhAQGwu1taT9vBhj9+4UZnbD2K0b6SuWNZpbRmW0A4KWs8PtozAgysmxkeOCG4pybJT2%0AJ1OwA4lEciJgnzOHopGnUDj0ZGr+8RyqquoWauwfb9PH1c3T/Lq2SRNRKrQGxcbUVGznnA2AUl4O%0ADod2vG+f+tY/gMjs0ugeh4MhSYuA8hcX17skDAbUigpNlEPC8Uz9+0Ntrb4+g8GgW/pHAynMrcDw%0A7kn88PAEBmTEE28z8er1I7lpfE8A/nxBf0yG+l/wvZP78cPDE1g1cxJzbh3DDeN6cv7QzoDWgWTd%0AvvKI95BIjheCiSL+wkKU0lJqZ71I3Tff6MIbe+01WM8/Txtst2MeMZy4xx4NE0rTSScFJvNAwK1g%0AOfVUEp7/p3bcZKL2sRnETL+eqDPPpHbWixQOGHRYAh09dQoA1U8+RfVftOiO2JtuxHLKKdotThqs%0Aj/XX1nenLxwwiJJLLgNV/dXulCAyXK6ViNS8NDbKxNzlufhCzOTnv91BtdPLzeN70a9zPB2izfz7%0Ah926i0MWqZcc79S8+BIAllPHorjd+Nauo+q22zGkayVv/cXFJP77Nd0VkPbF54AmlJ7Vq6l+8imM%0AGRkAxN54A97cXNyLvsP53lycASNHxMejVlRgHjyYmqf/BoBaV0ftrBcxDRhAdFD4myFmyhRc3/+A%0A69v/garqXxClZ2nWulob4soIfKkAGDp1wrtG++vWNmki0Dj873AtYCnMrUSweWkw7K242kms1cz+%0AMu3PsJgoI09fPpTBmR30kprBtGivX6FTghWDwSCL1EuOe7y/rAcgetpUqm6/UztoMKDk5wOECW8j%0AYQPcP2pxy0Gh9G3aROmi7zTLOWANmwcOxLN0KXWffabNbzbr56pnPontvMktygz0/LJej8bw7tyJ%0Aoii65S5iY/VxqjdgMFmtKAUF2usoC3GPPapvChrSUlFKSvGsXsO6tPTB+RmZIiM/r0Xmu3RltCKh%0A4XOXn9JNF2UAh9vPn+Zm887SfUBoAXw/aXFW6tx+Hrt4oIxflhz3qAHXg2ddSC9KIRA2G4aMDNyL%0Al1A3d54uvKHRDuZRgU4/NhtMoJKMAAAgAElEQVTW005DCIFl6FASnnoSY3o6hpQUjL164Vm6FADn%0Al19p471eTP206ohKfr5mBR+C0IQSY+/eUGun4qKLdReH6vU0uib6iivIyA+0ZHN7KOyaRdUjj2n3%0ALSnFPO5MANJMJgvwTEs/MynMrUho+Ny/f9gdcYzZpP0KQtOii2tcVDm9vLRwl4xflhz3GDtpLcw8%0Aq1brxwzx8YjYWMy9e5GRt5+MgwdI++JzDAaDvikYPfUKvGs0N6AhOpraWS/qAht7w3TS160h/vFH%0A8e/Zg3nEcG1ip1O/R8z11+mvnQsXHXKdzi++ABonlMRMmYL1/PPw79xVP9ijiXT0ddfg+GR+/fGo%0AKH1TECDxyZkgRNDPfdkhFxFAujJakaA7oyVMG5tFn07xuj8aYGt+Ne+vzJVF6iXHNbE33UDVPffh%0A21UvbNaLL8Y5bx6GlMauuuCmoGfDRu2AEKiKgrDZcC5chO28yXo5UH+pVpOmwz+fw71kCTWPP6HP%0Ao/sMzGaUstJDL9Tl0oZHSChJfuP1sKGOjz+m6p77qP3r03jWbwDAdNJJxNwwneo/3aOPE8nJoZEj%0ACYdehIYU5nbE4Qi5RHK8ELapBhgyMjAPGkid06mHwYWiR2PkHdQOBKIdVJMJpaxUj/IQ8fG6cHrW%0AbyDuxhvDhLlmRuC1EBG/ABphtYLXi3fbNkhL044FEkr0L4Lycs1aVlVEYqLu/wZI/NcrmLOywoS5%0A+uG/hN6h+tCLCHwGLR0okUgkR0ryG6+TkbefhKeeRCgKtX99mtg776gPkwsh6NP1bt6sH7NOnIhq%0At2NIScXx3lwAYm68AWNWFgB1c+bUxx7HaVUahaoSdc454PE0+gIIxlUX9O1PQb/+FA49GWNmFwAq%0A77mPsrO1TUhz/376F4F5xHBwuzULOCoKtbIS8/DhiLSA6Dud9aF5gY1G15dfIVJTgxuPn7f085IW%0As0QiaTNib5hO7A3Tmx0TycI2DRyAGrCwa155VRt31ZUYM7tQfe/9eLdtr489njYVY2Ym9n+9hnf9%0Aev0LwD5nDjX/9xxqTQ2oqpbeHYioiJ4yBcdbsxEdOqBWVOCvqACLBW9xCaUXXgxoIhvE2LsX/i1b%0A8WZnYxoyBF9JKdUzn8SUpTVPNvXqBRYzvq3bUEtLKfH7PWlG4wMt/ZykxSyRSI4JYVZr3/4UDBmm%0AJ4Q0Z2GHBr3FTNGsazwe6t6bCyYTqtVKzPTrSV+3hk4b15Pw0IN4N2+m+pHHUKurtYgLwLdxoz6P%0AY847YDQSNWECGfl5pH77X/B4iLngfK2qXQOUgkL9tTFQ7c6zfAV18+YBYP39pfi2bkPExyPi4kgz%0AGi3AJS39bKTFLJFI2pygewCLRY9wMPXqSe2sFzEPHIjtvMlAZAvbPGgg3s2bccydh6l7d/14/CN/%0AwdixI5V33U3U4MH6HACuRd/pry1DTsIZshEZugbXF19Q+PPPmHp0rz8XATWYYGIwgOIn4aknsf9L%0A66gSPW0q/tz92ji3W58bmB+ov7Ef6N5cTLO0mCUSSZsT9BOHiBa+DRvBYjlkaFvM1Vdpc7w1m+pH%0AHtWPR0+9Atull+jRG6GEdkMxBjIOwwj4hEVsLAmPPYpntZbJp1YfovaFwYAhJVUP3wta6J61gWJv%0AbjfGPr1Dr9gEdAMWNDtt83eVSCSSo0vxpMnUvf9B5JNCHDK0LZhgYoiNRVitmAYNAsAQE4MQAhEb%0A22iO0G4oltGjwyf0ePToC2PHjtguvQQC4XIiPq7phQgBPl/EyBI1pJhRA3HfEPjvBJpBCrNEImkz%0Aql+YhW/LliZdBHg8GFJSsc+ZQ8GAQfX99jIyKbnkUj3yItRC1SvP2e2oqqpHb4QS2g2l7qOPw+9p%0ANuuFkZSqKopGnqKH4alud9MPo6qYTx4WMbLEECLoSnWVfgXQMbikpieWwiyRSNqQug8+BCDqzDMi%0AD1BVzH166xt1oXjXrI1YiD4ounUffYxzwWeoTifuH37Qy3+W3/oHSi+4UB/v+vLL8C+GkM09pbgY%0ApbJSTwpxfv6FFt/cBEp5RcQaHCKhQ/0bp0t/OqA4uIwmJ0UKs0QiaUPUQLpy7PXXRzxvSElBCbSK%0A0rFadVdDpL5+QdeGY/bbVD0+A4CY2/5AwmOPamncX/9XE/xhw/Rrkl59hYSnnqwX6BChDia4AJj7%0A9ydj725trCEglzYbsXfeAURuZ+XZtAlvdnaj42h6OzTwenHEDyBkoEQikbQJIpD84VqyRKsr0fB8%0ASgpKWVnYMUNsjC6KTRWiD7o2YqdfD0DMtKmarzjEmk2cMztwE4Fz4SJib5hOdCDcrvOObRgCNT2U%0AkhJi7rgdAN++ffr8lpFaQaW0b/9L3J+1kGTVbtddLYWjTsHv9+sRIHEPPagnu4TUhD4JOAhc1Nzn%0AJIVZIpG0GdFTfg+A4403MSQm6sfNI7SuS/4dO+prZARQyiv0UpyHKkQfjL4IbgTqVi5giovThVop%0AK8U+Zw7Oz7VkvILBQ1CKNS+DdeJEEh56sPHaIxTSx+vF2LOHVms6v4Cqm2/R1xB3y81k7NiGITWV%0ACkXxAn5AAfY1+xBIYZZIJG1Iwv33I1K0CAmlqEjbeAO8mzZp7gGLRdscDEVV9c24YL3mpghGX9T+%0A5z8UjhgV1tXaF8j4Q1Vxr1xF9SOP6VYyDgciUB/DX1RE3Xwtmi00TjpYZS5YpjS49sQXnifpA60l%0AlnvZcn0Nwc1IpaqKZKPRDJQAAjgD2J+fkdlkgWgpzBKJpE2xnXsuAJ337SH6iisAiBp9imalmupz%0A3kIL0wOYhp9M3GOP0pDyP9xGftcs8rt0xblIi1+u/dszuushSMnIU+rfBOKn/bvry/Gq5VobN++m%0ATVQ/qt3Hu3NnWA/BYEZixsEDCJtNW1e3bhgDPnDV7W60GRmyudgJCDrJM2mmPrMUZolE0qaEWpSG%0AFC2dWSQkaH7YkPC09LWrMaRqYW8iMZGOX36hNT0NIbSofvTVV+Hbuk3fKHQtWqT5ioN+5tDU6kh9%0AAOMCXwQ+n95GKuYPt9ZvIjYoth/0l/tycvAHLHMRFRW2GVn95FOIEJcNcA+aOwOaqc8shVkikbQp%0AoRalCIioMJs16zLU9VBUhGrXBLIp33KwqH7CEzOInjpVOxiYE5eLqCFDIGDZxvzh1uYXVlGprSVE%0ASE1pqU1mEwb95ZX33U/FtCsBiBqjJa+Exlmb+/QJvayQet1tsj6zFGaJRNKmhFqUjnfeJeqMM3Cv%0AWEn1k09hm3K5Pq7y9jtQAx1Jgr7lYOGjoHtBqdDcD8bUVNzff69dGEyvtlpxLlyoW+HKodKrA8T9%0A5WH9tXvpsqazCVNSwGTCv3cfnuUrMKSn02H2W43WaLtiSuhloRX3m6zPLIsYSSSSNqe58p/2wYOp%0Afvpv+LZtB+p9y8HCR9ZJE3GvWUPtrBcRwaL6xcV6NxPRoQNqcTEYjXi3bNWtcENz6dUhxFx6CTUP%0A/Fmbt6g4YjZhcC2hhZM6PPUkFVddo/cfxGCgdtaLJL7xOju8Hkc/syUGmAYUAek0U59ZWswSiaRd%0AEXvDdDL27iYjP4+M/DzdtxyMD3YtXETsbbeB2axXeat+8ik8mzYBED3xHOKfnIlaV4cvJ6feCvc0%0AbqZq7Nmz0bHCEaP012ptrZ5NaDvnbN0aLr1Mm9N2xRTd1VH7xpu6KJtOGqyH+FXecituLZD5U7SQ%0AuTRgOdBkfWYpzBKJ5LggtEJc7TPP6pt5hs6dcS9egm+T1vHEMX8BnuUrtA0+oxHnp/PBbKbuk08b%0A1ejw5+Zi6JIRfqOQJBZfXh7VTz5F7J13YMjsQvUjjxEz/Xosw7QEPs+y5Vq8tNGId906/bqoSy6t%0An89mY4glKhbYl5GfZ8rIzzNm5OedJst+SiSS4x+lfmPQOrm+1rIhsQOp/9W6i1gnnoOwWHAtXKid%0ArKvTxNjr1TYSPR4sp51Khxdnaef9fpSD+RATU3+fkA3IDv/3rF7K0/2d5sOOnnqFHopXee995A8Y%0ApM1tMevXOWbOrF9ffPxhd8mWwiyRSI4PQkLcTENOqj9sd+hujg7/fI5OWzaFxUPbLrk4bBrPsuUI%0Amw1hs2H7/e/JyM8j+pL65iLpmzdqSTAh7hMIzyo0BXoNiuhozN26BiYOCccLSQU3de8e7Ngtu2RL%0AJJITDGO9XNlfmKV3HjHExDROxTaZ9FKeDRNVhM2mCa7RiPOrryhcsqS+Ywma2OJwgNmMd+MGikae%0Agur1aseBopGnYOyl+abVujq8O3ZqFwavg7AvEc+WLcF2WLJLtkQiObEILXYv4uK0zTwhMA3o3ygN%0AOijKEO6bBk14fTn7UO12TH36hHUsAaj78GMtTE9R8O3eQ8z064m57jr8+7V2UUpdHd7A+A7/+D8s%0Agap1QeEOw2DAfNLgYGnQrS19VinMEonkuCC02L012IVEVbGdc07jNOgQYfYFojWCKDU1+AuLADD3%0A7knlo4+Fna95+mmizjlH31yMnnoFqq/eTRFMigFQPZ6GmX3amEA9EBQF78pVKJoFXdVoYBNIYZZI%0AJMcFwcQUER+P8+uvEYG6yNbzz2uUBh175x3E3HoLAP599cXcRKdO4PWiBGKenQs+16IwQkqQiqgo%0AvOvX6y2rnPMX4HjjTf182oplkKC5i+vmvIMIepADyTAI/QiJr7xMxsEDVKmKj/ruJYdECrNEIjlu%0AiL1hOp23byUjbz+d9+wi4aEH9Q4iDRuimgcOqL8wUGNDLSzEet5kYm//Y/jEgZA3jEaiJkwIa1lV%0A/cRMzCfXF9l3L1uG8HjAZMK7axfulau0+991J7bLLtP8y4GQO8vpp6GqKtHCYKC+e8khkcIskUhO%0ASIJ1NAA6rg90FBECER3TuIGqy4WI0QryB2s1O+bO1U+bBg3WXzvefEvzQRsM2H73Ozpv20LCU09S%0A9/Yc3EuWEHvnHaQsmA+A8+NPcC74DKsQBuCrlq5dRmVITmjsnloe+Pl+SutKMBvNjOg4kukDb+SR%0A5Q+HHbtz2N1YjE00CJUclyiBrEAAY4Mi+ZahQ4kaNw734sUAxNx0I46587RsPaNJT7d2vP8B/pwc%0A6ubOxTRsKL71G/Bu3EjUOefg/u47XeAjpZgnPPUk9n+9hur18rbdXjQ9NnZ+S9cuLWbJCY3RYOKa%0A/tfy0lmvMrHbJJYcXMym0o2Njq0rWnuslyo5yoT27tOL5INe8yL+gfv08/6SUnC5wO/H/fPPANQ8%0A/wIiEO1hHT+OtK++BLNZ90EH/dtNEepaeaymKr+5TL+GSItZcsJh99Ry35J7KXQUAGAURsZ2Hkvv%0ADn0wG8xkJXQnKyELgFRbKmaDmc6xGc3MKDkeiZ46Bc/q1QBU3nCjdlBVdSs3uGFY84/ncH39tbYB%0A6HbX1212OvGt0b6wvVu36UXvE195GdsF57fq2oUaqWB0E4wYMUJdF5IPLpEcCyK5J0JdEU6fk9WF%0Aq3B47Oyr2cd3++vr6EYZo/ArCn7VhxrYO0+MSuSls14lIarFiVmS44TyW27F9c23mrVsMmmF70M2%0ADEOpee6f1L4wq/6A1aqJtKIgrFZETAzR06YS/+CfI17fHEKIbFVVR7R0vLSYJccdLp8Lp68OVVXx%0A+D0sObiYkR1HcUbmmQDYTDbGZY4H4Ou9X2IUWtzpGRln8tPBHxEIDMKAX/XTOSaDAkc+t353Ez7F%0AJ33OJxjJb7x+6EEBGiWiGI2oXi+oKomzXmh1KzkUKcySdklzVnGMJZZbBv+BrITu/GvDK2wq20ih%0Ao5Dbvr9VH9+rQ2+2lm/Bp2iJBv2S+pForU8E8KtaoZqgu2NIylCuGzSdhbnf8tmeBYzpNJaxGae2%0A/YNLjhmhmYWxD/4Z+//9A1QVU7++zfqSWwMpzJJ2SXDTLiuhuy6Wm8s2YffYMRvN9O7Qhy1lm/Gp%0AmvDO2/EeAAKBisrG0g1c0/86dlXuZHXRKnZU7GBnhVbTQKXefRd8XeEuJ8WWIn3Ov2GsZ0/QXRm+%0A7Tv0zcL4e+45bNfFr0VGZUjaJTaTjbEZp9I5trMulhf3vJSXznqVcV3Gs6F0vS7KAFnxWhEaFZUU%0Aq2b55Fbn0jW+qz5mUtZk7hr2JwT1/5MlW7VmoDsrdzL168t5Y/PrDEoZTMeYFidpSU4QQjMLXV9/%0ADTYbMXfc3ubWMkiLWdLOCHVhGIQBj9+DgoJA8OHO99lbvYdYcywGYWBa3yv57sB3lNQV4/TV6dZy%0AYV0hAEsLlujzdoruxKj0UbyQ/XyYxVzu0nrGCQQPjnyY3Npc5m1/j+/3f8fvel7Ytg8vOeY01/Kq%0ALZHCLGlXhLowvtn3NV/u+4L+SQPYXrGN9JhOLDm4WB87b0d9ZlZxXeRsV5vRRoothTx7Hl/v/Ypa%0Ab+SGnDGmGDrGpFMUEPUoY1TEcRJJWyBdGZJ2RdCFUeEq54cDWseIPVW7AcivzQcIc0UE6ZnQS3/d%0A0VbvhnD5XeTZ8xAIMuMyiTOHN+RMC4y1++z8afGdzN/9Ked1v4Czuk5AIjlWSItZ0u7YWraFx5Y/%0Aij/EhwzgVlz0SuiFyWBiR+UOLAYLHkVrsLm/dr8+rthZbz0H3RYqKuXuchRVCZuzxFmMzWjD6Xfy%0AxyF3MDFrUms9lkTSYqTFLGl39ErszctnvcJV/a8B4OSOwzEIA1ajjT3Ve9hdqVnQQVEG8CneiHOB%0AZoUD/FKcTZ3PicVgISmqPl3X6XcyIGmgtJIl7QZpMUvaFfuq9lLjqSE9Jp0qVyUAqwtXMSB5IOnR%0AHfkx70f8+CNe+/CoR9hatoUv930Rdtzp0+rknps1maFpw/AqHtYWreV/ud/qY87qOgGTQf7vIGkf%0AyH+JkmNGpCSS0zPO5PVN/6LSVUmMJZbBKSexp3I328q3sq9qLwOSBhBvSWBV0cpG8/19zdPN3s/h%0AdfDy+hcpdZbqxwSC8ZkTpLUsaVdIYZa0OUFBLgmExA1NG0Z6dDpf7vuCMZ3G8takOWGW8+rCVby1%0A5T9MyjqX83tcwFub3jz0TSLQO7EPtw+7kxpPDbsqdvL53s/YVLoRp69OWsuSdoX81yhpcyJl9Z3d%0A9RxMwsTsrW/xfPZzGIQBFRWf30dcVByj0k9hef4yvt77VZOuDLPBjFEYcfldxFsSqPHUNyUenHIS%0AZ3WdwM95Syh1ltAnsS82oxUAq8naJs8tkbQUKcySNicYEmf31OqV374/8B0dLB2Y2ncaWfFZPL7i%0AUexeO1HGKIakDuXOYXfj8bu5f8l9lNQV41f9YYkiAF7FixdtE7DGU020KRoQ1PkcGITAZDBR7Cxm%0A3vb3UFQtaaVbXDduG3J7W38EEkmzSGGWHBO2lm3h8RWP4VU89EzoiclgZmflDv6z+Q28ig81IJxj%0AOo1l8cGfGNNpLIlRiZze5QysxijmbZ+LT/VhEIZGIXAAUYYoPH6PnradYOkAwOV9pnB5nylt+qwS%0AyeEiw+Ukx4Reib25f/gDnJU5gb3Ve3H4HIAWQeFVNEFVUfVMv+8OLKLWV8uPB77nvW3v6oIbSZQB%0A3Io7rJbGqsKV/HPdP/D4PRHHSyTtCSnMkjZnX9Vetpdvo85fx4qC5QAcrM0jzhLP3097lrO7nqOP%0AVVFJs6WRXbwOn9/HvcPvD8v8s0RInY4yRCEQPDTyL5yVqUVbDEweJFtISY4bpCtD0uZUe6p5Zf1L%0AekjcKZ1OIcWWyvzdn/LQsj83Gl/iLEEg6BybQafYTrw84VV+zPuRT3d9jDdgAfeI70me/QBexYtb%0AcSMw8H9rnyU+Ko7zul9Ap5hObCnfLMt5So4LpDBL2pxhaSc3ColbdnBps9ckWZNxeuvYXr6N9Jh0%0AKpxat4ngBuC+mr16p5L06HSK6oqY0PUcJnQ9mxkrHsOjeBiWdrIs5yk5LpDCLDlmhFrOsZZYxnQ6%0AlUHJg/hszwLKXKVhY8tdZSzO/4l1RWupdFUSbYqmf9JA4s1xrC5eBWhNV0/vcgZOr5OiuiJSbKn0%0ASuzNrPEvsbxguSznKTlukMIsOWYELWfQ/M7f5nzDm1sa92hLsaZQ5iqjZ0Ivbhtyu25p13pqeD77%0An/o4j+Jhcd5PABiEgU92fsTnexZwUuoQ+icNAGQ5T8nxgRRmSbug2lNNdvE6DBgQiLAkkjJXGQOS%0ABjIqfRS3fX8rxY6isIiLIBO7TmJZwVLqfHUoqoJBGHD5XawpWk12cTbnZk2WqdeS4wIZlSFpFyRY%0AErjr5D/xyOhHGZk+EoB4S7x+/tSMU3lo6Z8pdhTpGX4AJoOJqEAG35byzWHhc4qqMDp9TKAjto+h%0AqcNk6rXkuED+K5W0C4L+5jJnmb6hV+PRuo0MSBrAiI6jmL/7U4QQePwe3aL2KT58aNZzQaDjtVEY%0AsZmisXtrWVW0Ug+vS41Oa+vHkkiOCGkxS9oFQX/zE2OfJMWWglEYdUt4R8UO7l1yN52iO/HHIXdE%0ArJVhNdo4I+NMAPyqH7u3Vj8XFPr82oNt8CQSya+n3VnMpXvL+ez+/6EqKjcvuBKDUX53/JZIsCRw%0A17A/6SF0725/hyv7X43Da+ezPQvYWrE14nUuv5Ol+T9HnK86UMxof21uay5dIjlqtJkwZ3+8iXXz%0ANgEw/cMpWGyWiONWzs7GYBT4FTXiecmJTcMQuvO6X8ClvS/jfznfYECrONeweFGQ4PEOlg7Uemvx%0Aq35dlAGSbSlt8gwSya+l7YT5g83667enfhzRGs5ZeQB7iYOs0ZnsXbq/4RSS3wChIXSgFTua+vXl%0AeBQP6TGdqHM7qPFF7nTd0daRYmcx1Z5qzAYzflVzeViMUXj8bvxK40gOiaQ90iZ+goV/W4yqqERo%0Abqzj9ymsfnc9p1x3MkazsS2WJTkOCCaIjEwfRZGjsElRhvAmrMF+gP2TBjC1z1QAbKbo1l2sRHKU%0AaHWL2W33kLv6IMk9EinPqWxy3I5FuzGajXz/3FKCf6mqigqHqdHSR33iEJqynWRNBrRWUFajFa/i%0Axaf6MAqjbhkHX1874HriLHHM3vIftldsI7c6h/O6XyBjmCXHDa0uzF8//j0I8NR5MZoM+L31caal%0Ae8tZcN+3NOEyZM5Vn3Djx1MbHW9OfKWP+sShob/5tM6nM6Hb2WTEZvDu1ndYVrBUF2WAUemjWFm4%0Akip3JadmnMq0flfy1pb/cOPgm5mYNekYPolEcni0ijCHCqc1LgpUqC2yh41RFZWVs7PDjtkSrTir%0AXLpQT358XMT5Q8W3bG8Fnz+4sN5VokLP07qxd5n0UR/vNPQ3ry/5RRfqKFMUUYYo3Io75Px6vQXV%0Af/d9rW8eSktZcrzRKsIcKpyn334KGxdspWRXediYt6d9hDnajMlixOfWrJ7UXskcWJuvj0npmdRo%0A7oYbhKvm/FJvIQcE3WCW7osTkdCqdDsrdxJljCLffpBPdn0MwE2Db5GWseSE4KgLc87KA1QX1Oou%0Ai67DO5PWK1mzhIF1H23iwNp8rPFWPE6vLsoAedn5GIwCxR/ZDRG6QXggWxPw2lIHKb2SKd5eSlSc%0ABXetp0kf9a4l+/jp+RUA3PjJVEyWdhfGLWkB1Z5q3t8+Vw+FsxijmJA5QVrGkhOGo6pMQeE0hlis%0Ail8hNjWG2NQYACY/Op6t3+xk42fb8Dq9YderCmExqg3D6nYs2k1UXBTdx2Sy84e9ANhLHLhqtD9n%0A3bXaTvzuxTkAzLn6E278SPNRl+4t10VZcnwzLO1k3jvv/WO9DImk1Tgqf/OX7i3njUvm8Z/L3kdV%0AVRzldfo5NcImXFVBLbUljiY3/ZqiqqCWkp1lvHnp++T9UqAf97m0+NTMkzsBkJTVQT/++kVzUfwK%0AC/+25HAfSyKRSI4JR0WYf351tS7ANYV2FF+94s6d/lmj8QPO7Q0CMoamh1nXh2LIRf259LnJDLqg%0Ab8Tzeb8UAlCRWxV2/M1L38dRVkdsan0cq+KP3MRTIpFIjjVHLMxBK/n1i+ZSeaCqyeSR82aMDxur%0A+BWyP9iEKcrEuY+MIyZZE8vLX7mAM+8a3ew9Y1NjSOqeyNZvdkU8n94/tclrhVFgL6235H1umQUm%0AkUjaJ0fkYy7dW86Ce7+tn8RqRnV5UbyNrdBvnvyJ1F5JYbHFVfk1+Fw+3rr8Q33cJ3d8HfFeDTfw%0Afn51VUT3yM0LrsTvVZh9xYeNzgGoDTYU37tuAbd+cXXTDymRSCTHiCOymH96IXwTrefp3RoJXxDF%0Ap+jhbUFOv20U4+8ey/i7x2JN0Eo7GkyRlzLn6k/0136fwp4lORHHqYrKf2f8cFjPEbTggUZWvUQi%0AkRwrDluY9y7fT1V+TVis8LZvdkW0YgGiO1gb1b/o2DeVPmf1oM9ZPThvxnhAE/BIXPjXc/TXOxbt%0ARjSRYv32VR9Tuqc84jkADBAVW1/RTjRI9V45OxsRmPrNS9+X4iyRSI4ZhyXMAgPL/r0GBKT1aVkJ%0AxejkaLqPyQyPLQ5h+X/WNnntTZ9OI7V3sv6+qqAWv6dxkXSAgZP7EJce2/RCFK1uR5CQTF49acVk%0ArffsSGGWSCTHisMS5n4xg/B7FVS/StHWkkOOzxiaroe37fppHxDumshZeYDyvU0XNgodC1pURs/T%0Au0Ucq3gVqg82XXmsKZRA7HX3MV3xOLyHvkAikUhamcPa/EswJTZKCmmK69+/HG+dr1HGX9A1EUxG%0AsSZYsZc4Is4R6sYALSqjz7geEWs1D76oH3nrC6guqG10Log1IQpXtTvs2PZFe7DEWtj9c06jIksS%0AiURyLDgsYd5sz+aBZ+7BXeth28JdFO8oA8BoMTZyMcyd/hk3fjw1LOMvlGAWX7eRGaydu7HRvYwW%0AY5gbA7QNum+f+insWO9x3dm9OIfYlBjG/2ksxTtK8dT52Pz1DjwhrgsAr7vxl8qK/6yL+KxN+cwl%0AEomktTksV4bDb6fbyC70OasHvc/sji1Ri6iI5Pc9VJxwMIsvkig3xY8vREipDvFdd+ybykkXDWDE%0AtJO44MnGdRPiO8Zy8Yu9r0kAABZfSURBVLOTGsU7J/dMbDT2nWs/bfG6JBKJ5GhyxAkmVQW1OCtd%0AjY4HIx/G3z0WaDoMbchF/RlyyQCik2wR51eUcJfC+vlbqMqrbjRu95L6uhihrHirsSVcub+Gzx9c%0ASNH20rDjyVmNhflw08UlEonkaHHERYyGXNSfPmd2B+r9x5c+N7mR+6GpwvWxqTH4fQp1Fc6I86s+%0ANayus8EYObVQGASqoob5o3NWHogcOheo19yQ4VcMZtDkvmHPctHfJjb16BKJRNKqHLEwN6wYF4lD%0ANVcdclF/ugxJp2RXOXuW5VBTUF9M/4zbR4eJelOlQMfdPYbFL65kwf3fcvOCK1FVWPXO+sibeIEp%0A4jvF0bFvil6FLiYpmviOcc0+i0TyW0RRFLZv386aNWtYu3Yta9euZdOmTXg84fs33bp1Izc399gs%0A8gSk1QoSB6Mu+p/bhzXvrge02GCD0UD2x5tYN28TANM/nEK3kV0YedUQ3p72EZ46bYPObDNhL3HQ%0AbVQm+5ZH7kZy6XOTWTkn3CLfsWg3auA+Dd0hQWoKa6kprI/eCC0PKpFI6rn55puZPXv2sV7Gb45W%0Aa/URjLrIy85HGDQ3RDDSIfuDzY3Gr5rzC16XT68At3beRk657mTspZoVbTAb6DKskz7+tD+OYsED%0A31K4pYRup3TRjwdLikaq2xGdGNmf3TAsTyKRaPj9kRO6JK1LqwlzMOqicGuJLsjvXPspC/+2GFVR%0AMUXV50R7XT42f7mdQef31YviR8Va6D4mU7egFa/CwfWF+jXL/rWmvpVUSJr2kIv6c+6j4xh/99iw%0A6IuLn51Ex37a+4uemUjXkRkAEf3iEomkaaKioo71Ek54Wk2YB5/fl9iUaEZdPVQv7Tnp4TPIXX2Q%0AzOGdEaJ+M2/JyysxmI2Munaofqx0dzlvXvo+VS3I5lNVTaFVRSU2NUYP6bvomUkM+l0/AD5/cCE5%0AKw8A8N8nfmTyo+O59YurpShLJM2QlJTEpEmTePTRR/niiy8oKCjgoYceOtbLOuFpNR9z3voCopOj%0AGXLpAKrya9j10z5Wv7MBBJz9wGnMvX4BoMVARyoDCpo1G4ySCHL9B1N495pPw4oe7f1Z80FH8hVH%0Aih6RrguJpGU8//zzx3oJv0laTZhD20AFKc/R6mK8PfVj/di7187n4v+bRHW+thm3cs4vuKpdjL97%0ALKm9k0nskkBedgExyTbspXUsf2OtJspGIOD+6jKsEwfXFzYS3IbNV2XEhUQiOR5oNWGOZKmecv0w%0AfC5NTdd/ugXFp9BvYi8+f3Ch7i8Obb4a6nvev/YgAHuW5moDQ/YkiraVRix6v/zfTVeuk0gkkvZK%0Aq/mYY1NjSO2dTGrvZN2fO/SSgQgjZH+4CcWnMP3DKVQX1IQlfYRmB0byPYf6pvVrIoTFNYzykEgk%0A7RPV66X0wovJ79GL/IxMfHl5x3pJx5xWs5ibIjRULmdNPpV51QgBaoT8kUi+50hhcA3FOpKlLZFI%0A2h7V66X00v9v786jo6ryBI5/X6VS2VkEEiBKhEaCCza0URAVFLVtcUVQQG1Ex13BpZ2WnlEHT2uL%0ANq2Ore063S404IKI0rSjgA4iiyYiu8SAAcxKAmRPrW/+uFX16lVVtqYqecHf55w69d599y3FgR/3%0A/N5dpuDetCn4jzxrwzrsx6kVjXyNjZSP/AV6gzHDZMWYsRH1Qq9XNflqXFu3gssFDge4XFHrdmdx%0AazFHE95V7usF3+Dz6GgtLCsVbQmqEZfnRnSFCx8+Ha2l3dIKKUKI9vM1NlL35+fbf4KmkXz+BOzD%0AhkU/brOROGokJCa2/3oXnE/yhRcAkHT22e1/lm6k01rMznpXsKtcYJJ9n1fH6/KQeUIfyneoiYVC%0Ap9vMyu1HVq4KwMMmDDFdL3w/VLSW9t+mvyOLrwrRTsGW6bZt4HQaLVKbjYQBA+BgK8u4hdDsdnrc%0Aew84ndTt2hVx3JacTN+/L6Bi7Nl4S0pMxwItZ4C+7y8hafQZaHY7GbNnUfvkUzQD9kHH4eTo02kt%0A5uWPrAx2lQtoqm7G6/YFgzLAmzcsOeJ7RWtpB2a7E0K0zdfUhGvzZnCqsFcxZizOjV9hS04mdcrk%0ADl9PDxlBWDFmrCmPrNntJAwcEO20oKqrJv+kcs+d1mKuP9AAurmrXDSxmKC+tZa2EKJtmsNB4pjR%0AuNdvgHYOy241nxzlpX0oX1PkFMJAMIf8U9NpgXnc3aOp3nMYMLrKjbg8lxPGqcAp020KYR225GQy%0A315MWd4Z+MrUVAhVU6eB243vmikR9b0lJZQePwStX7+IY+6iIrz79pnrV1UFX9Y1rVqNZ9u26A+S%0AmhoRmN1FRfgOqTER3h/Vy31P8V40h4OErKyO/VCL6rTAPHj0IAaPHgRA3vRTI47L4A8hrM2Rl4dr%0A/froKQV/i1g/cICEnBy8e40ZISvHR/7brrrsCtB1sjas4+CMG1q+aWNjRFHo9ZpXrgKgetp0sNnA%0A54vooREtX57Qv3/0HLpFdGqvDCFE9+EuKgKPsUScdoxa6af5fz+JqKuF9KoIDcpNK1czcO8PpP/m%0Afmx9+wbLE0eqHlMV54yPem+tVy9/ReO67sJCALJL9ps+A/f+QI8Hf0vKxIlRr6V7PHjLysCtJkTz%0AlpZFLbMSCcxCiKgqx5+H74DxYt65Tk1v4MjLi6irOUJmnHM4zMfsdnrefx/JF//KKEtTi2w4xp4Z%0A9d76YZX2JKR/8+H7H8BbURExIMVbVkbG7FnYhwyOei0tMZG0X1+PfcgQU1nqtdODz2q1l4udPsBE%0ACNF9LGioZ2GjPzgeqFBfnsiXceV1tUxs8K9A5EgCl5MRiQ6e31uMt6KChKwsGt9aEKzvWrsWAHtO%0ADi6Anj2hJnJNz1C+qipqn5hHr/l/JPmC87FlZdG8YoVqdbvdwXRKYD+QntDsdtLvuJ3a518AVBDO%0A2rCOjFl307hocUQ3PSuQFrMQIqrskv003XsPW9xu06essjKirsvrNeo01LPF7Wa3x03Dq69R+8Q8%0AADJmzwrWT/F3udNsKgQl5gwyXS9pwgRA9eoITVv0fvaZYF/mhMA5/nREcPhwtPSEpmELpEcCRe3o%0AptdVpMUshIibxNGj6fmHxykZOgyajIWX3btUvtjXQis52sCRaN3xAGw5g/Dt3afy0YEgHcZTXExC%0A7974/K3j6pk34dmzG1xG/dCeIl1NWsxCiLhxb9xIw7JlpqAM4Nmq5sxpWvoBAN7qg6bjvii9MVoa%0A3m3LyPDfzByUvSEt+8rx5+EO6ZKnu5ymoAxQ9/Qz7fhFnUMCsxCiRXPnzkXXddPnx4HHmj4H77mX%0Ayiuu5MeBx9K8YWOw/L2+mQDUPjKX7JL9OE5XLw37vr+EAd+bh2f7wvK8Te+8C5jTEYHh3SkXmcc6%0A6M6WB6DobjcVl14eUZ6YmxtZ2ePBW1HRyp9G55HALITokPDuar2ffSbq8UBOOWv1ysiL2GwkjTtH%0AzbvRCk9JSUSw1MOm+fV+/33wmqby8nI8paX4yssjrtv8z49JueZqU5lzzRfBfHhXk8AshDgiTatW%0AB3PFroJvcG3b3uY5WkICekMjXn/Q7P3Si8EWdajDs2a3P1iGBezauY9S+/gTpM/4NfahQyOquwoK%0AgtuBl4zh/8l0FQnMQogjcnDGDXgKVau19vHHOXjrbabjusdD+bhzcX2dD6juak2ffa66vIX1lABU%0ADjlBTQ3c9/0lpmCphne3v7+xLTWFjNmzsPU27pMyWfUIcZxqjED2VlW1+5qdQXplCCGOSHZJZKAM%0Anc/Cs3cf3t27TcdrHnqYAV9toP7NtyLOdeTlgc+Hp6go4li04d3JEyeSOm0qtY89FvwPAqDP4kUk%0ADjuhxecOvHgEqHtqPvZnn7bMXBvSYhZCxFzl+PNo8A8oOXjd9aRePcXUj7nfkndpWrUa3almlWv8%0AaDneCtWLQuuRge5fby48xxzIX/ffYfSwaF6xwtRqD6ieNp3aJ+apVnalMYLREzahEoBzzRrL5JcB%0AND3amk4tyMvL0/Pz8+P4OEKIo1Xtk09R99yfAZXTDZ0IvzWpV0+JyP06N2+heupU9Do12rDnk/Oo%0AeXCOqY6tTx989fXBOaUjrjt1Kr7qappXroz7JEaaphXouh6ZRG+BpDKEEF0i8/8+o+G1/6HhrQXB%0AtEMglRAI4i0FzKqJl5j2m5Z+YEqp6B4P9X95Eff2HTQtXx71/o1vv439xOEx/EWxI6kMIUTcuYuK%0A8BQXB/ddm741pTsCaYdA3WB+unhv1L7FgZSGzd/dLm2meerQwLDtwMRGtuxstGS1mlHvl14Mnp9y%0A4YWx/aExIi1mIUTchb+0O3THnVFTFOF1q6dNJ3nSlTg/+TS4knZg/b+O6LfkXQ5MmoxeZq3pPVsi%0AgVkIEXfRem60t66vuZmDN96E5/siNYeyX/1bC9D9Q7eda75A69GDlPHj2n2f8Ja5lVZAkVSGEMLS%0AbMnJ9F20kIRjs03lNXN+h+4f2NK4cCGHbrnVdDw88Ophaxe2lEqxAmkxCyG6pbZa4eEpkcBqKIHW%0AdUda8Z1NArMQ4qgUGnhLso8Lzj7XuHAhTcuWkVL4XVc9WpskMAshLC98Pg4tLQ3HKSe3+3wrt46j%0AkQEmQgjLK8k292VOyMmh/7q1XfQ0HScDTIQQR53u1uI9UtIrQwghLEYCsxBCWIwEZiGEsBgJzEII%0AYTESmIUQwmIkMAshhMVIYBZCCIuRwCyEEBYjgVkIISxGArMQQliMBGYhhLAYmStDxM9crfXjt22C%0AASM751mE6EYkMIvYaisYn/kbGHOv2k4PWcYn/DwJ2uInTAKziL+kHpB7OWxZAOv/pD6tue5jyGxh%0Art3wAD55MYyYGpvnFMIiJMcsYs+eDGlZMPB0te9xqqAc7swH4J49xr4jQ523c0nr18+9Am7+Sn1y%0AL4vdcwthEdJiFrGn2cHdCKVfq32vM3q9jc+Cq1Zt21NUQO+VA9+8Cv1/DmfcZdQNbSnvWgaFH0Hf%0A4XDL1/H5DUJ0IWkxi9gJBE93PbjqjPIhFxjbNjtk+Fc79nmg4BW17WmCxgNQ8pXa/+Gz1u+l++DA%0ADvhgZkweXQgrkcAsYmvYZTBjNYy62Sjbs9LY9nmgrqTt6+SMi17uSIfhk+Cm9Wq/cuu//qxCWJSk%0AMkRsFS5XaQab/6+WI0OlNXSv2u81GA7/AH2GQ3ULqxSn94fTbol+zFUP3y2FYn+LOnNEbJ9fCAuQ%0AFrOInXGPQN9cFZR9HlXmqjOCMqigDC0H5dRMqC+HTX81l098wbzffFgF/UlvxubZhbAQCcwidiY8%0ACnfvhDk1Rtnx58JJLXRnO/EquG8/jP8vtT8wDxor1XbFFqNeaYFqdQOkhvR9PnEyJCbH7PGFsApJ%0AZYjYKC1QL+yGXQKF/zDKiz8317viDeg9GF4fB98tg31rVRc5gMHnQ2m+2s461TjncDF8+ZTabqww%0AygN9nWVwijjKSGAWseFIh60L4bOH1Taol3TfLTXXW3aDsa17oaFSfQC+fNI4lj3a2M48BdL6qV4b%0Aobb8Hc56QG1f9DScdLXaDh1RKEQ3pOm63u7KeXl5en5+fhwfRxw15mqQ1BOcNS3Xmf4PWHSJsW9P%0AUd3mQoW3fsNbx+fPg1Vz1L0caWqE4cXPQULikf8GIWJE07QCXdfz2ltfWswiPs56ELwuKN8Umc4A%0AQIPNr5uLQoPy9OWw6FJ4eVTL9+g1BPJuh6QMWHGX+k8g/yX1kXSG6Mbk5Z+Ij1E3qoC839/f2B72%0Akk6zwY53Wz5/0aVt36OhSn2fcWfkMZ+7XY8phBVJi1nEXuBFYPkmo8zTbK4T2oWuLSl9oKlapSvc%0AjTDgNJWXPrwHXhsNv7g58hyfR14Kim5LWswi9gIvAgEICY5p/dV33h3tv1ZCkgrKoFIVPjeUbIBR%0AM1VZXWnIvTAGtuzfoL4velp1ybtvf8sz1glhMRKYRez1zYXbv1HbjnSw+V/ENZQDmsoBt1diqrGd%0AOUKNHARY/7T6Pmao+V72FLUdSJN8/qhqVX/x+L/0U4ToChKYRfxMfAFu+gLO9Q8gScsEWwIQpSdQ%0A+oDo12g+ZGxXbjVGDjYfhpRj4MY1KnUyfJIaBXisv5tdfYW6v7NGtarzX4LfO6Ds25j9PCHiRQKz%0AiJ8z7lTTd465T+0Pv9IYqh0wzD+fcn1Zx68/YxUkpasBKCUb4b1psO9LdSy9v/FS8IJ56nvEtZLO%0AEN2CvPwT8RE6EjD/ZVWWlmkc1xJUN7fdn3T82r1/BjM+hR7HRh7T/DntH9cZL/9WzlHfNfs6fi8h%0AuoC0mEV8BF4AvnASbPxvVbbmMfWtJajv5sNRJtG3E/Wv5fCrjO1Du2HpDGM/8xQ1rFuzqZz06XdF%0Ang9q+LekM0Q3ICP/RHzN1czDpXcuhY9nm+toCTD0V+B1w2k3q5nlij5WL/sqt0JybzX4REsAd0Pk%0APaJ1gwu0lpN6gLMWxv4W1j0FI66DK/8mIwNFp5KRf8J6Pn8U1s1Xw6VHzlRlY+6HDf6eFQkOtQyV%0AzwdLrocE/1/Lyu3q254MI29ULeL1843rjrhO5Y/TsyL7LJ/9O1j7BLj8gXzdH9V3zd64/EQhYkkC%0As4iviS/AoLPUBPqrH4Lq71V5ICgn9YDrP4HNb0D+i6qP864P1UASexIccwJUbjEHca9LbRcuV3nq%0Ai59T++ETGdkSYftiqC4EdOiZo9IZBa+Y1xMUwmIklSE6h6sR/pCmRvE5a1QOuk+u6k1xpCY+Dyvu%0Ajiy/Zgkc2gOf/rvaH3kTfPtXOO1WuOzlI7+vEO3U0VSGvPwT8VNaAF/OhwM74eu/qLLzHoVH3DDn%0AEPzyT0bdQLe5oRfD9A/hnP80l7emYkvkCicA70yG1Q+rljJA80H1HTrXsxAWJKkMET/hczSffpda%0ApeTL+aob3a5lRt3C5er7h1VQVqDyzaDWD2xLyjGqz/KKkPRERjbYU1Uf59oS9eJw7xfqGU67LWY/%0AUYh4kFSG6FxVu+C96VC1UwXrk6eqIdw541TrtvAjGHapCtQnXwPb32n9ev1OgsteUbPYOWthze+N%0AY+n9YfZucKS2fL4QnUB6ZQhrC51HI9yUxSoPHRiI0lZQBjiwA+rKVMu8aifYHDDoHChepRZ1/WAm%0AXNOO6whhIRKYRdcKjBDsdTx8+7oqazpoHB9yIez5tPVr1JXC5a+a1xwsXqWOVW6Nx1MLEVcSmEXX%0ACuShD2wHn1flgvethVOuhW0L2w7KoILv0Ivgq+dh5YOQmKZe+NXsVYNUhOhmJDCLrtVaaqPncSod%0AsfmN1q/RXKOuc+mL8PZkcNWBq14F5Ulvxv6ZhYgzCczCukbdqF4U2hLVBPn25MiVUACSe6rvEy6G%0Ahxo79xmFiAPpxyysqbQAdn0E5/wH/OyXqswW0o4ITIQE0F+WixJHF2kxC2sy5Z49ap4Mn3+dwIxs%0AaKwCr1d1l5N+yeIoIy1mYU2B3PMdWyDr52qODHsSHDcWrv8nTPBPIXr6ncakR0IcJTo0wETTtAOA%0ATM8lusSpWSQtmsyQIb1JaXLj/aiQQ//2Ifs8vq5+MiHalKPrer/2Vu5QYBZCCBF/ksoQQgiLkcAs%0AhBAWI4FZCCEsRgKzEEJYjARmIYSwGAnMQghhMRKYhRDCYiQwCyGExUhgFkIIi/l/HOhO8eQdfKUA%0AAAAASUVORK5CYII=)

## Reference

NetVLAD & Triplet loss code  [[code]](https://github.com/lyakaap/NetVLAD-pytorch)
NetVLAD papaer [[Paper]](https://arxiv.org/abs/1511.07247)
Triplet loss paper [[Paper]](https://arxiv.org/abs/1503.03832)
