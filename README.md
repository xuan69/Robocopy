# Robocopy
Robocopy was getting stuck copying some system folders so I used /xd switch to exclude the directories

robocopy h: e: /mir /xd “RECYCLER” “System Volume Information” “Thumbs.db”

