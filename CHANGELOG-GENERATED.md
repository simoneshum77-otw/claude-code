# Changelog - Recent Fixes

## 🐛 Bug Fixes

- **#50**: [BUG] Cross-project hook inheritance executes sibling project hooks inappropriately (bug, has repro, platform:macos, area:tools)
- **#48**: Claude Code executes wrong project hooks in multi-project workspace (bug, has repro, platform:macos, area:tools)
- **#37**: Invalid JSON Encoding in API Request Body (bug, duplicate, area:core, platform:macos, area:api)
- **#32**: Calling MCP tool create-spec-doc freezes in Cursor AI + GPT-5 (bug, area:mcp, area:ide, external)
- **#25**: Missing Tool Result Block for Tool Use ID toolu_01GUUUdR6TqtrqKTprMSuLqc (bug, duplicate, area:core, platform:macos, area:api)
- **#22**: [BUG] Search/Grep tool is BROKEN (bug, has repro, area:tools)
- **#21**: Invalid JSON Encoding Error During API Request (bug, duplicate, area:core, platform:macos, area:api)
- **#15**: [BUG] Hard to trace changes in releases (bug)
- **#13**: Agent Command Autocomplete Regression in v72 (bug, has repro, platform:macos, area:tui)
- **#12**: [BUG] PowerLevel10k terminal theme causes Claude Code timeout and parsing failures due to ANSI escape sequence contamination (bug, has repro, area:core, platform:macos, area:tui)

## 📚 Documentation

- **#39**: [DOCS] Slash command frontmatter table is misformatted (documentation)
- **#30**: [Docs] Undocumented `statusline` configuration feature (documentation, area:tui)
- **#23**: [Documentation] Claude Code release notes for v1.0.71 is not informative. Need more detailed notes. (documentation, enhancement)

## 🔄 Duplicates

- **#37**: Invalid JSON Encoding in API Request Body (bug, duplicate, area:core, platform:macos, area:api)
- **#25**: Missing Tool Result Block for Tool Use ID toolu_01GUUUdR6TqtrqKTprMSuLqc (bug, duplicate, area:core, platform:macos, area:api)
- **#21**: Invalid JSON Encoding Error During API Request (bug, duplicate, area:core, platform:macos, area:api)

## 📊 Statistics

### Total Closed Issues: 14

### Distribution by Platform
- **platform:macos**: 8 issues
- **Other/Unspecified**: 6 issues

### Distribution by Area
- **area:core**: 5 issues
- **area:tools**: 4 issues
- **area:tui**: 3 issues
- **area:api**: 3 issues
- **area:mcp**: 1 issue
- **area:ide**: 1 issue
- **Other/Unspecified**: 2 issues

### Key Metrics
- **Bug Issues**: 10
- **Documentation Issues**: 3
- **Enhancement Issues**: 2
- **Issues with Reproduction Steps**: 5
- **Duplicate Issues**: 3
- **External Issues**: 1

### Most Impacted Areas
1. **Core functionality**: Multiple API encoding issues and parsing failures
2. **Tool execution**: Hook inheritance problems and search/grep failures
3. **Terminal UI**: PowerLevel10k compatibility and autocomplete regression
4. **Documentation**: Missing or incomplete documentation for features

---
*Generated on 2025-11-21 from repository issue analysis*