# cat_and_dog_years
#about cat and dog years dependind from human years


def human_years_cat_years_dog_years(human_years):
    return [human_years,cat_Years (human_years),dog_Years (human_years)]


def cat_Years (human_years):
    human_years >= 1
    catY = 0
    if human_years == 1:
        catY = 15
    if human_years == 2:
        catY = 15 + 9
    if human_years >= 3:
        human_years-=2
        catY = (15 + 9) + (human_years*4)
    return catY


def dog_Years (human_years):
    human_years >= 1
    dogY = 0
    if human_years == 1:
        dogY = 15
    if human_years == 2:
        dogY = 15 + 9
    if human_years >= 3:
        human_years-=2
        dogY = (15 + 9) + (human_years*5)
    return dogY
