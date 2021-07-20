cmake_minimum_required(VERSION 3.5)
project(heera-icon-theme)

include(FeatureSummary)

install(DIRECTORY heera-dark DESTINATION /usr/share/icons)
install(DIRECTORY heera-light DESTINATION /usr/share/icons)
