# Framework Test

[![CI Status](https://github.com/wp-content-framework/0-framework-test/workflows/CI/badge.svg)](https://github.com/wp-content-framework/0-framework-test/actions)
[![codecov](https://codecov.io/gh/wp-content-framework/0-framework-test/branch/master/graph/badge.svg)](https://codecov.io/gh/wp-content-framework/0-framework-test)
[![CodeFactor](https://www.codefactor.io/repository/github/wp-content-framework/0-framework-test/badge)](https://www.codefactor.io/repository/github/wp-content-framework/0-framework-test)
[![License: GPL v2+](https://img.shields.io/badge/License-GPL%20v2%2B-blue.svg)](http://www.gnu.org/licenses/gpl-2.0.html)
[![PHP: >=5.6](https://img.shields.io/badge/PHP-%3E%3D5.6-orange.svg)](http://php.net/)
[![WordPress: >=5.4](https://img.shields.io/badge/WordPress-%3E%3D5.4-brightgreen.svg)](https://wordpress.org/)

WP Content Framework テスト用

## Table of Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
<details>
<summary>Details</summary>

- [要件](#%E8%A6%81%E4%BB%B6)
- [構成](#%E6%A7%8B%E6%88%90)
- [Dependency](#dependency)
- [Author](#author)
- [プラグイン作成用フレームワーク](#%E3%83%97%E3%83%A9%E3%82%B0%E3%82%A4%E3%83%B3%E4%BD%9C%E6%88%90%E7%94%A8%E3%83%95%E3%83%AC%E3%83%BC%E3%83%A0%E3%83%AF%E3%83%BC%E3%82%AF)

</details>
<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## 要件
- PHP 5.6 以上
- WordPress 5.4 以上

## 構成
- code check
  - PHP
    - PHP_CodeSniffer
    - PHPMD
  - JavaScript
    - ESLint
- test
  - PHP
    - PHPUnit
      - PHP v5.6 - v7.2
      - WordPress latest
  - JavaScript
    - Jest
- coverage
  - codecov
- deploy
  - GitHub releases

## Dependency
[Scripts for Travis CI](https://github.com/wp-content-framework/travis-ci)

## Author
[GitHub (Technote)](https://github.com/technote-space)  
[Blog](https://technote.space)

## プラグイン作成用フレームワーク
[WP Content Framework](https://github.com/wp-content-framework/core)
