# youtubedosa script

Publisher: 체인저스 캠퍼스

## Overview

This skills-only plugin helps video creators turn a foreign vlogger's source
transcript into a Korean commentary script. It translates spoken dialogue,
adds explanations between scenes, and provides a separate narration-only text
for recording. The writing workflow targets viewers in their fifties and
sixties and aims for approximately ten minutes of finished video, while actual
runtime depends on the clips and speaking speed. Users must provide the source
transcript; the plugin does not retrieve or download YouTube videos.

Install and enable the plugin in a supported Claude experience, then paste a
transcript and ask for a Korean commentary script. For example:

> youtubedosa-script 스킬로 대본 적어줘. 다음은 영상 원문이야: [원문 붙여넣기]

The result includes translated dialogue, scene commentary, and narration-only
recording text. Source timestamps are preserved when supplied. Missing times
are identified rather than invented. Current facts are checked only if the
host provides search, and unavailable search is disclosed.

## 한국어 안내

외국인 브이로그 원문을 한국어로 번역하고 장면 사이에 해설을 더합니다.
완성 대본과 녹음용 해설 전문을 함께 제공합니다. 원문을 붙여넣고
“youtubedosa-script 스킬로 대본 적어줘”라고 요청하세요.
약 10분·공백 제외 약 5,000자를 목표로 하며 실제 영상 길이는 달라질 수 있습니다.

## Data and connections

The package contains instructions and static documentation only. It has no MCP
server, executable scripts, API keys, login system, publisher-controlled storage,
or publisher-controlled telemetry. Input and output are handled by Claude under
the user's account and the applicable Anthropic terms. Optional host-provided
search may process queries according to that feature's terms. Do not submit
sensitive personal information. Publisher-side student authentication is not
implemented.

## License

See LICENSE for the custom limited-use license. Using the plugin to generate
scripts, editing generated scripts, and commercial video production are
permitted, subject to third-party rights. Modification and redistribution of
the instructions or plugin package require prior written permission. Sharing a
link to the authorized listing is permitted. The public source can be inspected;
this package does not restrict installation to students or technically prevent
copying.

## Review before publication

Check names, license authority, contact details in the submission portal, and
any platform findings before publication. The package has not been reviewed or
approved by Anthropic. Availability on specific Claude plans has not been
verified by account-level testing.
