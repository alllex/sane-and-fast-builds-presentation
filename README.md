# Sane and fast builds for projects of any scale

A talk by Alex Semin

[SLIDES](https://github.com/alllex/sane-and-fast-builds-presentation/blob/main/slides.pdf)

## Topics

- Gradle Project Anatomy
- Java Toolchains
- Test suites
- Convention Plugins
- Composite Builds
- Build Cache
- Parallel Builds
- Configuration Cache

## Abstract

When we start new projects, everything seems easy and fast: adding dependencies is trivial, and tests take only seconds to run. However, as soon as the project starts growing, so do the frictions experienced by developers on a daily basis. Working on mature projects could often be accompanied by unjustified waiting times, even for small changes. This disperses focus and hurts developer productivity.

Gradle’s recent evolutions aim to solve these challenges for JVM projects of any size. This talk will teach you how to keep builds sane in large monorepos and work efficiently on projects spread between repositories. Furthermore, build logic will be reusable, convention-based, and testable.

We’ll also see how Configuration Cache helps speed up local development and more.

