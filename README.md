# KTH-DevOps-EssayWordCounter
This repository contains a Github Actions yml file which checks the word count in pdf files in pull requests.

Will **fail** if the word count is *outside* of allowed interval.

Will **pass** if the word count is *inside* of allowed interval.

## How to use

Put the ```essay_word_counter.yml``` file in your ```.github/workflows``` folder in your repo and it should be good to go

The environment variables ```LOWER_LIMIT``` and ```UPPER_LIMIT``` can be changed to fit your needs.