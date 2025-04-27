## About the Project

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#cucumber-practice">Cucumber Practice</a>
      <ul>
        <li><a href="#gherkin-language">Gherkin Language</a></li>
      </ul>
    </li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

### Built With

This project was build with the following technologies:

[![Cucumber][cucumber]][cucumber-url]
[![Node][node]][node-url]
[![NPM][npm]][npm-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Getting Started

Before anything else, you need to follow some instructions on setting up your project locally.

### Prerequisites

To execute next steps, you need to ensure npm is installed in your environment.
```bash
npm install npm@latest -g
```

### Installation

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Testing Structure

Behavior driven development (BDD) / AAA Standard (Act, Arrange, Assert)
- Given (Act): condition.
- When (Arrange): action.
- Then (Assert): assertion.

### Gherkin Language

```gherkin
Feature: Description
As an <actor>
I want to <do something>
In order to <achieve some goal>

  Scenario: Description 1
    Given <a condition>
      And <another condition>
    When <actor does something>
    Then <some output is given>
  
  Scenario: Description 2
    Given <a condition>
      And <another condition>
    When <actor does something>
    Then <some output is given>
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

To found more information about Cucumber, visit: [cucumber.io/docs](https://cucumber.io/docs).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[cucumber]: https://img.shields.io/badge/Cucumber-43B02A?style=for-the-badge&logo=cucumber&logoColor=white
[cucumber-url]: https://cucumber.io/
[node]: https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white
[node-url]: https://nodejs.org/
[npm]: https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white
[npm-url]: https://www.npmjs.com/
