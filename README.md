<p align="center">
    <a href="https://myadoptimizer.com/">
        <img src="https://myadoptimizer.com/img/logo-blk.svg" alt="Logo" height="80">
    </a>
    <h3 align="center">MyAdOptimizer.com Dashboard Doc</h3>
    <p align="center">
        Learn how to use the <strong>MyAdOptimizer.com Dashboard</strong> and all its functions by following these steps
        <br />
        <a href="https://myadoptimizer.com">View Site</a>
        ·
        <a href="https://myadoptimizer.com/contact">Report Bug</a>
    </p>
</p>

## Table of Contents

* [General](#general)
* [Reports](#reports)
    * [Admin Listings](#admin-listings)
    * [Admin Report](#admin-report)
    * [Advertiser Report](#advertiser-report)
    * [Budget Report](#budget-report)
    * [Consumer Report](#consumer-report)
    * [Data Center](#data-center)
    * [LT Report](#lt-report)
    * [Lead Report](#lead-report)
    * [Publisher Report](#publisher-report)
* [Categories](#categories)
    * [Tabs](#tabs)
    * [Variables](#variables)
        * [Campaign Controls](#campaign-controls)
        * [Campaign Ad Copy](#campaign-ad-copy)
            * Auto Insurance
            * Home Insurance
            * Education
            * Medicare
            * Mortgage Refinance
        * [Consumer Constraints](#consumer-constraints)
            * Auto Insurance Constraints 
            * Home Insurance Constraints
            * Education Constraints
            * Medicare Constraints
            * Purchase Constraints
            * Mortgage Refinance Constraints
        * [Geo Constraints](#geo-constraints)
        * [Location Constraints](#location-constraints)
        * [Scheduling](#scheduling)
        * [Collaborator](#collaborator)

## General

### Welcome to MAO Dashboard

<p>
Here you can see everything related to your advertising campaigns, status, information and all the settings that the system can offer you. There are different categories, which are all organized in the sidenav. You can see management tools, settings and reports.
</p>

## Reports

<p>Here you will find all the reports with different types of data related to your advertising campaigns, each report has unique parameters to select and you can export the report based on what you want to see.</p>

<img src="https://myadoptimizer.github.io/images/report-0.png">

<p>Below each report with its fields.</p>

### Admin Listings

You can select different parameters, when selecting the vertical, different related options appear, select the render mode and give it run to generate the report.

Here are all the campaigns you have.

* Example
    * Live
        * <img src="https://myadoptimizer.github.io/images/example-1.png">
        * `Live generates impressions and clicks in DB`
    * Test
        * <img src="https://myadoptimizer.github.io/images/example-2.png">
        * `Test does not save this data in the DB`

### Admin Report

You have different edges, you can select the date range and group the data depending on the options, you can group by field or by specific data.

You can see detailed data from private exchanges.

Example

<img src="https://myadoptimizer.github.io/images/example-3.png">

### Advertiser Report

This is a specific report for the advertiser, you will select specific parameters to see a consolidated of all the campaigns of all the private echanges.

You can select different options to customize each event.

Example

<img src="https://myadoptimizer.github.io/images/example-4.png">

### Budget  Report

Here you can put budgets to the advertiser, if it has 0 they are unlimited.

You can see what you have spent per month, field rate, remaining budget, active and save status. Depending on your selection is, you can group the report by campaigning to see more detailed data.

Example

<img src="https://myadoptimizer.github.io/images/example-5.png">

### Data Center

Here you can find all the information related to the clicks of the campaigns, see details depending on your selection, it is useful data to identify specific events.

The result is a .txt file with all the raw data.

Example

<img src="https://myadoptimizer.github.io/images/example-6.png">

### Lead Report

Here you can see leads that were converted from clicks, the vertical Education specifically, has this parameter very marked, you can select different options to see the report according to your needs.

Example

<img src="https://myadoptimizer.github.io/images/example-7.png">

### Publisher Report

It is similar to the admin report, but this is at the ad network level, it has useful data to identify the selected parameters.

It is a quick way to show the report with data of interest.

Example

<img src="https://myadoptimizer.github.io/images/example-8.png">

## Categories

Now let's focus on the different categories for your ad campaign.

<img src="https://myadoptimizer.github.io/images/mao-0.png">

<p>Each option has different customization parameters for the ad campaigns.</p>

## Tabs

<p>In the first view we can find different tabs with specific parameters and configurations, each of them varies depending on the category, here you can fill in the specific information of your ads campaigns, name, logo, date range, budget and other options that without a doubt will be very useful to choose your audience.</p>

<img src="https://myadoptimizer.github.io/images/mao-1.png">

Part of the global options or fields will be assigned to you automatically, but you can configure your advertiser name, contact info and much more, you have the options new, clone and save.

<img src="https://myadoptimizer.github.io/images/mao-1.2.png">

### Options available in tabs

* Campaign Controls
* Campaign Ad Copy
* Consumer Constraints
* Geo Constraints
* Location Constraints (Education only)
* Scheduling (CST Time)
* Collaborator

## Variables

### Campaign Controls

<img src="https://myadoptimizer.github.io/images/mao-1.1.png">

Here you can find global settings about the campaign and tab settings, the advertiser ID and campaign ID will be assigned automatically, you can add the advertiser name, vertical. campaign name. bid. monthly budget, daily budget, margin and the weighting score. You can select the state of the campaign, if it is enabled, auto-reactivate and select the timezone.

### Campaign Ad Copy

<img src="https://myadoptimizer.github.io/images/mao-3.png">

Here you can put the link of your campaign, select the logo of the campaign that preferably we recommend that it be 500x240px, you can add the display URL, headline, bullet 1, bullet 2, bullet 3 and bullet 4, each one adapts to your needs.

You can see a complete list of constraints for each category in our documentation for server side or client side.

* Auto Insurance
    * [Server Side](https://gist.github.com/MyAdOptimizer/c27c9b6f76993afbf21697e5e1a9c369)
    * [Client Side](https://gist.github.com/MyAdOptimizer/06330d95eddd39e405ac0e4363224a3a)
    * Example
        <img src="https://myadoptimizer.github.io/images/variable-1.png">
* Home Insurance
    * [Server Side](https://gist.github.com/MyAdOptimizer/541dfd1d8bc4faf366c10f3b73110c04)
    * [Client Side](https://gist.github.com/MyAdOptimizer/78d480870e971c2c1dcb80965a0a5955)
    * Example
        <img src="https://myadoptimizer.github.io/images/variable-3.png">
* Education
    * [Server Side](https://gist.github.com/MyAdOptimizer/2ea38e8c81dc079f4d63c13f24f2a755)
    * [Client Side](https://gist.github.com/MyAdOptimizer/2e757af083ee93d50f2d67c460c61a89)
    * Example
        <img src="https://myadoptimizer.github.io/images/variable-2.png">
* Medicare
    * [Server Side](https://gist.github.com/MyAdOptimizer/6d9c404da0e4c7c37d0db96351157c49)
    * [Client Side](https://gist.github.com/MyAdOptimizer/d47014ce93c8bd8290312e3a6be0d66a)
    * Example
        <img src="https://myadoptimizer.github.io/images/variable-4.png">
* Mortgage Refinance
    * [Server Side](https://gist.github.com/MyAdOptimizer/1e1b43377225b4413a7e64864c026286)
    * [Client Side](https://gist.github.com/MyAdOptimizer/307e26de3051c7f13968a04d5d111d90)
    * Example
        <img src="https://myadoptimizer.github.io/images/variable-6.png">

You can add the variables to the URL depending the category, each one has different parameters, customize your URL to choose your right audience.

### Consumer Constraints

We have a great variety of options to configure the consumer constraints, each of the categories contains different options that you can select.

Here are all the parameters for each category.

### Auto Insurance

<img src="https://myadoptimizer.github.io/images/cons-1.png">

* [Auto Insurance Constraints](https://gist.github.com/MyAdOptimizer/027de92e05ec9dff6464ee419d32988a)

### Home Insurance

<img src="https://myadoptimizer.github.io/images/cons-3.png">

* [Home Insurance Constraints](https://gist.github.com/MyAdOptimizer/514dce5aba86409291674af1cabecd53)

### Education

<img src="https://myadoptimizer.github.io/images/cons-2.png">

* [Education Constraints](https://gist.github.com/MyAdOptimizer/855ebcf8464c8469d3d0abc2b1b409e6)

### Medicare

<img src="https://myadoptimizer.github.io/images/cons-4.png">

* [Medicare Constraints](https://gist.github.com/MyAdOptimizer/0bde67d2fa93d44e0e69b606d9621208)

### Purchase

<img src="https://myadoptimizer.github.io/images/cons-5.png">

* [Purchase Constraints](https://gist.github.com/MyAdOptimizer/d30797021001431d2f8eae9f81853cb6)

### Mortgage Refinance

<img src="https://myadoptimizer.github.io/images/cons-6.png">

* [Mortgage Refinance Constraints](https://gist.github.com/MyAdOptimizer/aa34f13dae6cf842b133c06bae9ee8ec)

### Geo Constraints

<img src="https://myadoptimizer.github.io/images/mao-5.png">

In the geo constraints you can select the states in which you want your campaign to be active, also on one side you can put the zip codes that you want to be excluded or ignored separated by commas and below you can add the zip codes where you want your campaign to be active, it will only be shown in the ones you add here.

### Location Constraints

<img src="https://myadoptimizer.github.io/images/mao-8.png">

This option is only available for Education, you can select the location of the school, if it is on-line or a campus, you can select the campus info, city, state and zip code.

### Scheduling

<img src="https://myadoptimizer.github.io/images/mao-6.png">

You can put the range of hours in which you want your campaign to be active, here we show an example where most of the calendar is selected, by clicking on the square you can activate or deactivate it.

### Collaborator

<img src="https://myadoptimizer.github.io/images/mao-7.png">

Here you can add collaborators and you can send them an invite to their email, they will have access to this campaign, you can edit their information or delete a collaborator.

<p>
That's it, <strong>MyAdOptimizer.com Dashboard</strong> is the best option for configuring your ad campaigns, choose your specific audience and see effective results.
</p>
