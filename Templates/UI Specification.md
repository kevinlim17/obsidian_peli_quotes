🕐 Created : <% tp.file.creation_date() %>
✍ Last Edited : <% tp.file.last_modified_date() %>

## Current UI
<p align="left">
	<img src="https://github.com/user-attachments/assets/3e448106-65a7-4281-b71d-320501227586" width="50%">
<p/>

## Needed Data

> [!kotlin] 
> 예시) 책 정보를 관리하는 Data Class
> ```run-kotlin 
> data class Book (
> 	 val id : String,
> 	 val imageURI : String,
> 	 val title : String,
> 	 val author : String,
> 	 val translator : String?,
> 	 val publisher : String,
> 	 val publishDate : Int,
> 	 val genre : String,
> 	 val firstAdded : Int,
> 	 val quote : List<Quote?>
)

> [!swift] 
>  예시) 카메라 API를 가져오는 데 필요한 Context
> ```swift
>

## Requirements
- 예시 ) Splash Screen 구현
- 예시 ) Camera API Lifecycle 관리하기


## Technical Obstacles
- Github Issue 링크를 가져온다든지
- 아니면 따로 작성한 마크다운을 가져온다든지


## Next Screen
- 링크 기능 활용해 다음 화면과 연결
- [[]]

