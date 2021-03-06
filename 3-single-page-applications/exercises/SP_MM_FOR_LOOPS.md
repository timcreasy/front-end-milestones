# Very Large Array - Muscle Memory Exercise

## Prerequisite
Students should have music history 3 completed before attempting this muscle memory exercise.

## Setup

1. Create a branch in your `musichistory` repository named `MM-arrays`.
1. Switch to that branch.

## Requirements

Use JavaScript arrays and innerHTML to show the music you love.

Students must use JavaScript to create arrays, modify them (using only the following methods: join, push, reverse, sort or unshift), and output lists to the DOM.

1. Each student must create four separate arrays, one for songs, one for albums, one for artists and one for genres.
1. The song array should be initialized with 10 songs.
1. Each subsequent array should hold the corresponding data (artist, album and genre).
1. A genre input field should be added to the add song form.
1. An output should be added on the add song page, under the form, for each of the sections (songs, artists, albums & genres).
1. Add 10 more songs from the add song form.
    + Each song should be added to the end of the song array.
    + Each artist should be added to the beginning of the artist array.
    + Each album should be added to the end of the album array.
    + Each genre should be added to the beginning of the genre array.
1. For each output element send the corresponding data as follows:
    + Songs should output vertically down the page descending alphabetically.
    + Artists should output exactly as they were added horizontally, separated by ` : `.
    + Albums should output verticallly down the page ascending alphabetically.
    + Genres should output horizontally, separated by commas alphabetically.


## Merging your branch

After you've got all of the requirements completed, follow these steps.

1. In your `musichistory` directory, enter the command `git checkout master`. This switches you back to the master branch.
1. `git merge -X theirs version2`
1. If you see a vim screen with a default message in it just `:x` to save and exit.

Your branch is now merged into the master branch and you can push the master branch up to Github with `git push origin master`.