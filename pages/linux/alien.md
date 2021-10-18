 # Alien
> Converts different instalation packages to multiple other formats. More information: https://www.unixmen.com/convert-deb-files-to-rpm-and-rpm-to-deb-using-alien-2/

- Converts the installation file to [d]ebian linux format [deb]:

`alien -d {{file}}`
`alien --to-deb {{file}}`

- Converts the installation file to [r]ed hat linux format [rpm]:

`alien -r {{file}`
`alien --to-rpm {{file}}`

- Converts the installation file to Stampede [SLP] format:

`alien --to-slp {{file}}`

- Converts the installation file to a Slackware [t]gz installation file [tgz]:

`alien -t {{file}}`
`alien --to-tgz {{file}}`

- [I]nstalls a package as soon as it finishes converting:

`alien {{options}} {{file}} -i`
