# TrackMoney

## Description
TrackMoney is an app to track the daily or monthly use of your money

## Models
    .   User (Authorization and Authentication must be implemented)
    .   Project
    .   ProjectType
    .   Item
    .   ItemType
    .   ItemCategory
    .   ItemSubCategory
    .   ProjectReport

## Relationship
    .   User - Project (1 : M)
    .   Project - ItemCategory (1 : M)
    .   ItemCategory - ItemSubCategory (1 : M)
    .   ItemSubCategory - Item (1 : M)


