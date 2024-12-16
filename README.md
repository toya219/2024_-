# 2024_-ユースケース
@startuml
left to right direction
package system{
    usecase "出席の管理"as f1
    usecase "履修登録"as f2
}
:user:-->(課題の提出)
:user:-->(資料の配布)
:user:-->(お知らせの確認)
@enduml