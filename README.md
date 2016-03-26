# StartKit

새로운 iOS project를 시작할 때 해야할 것들.

## [Swiftlint](https://github.com/realm/SwiftLint)

* 새로운 "Run Script Phase" 추가:

		if which swiftlint >/dev/null; then
			swiftlint
		else
			echo "warning: SwiftLint not installed, download from https://github.com/realm/SwiftLint"
		fi

* 코딩룰이 적용된`.swiftlint.yml` 파일을 작성하여 Project root folder에 저장

