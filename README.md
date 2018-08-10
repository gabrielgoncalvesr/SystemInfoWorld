# Project-TCC
Repositório para colocar os arquivos do projeto que será implementado no TCC.
Esse é um sistema criado para gerenciamento de usuários no FTP, além de oferecer uma página de cadastro e login, oferece também o gerenciamento do sistemas por um administrador.
<p align="center">
  <a href="https://cakephp.org/" target="_blank" >
    <img alt="CakePHP" src="https://cakephp.org/v2/img/logos/CakePHP_Logo.svg" width="400" />
  </a>
</p>
<p align="center">
    <a href="LICENSE" target="_blank">
        <img alt="Software License" src="https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square">
    </a>
    <a href="https://travis-ci.org/cakephp/cakephp" target="_blank">
        <img alt="Build Status" src="https://img.shields.io/travis/cakephp/cakephp/master.svg?style=flat-square">
    </a>
    <a href="https://codecov.io/github/cakephp/cakephp" target="_blank">
        <img alt="Coverage Status" src="https://img.shields.io/codecov/c/github/cakephp/cakephp.svg?style=flat-square">
    </a>
    <a href="https://squizlabs.github.io/PHP_CodeSniffer/analysis/cakephp/cakephp/" target="_blank">
        <img alt="Code Consistency" src="https://squizlabs.github.io/PHP_CodeSniffer/analysis/cakephp/cakephp/grade.svg">
    </a>
    <a href="https://packagist.org/packages/cakephp/cakephp" target="_blank">
        <img alt="Total Downloads" src="https://img.shields.io/packagist/dt/cakephp/cakephp.svg?style=flat-square">
    </a>
    <a href="https://packagist.org/packages/cakephp/cakephp" target="_blank">
        <img alt="Latest Stable Version" src="https://img.shields.io/packagist/v/cakephp/cakephp.svg?style=flat-square&label=stable">
    </a>
</p>

[CakePHP](https://cakephp.org) is a rapid development framework for PHP which
uses commonly known design patterns like Associative Data
Mapping, Front Controller, and MVC.  Our primary goal is to provide a structured
framework that enables PHP users at all levels to rapidly develop robust web
applications, without any loss to flexibility.

## Installing CakePHP via Composer

You can install CakePHP into your project using
[Composer](https://getcomposer.org).  If you're starting a new project, we
recommend using the [app skeleton](https://github.com/cakephp/app) as
a starting point. For existing applications you can run the following:

``` bash
$ composer require cakephp/cakephp:"~3.6"
```

## Running Tests

Assuming you have PHPUnit installed system wide using one of the methods stated
[here](https://phpunit.de/manual/current/en/installation.html), you can run the
tests for CakePHP by doing the following:

1. Copy `phpunit.xml.dist` to `phpunit.xml`.
2. Add the relevant database credentials to your `phpunit.xml` if you want to run tests against
   a non-SQLite datasource.
3. Run `phpunit`.

## Site

<a href="https://imgur.com/sHanpBr"><img src="https://i.imgur.com/sHanpBr.png" title="source: imgur.com" /></a>

# Security

If you’ve found a security issue in CakePHP, please use the following procedure instead of the normal bug reporting system. Instead of using the bug tracker, mailing list or IRC please send an email to security [at] cakephp.org. Emails sent to this address go to the CakePHP core team on a private mailing list.

For each report, we try to first confirm the vulnerability. Once confirmed, the CakePHP team will take the following actions:

- Acknowledge to the reporter that we’ve received the issue, and are working on a fix. We ask that the reporter keep the issue confidential until we announce it.
- Get a fix/patch prepared.
- Prepare a post describing the vulnerability, and the possible exploits.
- Release new versions of all affected versions.
- Prominently feature the problem in the release announcement.
