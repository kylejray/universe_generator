# example site
This repository is just really for showing how to do some webstie suff. Coincidentally it contains some really cutting edge code that many people are going to want to use! See below if you dare!




    def calculate_universe(x):

    does mindblowing calculations on current state of the universe and returns the next state of the universe, I cant even begin to describe the comlexities and nuances.

    Parameters
    ----------
    x: number or array of numbers
        the current state of the universe, must be able to have 1 added to it for... reasons
    
    Returns
    -------
    x: same type as input
        the next state of the universe, will return 'invalid input' if the calculation fails.

    
    try:
        x += 1
        return x
    except:
        print('invalid input')