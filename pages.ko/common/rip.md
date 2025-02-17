# rip

> 파일이나 디렉토리를 무덤에 보내 제거하고, 복구할 수 있도록 합니다.
> 더 많은 정보: <https://github.com/nivekuil/rip>.

- 지정된 위치에서 파일이나 디렉토리를 제거하고 무덤에 보관:

`rip {{경로/대상/파일_또는_디렉토리}} {{경로/대상/다른/파일_또는_디렉토리}}`

- 파일이나 디렉토리를 대화식으로 제거하며, 제거 전마다 확인 메시지를 표시:

`rip --inspect {{경로/대상/파일_또는_디렉토리}} {{경로/대상/다른/파일_또는_디렉토리}}`

- 현재 디렉토리 내에 원래 있던 파일과 디렉토리를 무덤에서 모두 나열:

`rip --seance`

- 무덤에 있는 모든 파일과 디렉토리를 영구 삭제:

`rip --decompose`

- 가장 최근에 제거된 파일과 디렉토리를 복원:

`rip --unbury`

- `rip --seance`로 나열된 모든 파일과 디렉토리를 복원:

`rip --seance --unbury`
