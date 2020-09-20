#!/usr/bin/env node
const program = require('commander')

console.log('version', require('../package').version)

program
  .version(require('../package').version)
	.usage('<command> [项目名称]')
	.command('init', '创建新项目')
	.parse(process.argv)