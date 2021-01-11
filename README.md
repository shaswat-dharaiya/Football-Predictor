# Football Predictor

By using data from this [link](https://www.football-data.co.uk/englandm.php) we use [Poisson probability distribution](https://en.wikipedia.org/wiki/Poisson_distribution) to calculate probability of teams' winning chances. In order to implement it we use [poisson](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.poisson.html) from scipy library.

$$ f(k) = \exp(-\mu) \frac{\mu^k}{k!} $$

Steps to build the predictor are implemented in [PremierLeague.ipynb](https://github.com/shaswat-dharaiya/Football-Predictor/blob/main/PremierLeague.ipynb) 
