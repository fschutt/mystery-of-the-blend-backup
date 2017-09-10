# List of blender data structures

### Linkreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| next                    | Link           | Link         | *next                   | 0      | 4    |
| prev                    | Link           | Link         | *prev                   | 4      | 4    |

### LinkDatareference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| next                    | LinkData       | LinkData     | *next                   | 0      | 4    |
| prev                    | LinkData       | LinkData     | *prev                   | 4      | 4    |
| data                    | LinkData       | void         | *data                   | 8      | 4    |

### ListBasereference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| first                   | ListBase       | void         | *first                  | 0      | 4    |
| last                    | ListBase       | void         | *last                   | 4      | 4    |


### vec2sreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| x                       | vec2s          | short        | x                       | 0      | 2    |
| y                       | vec2s          | short        | y                       | 2      | 2    |

### vec2ireference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| x                       | vec2i          | int          | x                       | 0      | 4    |
| y                       | vec2i          | int          | y                       | 4      | 4    |




### vec2freference   

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| x                       | vec2f          | float        | x                       | 0      | 4    |
| y                       | vec2f          | float        | y                       | 4      | 4    |




### vec2dreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| x                       | vec2d          | double       | x                       | 0      | 8    |
| y                       | vec2d          | double       | y                       | 8      | 8    |




### vec3ireference   

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| x                       | vec3i          | int          | x                       | 0      | 4    |
| y                       | vec3i          | int          | y                       | 4      | 4    |
| z                       | vec3i          | int          | z                       | 8      | 4    |




### vec3freference   

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| x                       | vec3f          | float        | x                       | 0      | 4    |
| y                       | vec3f          | float        | y                       | 4      | 4    |
| z                       | vec3f          | float        | z                       | 8      | 4    |




### vec3dreference 

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| x                       | vec3d          | double       | x                       | 0      | 8    |
| y                       | vec3d          | double       | y                       | 8      | 8    |
| z                       | vec3d          | double       | z                       | 16     | 8    |




### vec4ireference   

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| x                       | vec4i          | int          | x                       | 0      | 4    |
| y                       | vec4i          | int          | y                       | 4      | 4    |
| z                       | vec4i          | int          | z                       | 8      | 4    |
| w                       | vec4i          | int          | w                       | 12     | 4    |




### vec4freference   

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| x                       | vec4f          | float        | x                       | 0      | 4    |
| y                       | vec4f          | float        | y                       | 4      | 4    |
| z                       | vec4f          | float        | z                       | 8      | 4    |
| w                       | vec4f          | float        | w                       | 12     | 4    |




### vec4dreference   

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| x                       | vec4d          | double       | x                       | 0      | 8    |
| y                       | vec4d          | double       | y                       | 8      | 8    |
| z                       | vec4d          | double       | z                       | 16     | 8    |
| w                       | vec4d          | double       | w                       | 24     | 8    |




### rctireference    

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| xmin                    | rcti           | int          | xmin                    | 0      | 4    |
| xmax                    | rcti           | int          | xmax                    | 4      | 4    |
| ymin                    | rcti           | int          | ymin                    | 8      | 4    |
| ymax                    | rcti           | int          | ymax                    | 12     | 4    |


### rctfreference    

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| xmin                    | rctf           | float        | xmin                    | 0      | 4    |
| xmax                    | rctf           | float        | xmax                    | 4      | 4    |
| ymin                    | rctf           | float        | ymin                    | 8      | 4    |
| ymax                    | rctf           | float        | ymax                    | 12     | 4    |


### IDPropertyDatareference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| pointer                 | IDPropertyData | void         | *pointer                | 0      | 4    |
| group.first             | ListBase       | void         | *first                  | 4      | 4    |
| group.last              | ListBase       | void         | *last                   | 8      | 4    |
| val                     | IDPropertyData | int          | val                     | 12     | 4    |
| val2                    | IDPropertyData | int          | val2                    | 16     | 4    |


### IDPropertyreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| next                    | IDProperty     | IDProperty   | *next                   | 0      | 4    |
| prev                    | IDProperty     | IDProperty   | *prev                   | 4      | 4    |
| name                    | IDProperty     | char         | name[32]                | 8      | 32   |
| type                    | IDProperty     | char         | type                    | 40     | 1    |
| subtype                 | IDProperty     | char         | subtype                 | 41     | 1    |
| flag                    | IDProperty     | short        | flag                    | 42     | 2    |
| saved                   | IDProperty     | int          | saved                   | 44     | 4    |
| data.pointer            | IDPropertyData | void         | *pointer                | 48     | 4    |
| data.group.first        | ListBase       | void         | *first                  | 52     | 4    |
| data.group.last         | ListBase       | void         | *last                   | 56     | 4    |
| data.val                | IDPropertyData | int          | val                     | 60     | 4    |
| data.val2               | IDPropertyData | int          | val2                    | 64     | 4    |
| len                     | IDProperty     | int          | len                     | 68     | 4    |
| totallen                | IDProperty     | int          | totallen                | 72     | 4    |




### IDreference     

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| next                    | ID             | void         | *next                   | 0      | 4    |
| prev                    | ID             | void         | *prev                   | 4      | 4    |
| newid                   | ID             | ID           | *newid                  | 8      | 4    |
| lib                     | ID             | Library      | *lib                    | 12     | 4    |
| name                    | ID             | char         | name[24]                | 16     | 24   |
| us                      | ID             | short        | us                      | 40     | 2    |
| flag                    | ID             | short        | flag                    | 42     | 2    |
| icon_id                 | ID             | int          | icon_id                 | 44     | 4    |
| properties              | ID             | IDProperty   | *properties             | 48     | 4    |




### Libraryreference 

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| id.next                 | ID             | void         | *next                   | 0      | 4    |
| id.prev                 | ID             | void         | *prev                   | 4      | 4    |
| id.newid                | ID             | ID           | *newid                  | 8      | 4    |
| id.lib                  | ID             | Library      | *lib                    | 12     | 4    |
| id.name                 | ID             | char         | name[24]                | 16     | 24   |
| id.us                   | ID             | short        | us                      | 40     | 2    |
| id.flag                 | ID             | short        | flag                    | 42     | 2    |
| id.icon_id              | ID             | int          | icon_id                 | 44     | 4    |
| id.properties           | ID             | IDProperty   | *properties             | 48     | 4    |
| idblock                 | Library        | ID           | *idblock                | 52     | 4    |
| filedata                | Library        | FileData     | *filedata               | 56     | 4    |
| name                    | Library        | char         | name[240]               | 60     | 240  |
| filename                | Library        | char         | filename[240]           | 300    | 240  |
| tot                     | Library        | int          | tot                     | 540    | 4    |
| pad                     | Library        | int          | pad                     | 544    | 4    |
| parent                  | Library        | Library      | *parent                 | 548    | 4    |



### PreviewImagereference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| w                       | PreviewImage   | int          | w[2]                    | 0      | 8    |
| h                       | PreviewImage   | int          | h[2]                    | 8      | 8    |
| changed                 | PreviewImage   | short        | changed[2]              | 16     | 4    |
| pad0                    | PreviewImage   | short        | pad0                    | 20     | 2    |
| pad1                    | PreviewImage   | short        | pad1                    | 22     | 2    |
| rect                    | PreviewImage   | int          | *rect[2]                | 24     | 8    |


### IpoDriverreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| ob                      | IpoDriver      | Object       | *ob                     | 0      | 4    |
| blocktype               | IpoDriver      | short        | blocktype               | 4      | 2    |
| adrcode                 | IpoDriver      | short        | adrcode                 | 6      | 2    |
| type                    | IpoDriver      | short        | type                    | 8      | 2    |
| flag                    | IpoDriver      | short        | flag                    | 10     | 2    |
| name                    | IpoDriver      | char         | name[128]               | 12     | 128  |


### IpoCurvereference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| next                    | IpoCurve       | IpoCurve     | *next                   | 0      | 4    |
| prev                    | IpoCurve       | IpoCurve     | *prev                   | 4      | 4    |
| bp                      | IpoCurve       | BPoint       | *bp                     | 8      | 4    |
| bezt                    | IpoCurve       | BezTriple    | *bezt                   | 12     | 4    |
| maxrct.xmin             | rctf           | float        | xmin                    | 16     | 4    |
| maxrct.xmax             | rctf           | float        | xmax                    | 20     | 4    |
| maxrct.ymin             | rctf           | float        | ymin                    | 24     | 4    |
| maxrct.ymax             | rctf           | float        | ymax                    | 28     | 4    |
| totrct.xmin             | rctf           | float        | xmin                    | 32     | 4    |
| totrct.xmax             | rctf           | float        | xmax                    | 36     | 4    |
| totrct.ymin             | rctf           | float        | ymin                    | 40     | 4    |
| totrct.ymax             | rctf           | float        | ymax                    | 44     | 4    |
| blocktype               | IpoCurve       | short        | blocktype               | 48     | 2    |
| adrcode                 | IpoCurve       | short        | adrcode                 | 50     | 2    |
| vartype                 | IpoCurve       | short        | vartype                 | 52     | 2    |
| totvert                 | IpoCurve       | short        | totvert                 | 54     | 2    |
| ipo                     | IpoCurve       | short        | ipo                     | 56     | 2    |
| extrap                  | IpoCurve       | short        | extrap                  | 58     | 2    |
| flag                    | IpoCurve       | short        | flag                    | 60     | 2    |
| rt                      | IpoCurve       | short        | rt                      | 62     | 2    |
| ymin                    | IpoCurve       | float        | ymin                    | 64     | 4    |
| ymax                    | IpoCurve       | float        | ymax                    | 68     | 4    |
| bitmask                 | IpoCurve       | int          | bitmask                 | 72     | 4    |
| slide_min               | IpoCurve       | float        | slide_min               | 76     | 4    |
| slide_max               | IpoCurve       | float        | slide_max               | 80     | 4    |
| curval                  | IpoCurve       | float        | curval                  | 84     | 4    |
| driver                  | IpoCurve       | IpoDriver    | *driver                 | 88     | 4    |


### Iporeference     

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| id.next                 | ID             | void         | *next                   | 0      | 4    |
| id.prev                 | ID             | void         | *prev                   | 4      | 4    |
| id.newid                | ID             | ID           | *newid                  | 8      | 4    |
| id.lib                  | ID             | Library      | *lib                    | 12     | 4    |
| id.name                 | ID             | char         | name[24]                | 16     | 24   |
| id.us                   | ID             | short        | us                      | 40     | 2    |
| id.flag                 | ID             | short        | flag                    | 42     | 2    |
| id.icon_id              | ID             | int          | icon_id                 | 44     | 4    |
| id.properties           | ID             | IDProperty   | *properties             | 48     | 4    |
| curve.first             | ListBase       | void         | *first                  | 52     | 4    |
| curve.last              | ListBase       | void         | *last                   | 56     | 4    |
| cur.xmin                | rctf           | float        | xmin                    | 60     | 4    |
| cur.xmax                | rctf           | float        | xmax                    | 64     | 4    |
| cur.ymin                | rctf           | float        | ymin                    | 68     | 4    |
| cur.ymax                | rctf           | float        | ymax                    | 72     | 4    |
| blocktype               | Ipo            | short        | blocktype               | 76     | 2    |
| showkey                 | Ipo            | short        | showkey                 | 78     | 2    |
| muteipo                 | Ipo            | short        | muteipo                 | 80     | 2    |
| pad                     | Ipo            | short        | pad                     | 82     | 2    |


### KeyBlockreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| next                    | KeyBlock       | KeyBlock     | *next                   | 0      | 4    |
| prev                    | KeyBlock       | KeyBlock     | *prev                   | 4      | 4    |
| pos                     | KeyBlock       | float        | pos                     | 8      | 4    |
| curval                  | KeyBlock       | float        | curval                  | 12     | 4    |
| type                    | KeyBlock       | short        | type                    | 16     | 2    |
| adrcode                 | KeyBlock       | short        | adrcode                 | 18     | 2    |
| relative                | KeyBlock       | short        | relative                | 20     | 2    |
| flag                    | KeyBlock       | short        | flag                    | 22     | 2    |
| totelem                 | KeyBlock       | int          | totelem                 | 24     | 4    |
| pad2                    | KeyBlock       | int          | pad2                    | 28     | 4    |
| data                    | KeyBlock       | void         | *data                   | 32     | 4    |
| weights                 | KeyBlock       | float        | *weights                | 36     | 4    |
| name                    | KeyBlock       | char         | name[32]                | 40     | 32   |
| vgroup                  | KeyBlock       | char         | vgroup[32]              | 72     | 32   |
| slidermin               | KeyBlock       | float        | slidermin               | 104    | 4    |
| slidermax               | KeyBlock       | float        | slidermax               | 108    | 4    |


### Keyreference     

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| id.next                 | ID             | void         | *next                   | 0      | 4    |
| id.prev                 | ID             | void         | *prev                   | 4      | 4    |
| id.newid                | ID             | ID           | *newid                  | 8      | 4    |
| id.lib                  | ID             | Library      | *lib                    | 12     | 4    |
| id.name                 | ID             | char         | name[24]                | 16     | 24   |
| id.us                   | ID             | short        | us                      | 40     | 2    |
| id.flag                 | ID             | short        | flag                    | 42     | 2    |
| id.icon_id              | ID             | int          | icon_id                 | 44     | 4    |
| id.properties           | ID             | IDProperty   | *properties             | 48     | 4    |
| refkey                  | Key            | KeyBlock     | *refkey                 | 52     | 4    |
| elemstr                 | Key            | char         | elemstr[32]             | 56     | 32   |
| elemsize                | Key            | int          | elemsize                | 88     | 4    |
| curval                  | Key            | float        | curval                  | 92     | 4    |
| block.first             | ListBase       | void         | *first                  | 96     | 4    |
| block.last              | ListBase       | void         | *last                   | 100    | 4    |
| ipo                     | Key            | Ipo          | *ipo                    | 104    | 4    |
| from                    | Key            | ID           | *from                   | 108    | 4    |
| type                    | Key            | short        | type                    | 112    | 2    |
| totkey                  | Key            | short        | totkey                  | 114    | 2    |
| slurph                  | Key            | short        | slurph                  | 116    | 2    |
| flag                    | Key            | short        | flag                    | 118    | 2    |


### ScriptLinkreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| scripts                 | ScriptLink     | ID           | **scripts               | 0      | 4    |
| flag                    | ScriptLink     | short        | *flag                   | 4      | 4    |
| actscript               | ScriptLink     | short        | actscript               | 8      | 2    |
| totscript               | ScriptLink     | short        | totscript               | 10     | 2    |
| pad                     | ScriptLink     | int          | pad                     | 12     | 4    |


### TextLinereference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| next                    | TextLine       | TextLine     | *next                   | 0      | 4    |
| prev                    | TextLine       | TextLine     | *prev                   | 4      | 4    |
| line                    | TextLine       | char         | *line                   | 8      | 4    |
| format                  | TextLine       | char         | *format                 | 12     | 4    |
| len                     | TextLine       | int          | len                     | 16     | 4    |
| blen                    | TextLine       | int          | blen                    | 20     | 4    |




### TextMarkerreference     

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| next                    | TextMarker     | TextMarker   | *next                   | 0      | 4    |
| prev                    | TextMarker     | TextMarker   | *prev                   | 4      | 4    |
| lineno                  | TextMarker     | int          | lineno                  | 8      | 4    |
| start                   | TextMarker     | int          | start                   | 12     | 4    |
| end                     | TextMarker     | int          | end                     | 16     | 4    |
| pad1                    | TextMarker     | int          | pad1                    | 20     | 4    |
| group                   | TextMarker     | int          | group                   | 24     | 4    |
| flags                   | TextMarker     | int          | flags                   | 28     | 4    |
| color                   | TextMarker     | char         | color[4]                | 32     | 4    |
| pad                     | TextMarker     | char         | pad[4]                  | 36     | 4    |


### Textreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| id.next                 | ID             | void         | *next                   | 0      | 4    |
| id.prev                 | ID             | void         | *prev                   | 4      | 4    |
| id.newid                | ID             | ID           | *newid                  | 8      | 4    |
| id.lib                  | ID             | Library      | *lib                    | 12     | 4    |
| id.name                 | ID             | char         | name[24]                | 16     | 24   |
| id.us                   | ID             | short        | us                      | 40     | 2    |
| id.flag                 | ID             | short        | flag                    | 42     | 2    |
| id.icon_id              | ID             | int          | icon_id                 | 44     | 4    |
| id.properties           | ID             | IDProperty   | *properties             | 48     | 4    |
| name                    | Text           | char         | *name                   | 52     | 4    |
| flags                   | Text           | int          | flags                   | 56     | 4    |
| nlines                  | Text           | int          | nlines                  | 60     | 4    |
| lines.first             | ListBase       | void         | *first                  | 64     | 4    |
| lines.last              | ListBase       | void         | *last                   | 68     | 4    |
| curl                    | Text           | TextLine     | *curl                   | 72     | 4    |
| sell                    | Text           | TextLine     | *sell                   | 76     | 4    |
| curc                    | Text           | int          | curc                    | 80     | 4    |
| selc                    | Text           | int          | selc                    | 84     | 4    |
| markers.first           | ListBase       | void         | *first                  | 88     | 4    |
| markers.last            | ListBase       | void         | *last                   | 92     | 4    |
| undo_buf                | Text           | char         | *undo_buf               | 96     | 4    |
| undo_pos                | Text           | int          | undo_pos                | 100    | 4    |
| undo_len                | Text           | int          | undo_len                | 104    | 4    |
| compiled                | Text           | void         | *compiled               | 108    | 4    |
| mtime                   | Text           | double       | mtime                   | 112    | 8    |


### PackedFilereference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| size                    | PackedFile     | int          | size                    | 0      | 4    |
| seek                    | PackedFile     | int          | seek                    | 4      | 4    |
| flags                   | PackedFile     | int          | flags                   | 8      | 4    |
| pad                     | PackedFile     | int          | pad                     | 12     | 4    |
| data                    | PackedFile     | void         | *data                   | 16     | 4    |


### Camerareference  

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| id.next                 | ID             | void         | *next                   | 0      | 4    |
| id.prev                 | ID             | void         | *prev                   | 4      | 4    |
| id.newid                | ID             | ID           | *newid                  | 8      | 4    |
| id.lib                  | ID             | Library      | *lib                    | 12     | 4    |
| id.name                 | ID             | char         | name[24]                | 16     | 24   |
| id.us                   | ID             | short        | us                      | 40     | 2    |
| id.flag                 | ID             | short        | flag                    | 42     | 2    |
| id.icon_id              | ID             | int          | icon_id                 | 44     | 4    |
| id.properties           | ID             | IDProperty   | *properties             | 48     | 4    |
| type                    | Camera         | short        | type                    | 52     | 2    |
| flag                    | Camera         | short        | flag                    | 54     | 2    |
| passepartalpha          | Camera         | float        | passepartalpha          | 56     | 4    |
| angle                   | Camera         | float        | angle                   | 60     | 4    |
| clipsta                 | Camera         | float        | clipsta                 | 64     | 4    |
| clipend                 | Camera         | float        | clipend                 | 68     | 4    |
| lens                    | Camera         | float        | lens                    | 72     | 4    |
| ortho_scale             | Camera         | float        | ortho_scale             | 76     | 4    |
| drawsize                | Camera         | float        | drawsize                | 80     | 4    |
| shiftx                  | Camera         | float        | shiftx                  | 84     | 4    |
| shifty                  | Camera         | float        | shifty                  | 88     | 4    |
| YF_dofdist              | Camera         | float        | YF_dofdist              | 92     | 4    |
| YF_aperture             | Camera         | float        | YF_aperture             | 96     | 4    |
| YF_bkhtype              | Camera         | short        | YF_bkhtype              | 100    | 2    |
| YF_bkhbias              | Camera         | short        | YF_bkhbias              | 102    | 2    |
| YF_bkhrot               | Camera         | float        | YF_bkhrot               | 104    | 4    |
| ipo                     | Camera         | Ipo          | *ipo                    | 108    | 4    |
| scriptlink.scripts      | ScriptLink     | ID           | **scripts               | 112    | 4    |
| scriptlink.flag         | ScriptLink     | short        | *flag                   | 116    | 4    |
| scriptlink.actscript    | ScriptLink     | short        | actscript               | 120    | 2    |
| scriptlink.totscript    | ScriptLink     | short        | totscript               | 122    | 2    |
| scriptlink.pad          | ScriptLink     | int          | pad                     | 124    | 4    |
| dof_ob                  | Camera         | Object       | *dof_ob                 | 128    | 4    |


### ImageUserreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| framenr                 | ImageUser      | int          | framenr                 | 0      | 4    |
| frames                  | ImageUser      | int          | frames                  | 4      | 4    |
| offset                  | ImageUser      | int          | offset                  | 8      | 4    |
| sfra                    | ImageUser      | int          | sfra                    | 12     | 4    |
| fie_ima                 | ImageUser      | short        | fie_ima                 | 16     | 2    |
| cycl                    | ImageUser      | short        | cycl                    | 18     | 2    |
| flag                    | ImageUser      | short        | flag                    | 20     | 2    |
| ok                      | ImageUser      | short        | ok                      | 22     | 2    |
| multi_index             | ImageUser      | short        | multi_index             | 24     | 2    |
| layer                   | ImageUser      | short        | layer                   | 26     | 2    |
| pass                    | ImageUser      | short        | pass                    | 28     | 2    |
| menunr                  | ImageUser      | short        | menunr                  | 30     | 2    |


### Imagereference  

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| id.next                 | ID             | void         | *next                   | 0      | 4    |
| id.prev                 | ID             | void         | *prev                   | 4      | 4    |
| id.newid                | ID             | ID           | *newid                  | 8      | 4    |
| id.lib                  | ID             | Library      | *lib                    | 12     | 4    |
| id.name                 | ID             | char         | name[24]                | 16     | 24   |
| id.us                   | ID             | short        | us                      | 40     | 2    |
| id.flag                 | ID             | short        | flag                    | 42     | 2    |
| id.icon_id              | ID             | int          | icon_id                 | 44     | 4    |
| id.properties           | ID             | IDProperty   | *properties             | 48     | 4    |
| name                    | Image          | char         | name[240]               | 52     | 240  |
| ibufs.first             | ListBase       | void         | *first                  | 292    | 4    |
| ibufs.last              | ListBase       | void         | *last                   | 296    | 4    |
| gputexture              | Image          | GPUTexture   | *gputexture             | 300    | 4    |
| anim                    | Image          | anim         | *anim                   | 304    | 4    |
| rr                      | Image          | RenderResult | *rr                     | 308    | 4    |
| ok                      | Image          | short        | ok                      | 312    | 2    |
| flag                    | Image          | short        | flag                    | 314    | 2    |
| source                  | Image          | short        | source                  | 316    | 2    |
| type                    | Image          | short        | type                    | 318    | 2    |
| pad                     | Image          | short        | pad                     | 320    | 2    |
| pad1                    | Image          | short        | pad1                    | 322    | 2    |
| lastframe               | Image          | int          | lastframe               | 324    | 4    |
| tpageflag               | Image          | short        | tpageflag               | 328    | 2    |
| totbind                 | Image          | short        | totbind                 | 330    | 2    |
| xrep                    | Image          | short        | xrep                    | 332    | 2    |
| yrep                    | Image          | short        | yrep                    | 334    | 2    |
| twsta                   | Image          | short        | twsta                   | 336    | 2    |
| twend                   | Image          | short        | twend                   | 338    | 2    |
| bindcode                | Image          | int          | bindcode                | 340    | 4    |
| repbind                 | Image          | int          | *repbind                | 344    | 4    |
| packedfile              | Image          | PackedFile   | *packedfile             | 348    | 4    |
| preview                 | Image          | PreviewImage | *preview                | 352    | 4    |
| lastupdate              | Image          | float        | lastupdate              | 356    | 4    |
| lastused                | Image          | int          | lastused                | 360    | 4    |
| animspeed               | Image          | short        | animspeed               | 364    | 2    |
| gen_x                   | Image          | short        | gen_x                   | 366    | 2    |
| gen_y                   | Image          | short        | gen_y                   | 368    | 2    |
| gen_type                | Image          | short        | gen_type                | 370    | 2    |
| aspx                    | Image          | float        | aspx                    | 372    | 4    |
| aspy                    | Image          | float        | aspy                    | 376    | 4    |
| vnode                   | Image          | void         | *vnode                  | 380    | 4    |


### MTexreference 

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| texco                   | MTex           | short        | texco                   | 0      | 2    |
| mapto                   | MTex           | short        | mapto                   | 2      | 2    |
| maptoneg                | MTex           | short        | maptoneg                | 4      | 2    |
| blendtype               | MTex           | short        | blendtype               | 6      | 2    |
| object                  | MTex           | Object       | *object                 | 8      | 4    |
| tex                     | MTex           | Tex          | *tex                    | 12     | 4    |
| uvname                  | MTex           | char         | uvname[32]              | 16     | 32   |
| projx                   | MTex           | char         | projx                   | 48     | 1    |
| projy                   | MTex           | char         | projy                   | 49     | 1    |
| projz                   | MTex           | char         | projz                   | 50     | 1    |
| mapping                 | MTex           | char         | mapping                 | 51     | 1    |
| ofs                     | MTex           | float        | ofs[3]                  | 52     | 12   |
| size                    | MTex           | float        | size[3]                 | 64     | 12   |
| texflag                 | MTex           | short        | texflag                 | 76     | 2    |
| colormodel              | MTex           | short        | colormodel              | 78     | 2    |
| pmapto                  | MTex           | short        | pmapto                  | 80     | 2    |
| pmaptoneg               | MTex           | short        | pmaptoneg               | 82     | 2    |
| normapspace             | MTex           | short        | normapspace             | 84     | 2    |
| pad                     | MTex           | short        | pad[3]                  | 86     | 6    |
| r                       | MTex           | float        | r                       | 92     | 4    |
| g                       | MTex           | float        | g                       | 96     | 4    |
| b                       | MTex           | float        | b                       | 100    | 4    |
| k                       | MTex           | float        | k                       | 104    | 4    |
| def_var                 | MTex           | float        | def_var                 | 108    | 4    |
| rt                      | MTex           | float        | rt                      | 112    | 4    |
| colfac                  | MTex           | float        | colfac                  | 116    | 4    |
| norfac                  | MTex           | float        | norfac                  | 120    | 4    |
| varfac                  | MTex           | float        | varfac                  | 124    | 4    |
| dispfac                 | MTex           | float        | dispfac                 | 128    | 4    |
| warpfac                 | MTex           | float        | warpfac                 | 132    | 4    |


### PluginTexreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| name                    | PluginTex      | char         | name[160]               | 0      | 160  |
| handle                  | PluginTex      | void         | *handle                 | 160    | 4    |
| pname                   | PluginTex      | char         | *pname                  | 164    | 4    |
| stnames                 | PluginTex      | char         | *stnames                | 168    | 4    |
| stypes                  | PluginTex      | int          | stypes                  | 172    | 4    |
| vars                    | PluginTex      | int          | vars                    | 176    | 4    |
| varstr                  | PluginTex      | void         | *varstr                 | 180    | 4    |
| result                  | PluginTex      | float        | *result                 | 184    | 4    |
| cfra                    | PluginTex      | float        | *cfra                   | 188    | 4    |
| data                    | PluginTex      | float        | data[32]                | 192    | 128  |
| doit                    | PluginTex      | int          | (*doit)()               | 320    | 4    |
| instance_init           | PluginTex      | void         | (*instance_init)()      | 324    | 4    |
| callback                | PluginTex      | void         | (*callback)()           | 328    | 4    |
| version                 | PluginTex      | int          | version                 | 332    | 4    |
| pad                     | PluginTex      | int          | pad                     | 336    | 4    |




### CBDatareference  

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| r                       | CBData         | float        | r                       | 0      | 4    |
| g                       | CBData         | float        | g                       | 4      | 4    |
| b                       | CBData         | float        | b                       | 8      | 4    |
| a                       | CBData         | float        | a                       | 12     | 4    |
| pos                     | CBData         | float        | pos                     | 16     | 4    |
| cur                     | CBData         | int          | cur                     | 20     | 4    |


### ColorBandreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| flag                    | ColorBand      | short        | flag                    | 0      | 2    |
| tot                     | ColorBand      | short        | tot                     | 2      | 2    |
| cur                     | ColorBand      | short        | cur                     | 4      | 2    |
| ipotype                 | ColorBand      | short        | ipotype                 | 6      | 2    |
| data.r                  | CBData         | float        | r                       | 8      | 4    |
| data.g                  | CBData         | float        | g                       | 12     | 4    |
| data.b                  | CBData         | float        | b                       | 16     | 4    |
| data.a                  | CBData         | float        | a                       | 20     | 4    |
| data.pos                | CBData         | float        | pos                     | 24     | 4    |
| data.cur                | CBData         | int          | cur                     | 28     | 4    |


### EnvMapreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| object                  | EnvMap         | Object       | *object                 | 0      | 4    |
| ima                     | EnvMap         | Image        | *ima                    | 4      | 4    |
| cube                    | EnvMap         | ImBuf        | *cube[6]                | 8      | 24   |
| imat                    | EnvMap         | float        | imat[4][4]              | 32     | 16   |
| obimat                  | EnvMap         | float        | obimat[3][3]            | 48     | 12   |
| type                    | EnvMap         | short        | type                    | 60     | 2    |
| stype                   | EnvMap         | short        | stype                   | 62     | 2    |
| clipsta                 | EnvMap         | float        | clipsta                 | 64     | 4    |
| clipend                 | EnvMap         | float        | clipend                 | 68     | 4    |
| viewscale               | EnvMap         | float        | viewscale               | 72     | 4    |
| notlay                  | EnvMap         | int          | notlay                  | 76     | 4    |
| cuberes                 | EnvMap         | short        | cuberes                 | 80     | 2    |
| depth                   | EnvMap         | short        | depth                   | 82     | 2    |
| ok                      | EnvMap         | int          | ok                      | 84     | 4    |
| lastframe               | EnvMap         | int          | lastframe               | 88     | 4    |
| recalc                  | EnvMap         | short        | recalc                  | 92     | 2    |
| lastsize                | EnvMap         | short        | lastsize                | 94     | 2    |


### Texreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| id.next                 | ID             | void         | *next                   | 0      | 4    |
| id.prev                 | ID             | void         | *prev                   | 4      | 4    |
| id.newid                | ID             | ID           | *newid                  | 8      | 4    |
| id.lib                  | ID             | Library      | *lib                    | 12     | 4    |
| id.name                 | ID             | char         | name[24]                | 16     | 24   |
| id.us                   | ID             | short        | us                      | 40     | 2    |
| id.flag                 | ID             | short        | flag                    | 42     | 2    |
| id.icon_id              | ID             | int          | icon_id                 | 44     | 4    |
| id.properties           | ID             | IDProperty   | *properties             | 48     | 4    |
| noisesize               | Tex            | float        | noisesize               | 52     | 4    |
| turbul                  | Tex            | float        | turbul                  | 56     | 4    |
| bright                  | Tex            | float        | bright                  | 60     | 4    |
| contrast                | Tex            | float        | contrast                | 64     | 4    |
| rfac                    | Tex            | float        | rfac                    | 68     | 4    |
| gfac                    | Tex            | float        | gfac                    | 72     | 4    |
| bfac                    | Tex            | float        | bfac                    | 76     | 4    |
| filtersize              | Tex            | float        | filtersize              | 80     | 4    |
| mg_H                    | Tex            | float        | mg_H                    | 84     | 4    |
| mg_lacunarity           | Tex            | float        | mg_lacunarity           | 88     | 4    |
| mg_octaves              | Tex            | float        | mg_octaves              | 92     | 4    |
| mg_offset               | Tex            | float        | mg_offset               | 96     | 4    |
| mg_gain                 | Tex            | float        | mg_gain                 | 100    | 4    |
| dist_amount             | Tex            | float        | dist_amount             | 104    | 4    |
| ns_outscale             | Tex            | float        | ns_outscale             | 108    | 4    |
| vn_w1                   | Tex            | float        | vn_w1                   | 112    | 4    |
| vn_w2                   | Tex            | float        | vn_w2                   | 116    | 4    |
| vn_w3                   | Tex            | float        | vn_w3                   | 120    | 4    |
| vn_w4                   | Tex            | float        | vn_w4                   | 124    | 4    |
| vn_mexp                 | Tex            | float        | vn_mexp                 | 128    | 4    |
| vn_distm                | Tex            | short        | vn_distm                | 132    | 2    |
| vn_coltype              | Tex            | short        | vn_coltype              | 134    | 2    |
| noisedepth              | Tex            | short        | noisedepth              | 136    | 2    |
| noisetype               | Tex            | short        | noisetype               | 138    | 2    |
| noisebasis              | Tex            | short        | noisebasis              | 140    | 2    |
| noisebasis2             | Tex            | short        | noisebasis2             | 142    | 2    |
| imaflag                 | Tex            | short        | imaflag                 | 144    | 2    |
| flag                    | Tex            | short        | flag                    | 146    | 2    |
| type                    | Tex            | short        | type                    | 148    | 2    |
| stype                   | Tex            | short        | stype                   | 150    | 2    |
| cropxmin                | Tex            | float        | cropxmin                | 152    | 4    |
| cropymin                | Tex            | float        | cropymin                | 156    | 4    |
| cropxmax                | Tex            | float        | cropxmax                | 160    | 4    |
| cropymax                | Tex            | float        | cropymax                | 164    | 4    |
| xrepeat                 | Tex            | short        | xrepeat                 | 168    | 2    |
| yrepeat                 | Tex            | short        | yrepeat                 | 170    | 2    |
| extend                  | Tex            | short        | extend                  | 172    | 2    |
| fie_ima                 | Tex            | short        | fie_ima                 | 174    | 2    |
| len                     | Tex            | int          | len                     | 176    | 4    |
| frames                  | Tex            | int          | frames                  | 180    | 4    |
| offset                  | Tex            | int          | offset                  | 184    | 4    |
| sfra                    | Tex            | int          | sfra                    | 188    | 4    |
| checkerdist             | Tex            | float        | checkerdist             | 192    | 4    |
| nabla                   | Tex            | float        | nabla                   | 196    | 4    |
| norfac                  | Tex            | float        | norfac                  | 200    | 4    |
| iuser.framenr           | ImageUser      | int          | framenr                 | 204    | 4    |
| iuser.frames            | ImageUser      | int          | frames                  | 208    | 4    |
| iuser.offset            | ImageUser      | int          | offset                  | 212    | 4    |
| iuser.sfra              | ImageUser      | int          | sfra                    | 216    | 4    |
| iuser.fie_ima           | ImageUser      | short        | fie_ima                 | 220    | 2    |
| iuser.cycl              | ImageUser      | short        | cycl                    | 222    | 2    |
| iuser.flag              | ImageUser      | short        | flag                    | 224    | 2    |
| iuser.ok                | ImageUser      | short        | ok                      | 226    | 2    |
| iuser.multi_index       | ImageUser      | short        | multi_index             | 228    | 2    |
| iuser.layer             | ImageUser      | short        | layer                   | 230    | 2    |
| iuser.pass              | ImageUser      | short        | pass                    | 232    | 2    |
| iuser.menunr            | ImageUser      | short        | menunr                  | 234    | 2    |
| ipo                     | Tex            | Ipo          | *ipo                    | 236    | 4    |
| ima                     | Tex            | Image        | *ima                    | 240    | 4    |
| plugin                  | Tex            | PluginTex    | *plugin                 | 244    | 4    |
| coba                    | Tex            | ColorBand    | *coba                   | 248    | 4    |
| env                     | Tex            | EnvMap       | *env                    | 252    | 4    |
| preview                 | Tex            | PreviewImage | *preview                | 256    | 4    |


### TexMappingreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| loc                     | TexMapping     | float        | loc[3]                  | 0      | 12   |
| rot                     | TexMapping     | float        | rot[3]                  | 12     | 12   |
| size                    | TexMapping     | float        | size[3]                 | 24     | 12   |
| flag                    | TexMapping     | int          | flag                    | 36     | 4    |
| mat                     | TexMapping     | float        | mat[4][4]               | 40     | 16   |
| min                     | TexMapping     | float        | min[3]                  | 56     | 12   |
| max                     | TexMapping     | float        | max[3]                  | 68     | 12   |
| ob                      | TexMapping     | Object       | *ob                     | 80     | 4    |


### Lampreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| id.next                 | ID             | void         | *next                   | 0      | 4    |
| id.prev                 | ID             | void         | *prev                   | 4      | 4    |
| id.newid                | ID             | ID           | *newid                  | 8      | 4    |
| id.lib                  | ID             | Library      | *lib                    | 12     | 4    |
| id.name                 | ID             | char         | name[24]                | 16     | 24   |
| id.us                   | ID             | short        | us                      | 40     | 2    |
| id.flag                 | ID             | short        | flag                    | 42     | 2    |
| id.icon_id              | ID             | int          | icon_id                 | 44     | 4    |
| id.properties           | ID             | IDProperty   | *properties             | 48     | 4    |
| type                    | Lamp           | short        | type                    | 52     | 2    |
| pad3                    | Lamp           | short        | pad3                    | 54     | 2    |
| mode                    | Lamp           | int          | mode                    | 56     | 4    |
| colormodel              | Lamp           | short        | colormodel              | 60     | 2    |
| totex                   | Lamp           | short        | totex                   | 62     | 2    |
| r                       | Lamp           | float        | r                       | 64     | 4    |
| g                       | Lamp           | float        | g                       | 68     | 4    |
| b                       | Lamp           | float        | b                       | 72     | 4    |
| k                       | Lamp           | float        | k                       | 76     | 4    |
| shdwr                   | Lamp           | float        | shdwr                   | 80     | 4    |
| shdwg                   | Lamp           | float        | shdwg                   | 84     | 4    |
| shdwb                   | Lamp           | float        | shdwb                   | 88     | 4    |
| shdwpad                 | Lamp           | float        | shdwpad                 | 92     | 4    |
| energy                  | Lamp           | float        | energy                  | 96     | 4    |
| dist                    | Lamp           | float        | dist                    | 100    | 4    |
| spotsize                | Lamp           | float        | spotsize                | 104    | 4    |
| spotblend               | Lamp           | float        | spotblend               | 108    | 4    |
| haint                   | Lamp           | float        | haint                   | 112    | 4    |
| att1                    | Lamp           | float        | att1                    | 116    | 4    |
| att2                    | Lamp           | float        | att2                    | 120    | 4    |
| curfalloff              | Lamp           | CurveMapping | *curfalloff             | 124    | 4    |
| falloff_type            | Lamp           | short        | falloff_type            | 128    | 2    |
| pad2                    | Lamp           | short        | pad2                    | 130    | 2    |
| clipsta                 | Lamp           | float        | clipsta                 | 132    | 4    |
| clipend                 | Lamp           | float        | clipend                 | 136    | 4    |
| shadspotsize            | Lamp           | float        | shadspotsize            | 140    | 4    |
| bias                    | Lamp           | float        | bias                    | 144    | 4    |
| soft                    | Lamp           | float        | soft                    | 148    | 4    |
| bufsize                 | Lamp           | short        | bufsize                 | 152    | 2    |
| samp                    | Lamp           | short        | samp                    | 154    | 2    |
| buffers                 | Lamp           | short        | buffers                 | 156    | 2    |
| filtertype              | Lamp           | short        | filtertype              | 158    | 2    |
| bufflag                 | Lamp           | char         | bufflag                 | 160    | 1    |
| buftype                 | Lamp           | char         | buftype                 | 161    | 1    |
| ray_samp                | Lamp           | short        | ray_samp                | 162    | 2    |
| ray_sampy               | Lamp           | short        | ray_sampy               | 164    | 2    |
| ray_sampz               | Lamp           | short        | ray_sampz               | 166    | 2    |
| ray_samp_type           | Lamp           | short        | ray_samp_type           | 168    | 2    |
| area_shape              | Lamp           | short        | area_shape              | 170    | 2    |
| area_size               | Lamp           | float        | area_size               | 172    | 4    |
| area_sizey              | Lamp           | float        | area_sizey              | 176    | 4    |
| area_sizez              | Lamp           | float        | area_sizez              | 180    | 4    |
| adapt_thresh            | Lamp           | float        | adapt_thresh            | 184    | 4    |
| ray_samp_method         | Lamp           | short        | ray_samp_method         | 188    | 2    |
| pad1                    | Lamp           | short        | pad1                    | 190    | 2    |
| texact                  | Lamp           | short        | texact                  | 192    | 2    |
| shadhalostep            | Lamp           | short        | shadhalostep            | 194    | 2    |
| sun_effect_type         | Lamp           | short        | sun_effect_type         | 196    | 2    |
| skyblendtype            | Lamp           | short        | skyblendtype            | 198    | 2    |
| horizon_brightness      | Lamp           | float        | horizon_brightness      | 200    | 4    |
| spread                  | Lamp           | float        | spread                  | 204    | 4    |
| sun_brightness          | Lamp           | float        | sun_brightness          | 208    | 4    |
| sun_size                | Lamp           | float        | sun_size                | 212    | 4    |
| backscattered_light     | Lamp           | float        | backscattered_light     | 216    | 4    |
| sun_intensity           | Lamp           | float        | sun_intensity           | 220    | 4    |
| atm_turbidity           | Lamp           | float        | atm_turbidity           | 224    | 4    |
| atm_inscattering_factor | Lamp           | float        | atm_inscattering_factor | 228    | 4    |
| atm_extinction_factor   | Lamp           | float        | atm_extinction_factor   | 232    | 4    |
| atm_distance_factor     | Lamp           | float        | atm_distance_factor     | 236    | 4    |
| skyblendfac             | Lamp           | float        | skyblendfac             | 240    | 4    |
| sky_exposure            | Lamp           | float        | sky_exposure            | 244    | 4    |
| sky_colorspace          | Lamp           | short        | sky_colorspace          | 248    | 2    |
| pad4                    | Lamp           | short        | pad4                    | 250    | 2    |
| YF_numphotons           | Lamp           | int          | YF_numphotons           | 252    | 4    |
| YF_numsearch            | Lamp           | int          | YF_numsearch            | 256    | 4    |
| YF_phdepth              | Lamp           | short        | YF_phdepth              | 260    | 2    |
| YF_useqmc               | Lamp           | short        | YF_useqmc               | 262    | 2    |
| YF_bufsize              | Lamp           | short        | YF_bufsize              | 264    | 2    |
| YF_pad                  | Lamp           | short        | YF_pad                  | 266    | 2    |
| YF_causticblur          | Lamp           | float        | YF_causticblur          | 268    | 4    |
| YF_ltradius             | Lamp           | float        | YF_ltradius             | 272    | 4    |
| YF_glowint              | Lamp           | float        | YF_glowint              | 276    | 4    |
| YF_glowofs              | Lamp           | float        | YF_glowofs              | 280    | 4    |
| YF_glowtype             | Lamp           | short        | YF_glowtype             | 284    | 2    |
| YF_pad2                 | Lamp           | short        | YF_pad2                 | 286    | 2    |
| mtex                    | Lamp           | MTex         | *mtex[18]               | 288    | 72   |
| ipo                     | Lamp           | Ipo          | *ipo                    | 360    | 4    |
| preview                 | Lamp           | PreviewImage | *preview                | 364    | 4    |
| scriptlink.scripts      | ScriptLink     | ID           | **scripts               | 368    | 4    |
| scriptlink.flag         | ScriptLink     | short        | *flag                   | 372    | 4    |
| scriptlink.actscript    | ScriptLink     | short        | actscript               | 376    | 2    |
| scriptlink.totscript    | ScriptLink     | short        | totscript               | 378    | 2    |
| scriptlink.pad          | ScriptLink     | int          | pad                     | 380    | 4    |


### Wavereference  

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| id.next                 | ID             | void         | *next                   | 0      | 4    |
| id.prev                 | ID             | void         | *prev                   | 4      | 4    |
| id.newid                | ID             | ID           | *newid                  | 8      | 4    |
| id.lib                  | ID             | Library      | *lib                    | 12     | 4    |
| id.name                 | ID             | char         | name[24]                | 16     | 24   |
| id.us                   | ID             | short        | us                      | 40     | 2    |
| id.flag                 | ID             | short        | flag                    | 42     | 2    |
| id.icon_id              | ID             | int          | icon_id                 | 44     | 4    |
| id.properties           | ID             | IDProperty   | *properties             | 48     | 4    |
| ipo                     | Wave           | Ipo          | *ipo                    | 52     | 4    |


### Materialreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| id.next                 | ID             | void         | *next                   | 0      | 4    |
| id.prev                 | ID             | void         | *prev                   | 4      | 4    |
| id.newid                | ID             | ID           | *newid                  | 8      | 4    |
| id.lib                  | ID             | Library      | *lib                    | 12     | 4    |
| id.name                 | ID             | char         | name[24]                | 16     | 24   |
| id.us                   | ID             | short        | us                      | 40     | 2    |
| id.flag                 | ID             | short        | flag                    | 42     | 2    |
| id.icon_id              | ID             | int          | icon_id                 | 44     | 4    |
| id.properties           | ID             | IDProperty   | *properties             | 48     | 4    |
| colormodel              | Material       | short        | colormodel              | 52     | 2    |
| flag                    | Material       | short        | flag                    | 54     | 2    |
| r                       | Material       | float        | r                       | 56     | 4    |
| g                       | Material       | float        | g                       | 60     | 4    |
| b                       | Material       | float        | b                       | 64     | 4    |
| specr                   | Material       | float        | specr                   | 68     | 4    |
| specg                   | Material       | float        | specg                   | 72     | 4    |
| specb                   | Material       | float        | specb                   | 76     | 4    |
| mirr                    | Material       | float        | mirr                    | 80     | 4    |
| mirg                    | Material       | float        | mirg                    | 84     | 4    |
| mirb                    | Material       | float        | mirb                    | 88     | 4    |
| ambr                    | Material       | float        | ambr                    | 92     | 4    |
| ambb                    | Material       | float        | ambb                    | 96     | 4    |
| ambg                    | Material       | float        | ambg                    | 100    | 4    |
| amb                     | Material       | float        | amb                     | 104    | 4    |
| emit                    | Material       | float        | emit                    | 108    | 4    |
| ang                     | Material       | float        | ang                     | 112    | 4    |
| spectra                 | Material       | float        | spectra                 | 116    | 4    |
| ray_mirror              | Material       | float        | ray_mirror              | 120    | 4    |
| alpha                   | Material       | float        | alpha                   | 124    | 4    |
| ref                     | Material       | float        | ref                     | 128    | 4    |
| spec                    | Material       | float        | spec                    | 132    | 4    |
| zoffs                   | Material       | float        | zoffs                   | 136    | 4    |
| add                     | Material       | float        | add                     | 140    | 4    |
| translucency            | Material       | float        | translucency            | 144    | 4    |
| fresnel_mir             | Material       | float        | fresnel_mir             | 148    | 4    |
| fresnel_mir_i           | Material       | float        | fresnel_mir_i           | 152    | 4    |
| fresnel_tra             | Material       | float        | fresnel_tra             | 156    | 4    |
| fresnel_tra_i           | Material       | float        | fresnel_tra_i           | 160    | 4    |
| filter                  | Material       | float        | filter                  | 164    | 4    |
| tx_limit                | Material       | float        | tx_limit                | 168    | 4    |
| tx_falloff              | Material       | float        | tx_falloff              | 172    | 4    |
| ray_depth               | Material       | short        | ray_depth               | 176    | 2    |
| ray_depth_tra           | Material       | short        | ray_depth_tra           | 178    | 2    |
| har                     | Material       | short        | har                     | 180    | 2    |
| seed1                   | Material       | char         | seed1                   | 182    | 1    |
| seed2                   | Material       | char         | seed2                   | 183    | 1    |
| gloss_mir               | Material       | float        | gloss_mir               | 184    | 4    |
| gloss_tra               | Material       | float        | gloss_tra               | 188    | 4    |
| samp_gloss_mir          | Material       | short        | samp_gloss_mir          | 192    | 2    |
| samp_gloss_tra          | Material       | short        | samp_gloss_tra          | 194    | 2    |
| adapt_thresh_mir        | Material       | float        | adapt_thresh_mir        | 196    | 4    |
| adapt_thresh_tra        | Material       | float        | adapt_thresh_tra        | 200    | 4    |
| aniso_gloss_mir         | Material       | float        | aniso_gloss_mir         | 204    | 4    |
| dist_mir                | Material       | float        | dist_mir                | 208    | 4    |
| fadeto_mir              | Material       | short        | fadeto_mir              | 212    | 2    |
| shade_flag              | Material       | short        | shade_flag              | 214    | 2    |
| mode                    | Material       | int          | mode                    | 216    | 4    |
| mode_l                  | Material       | int          | mode_l                  | 220    | 4    |
| flarec                  | Material       | short        | flarec                  | 224    | 2    |
| starc                   | Material       | short        | starc                   | 226    | 2    |
| linec                   | Material       | short        | linec                   | 228    | 2    |
| ringc                   | Material       | short        | ringc                   | 230    | 2    |
| hasize                  | Material       | float        | hasize                  | 232    | 4    |
| flaresize               | Material       | float        | flaresize               | 236    | 4    |
| subsize                 | Material       | float        | subsize                 | 240    | 4    |
| flareboost              | Material       | float        | flareboost              | 244    | 4    |
| strand_sta              | Material       | float        | strand_sta              | 248    | 4    |
| strand_end              | Material       | float        | strand_end              | 252    | 4    |
| strand_ease             | Material       | float        | strand_ease             | 256    | 4    |
| strand_surfnor          | Material       | float        | strand_surfnor          | 260    | 4    |
| strand_min              | Material       | float        | strand_min              | 264    | 4    |
| strand_widthfade        | Material       | float        | strand_widthfade        | 268    | 4    |
| strand_uvname           | Material       | char         | strand_uvname[32]       | 272    | 32   |
| sbias                   | Material       | float        | sbias                   | 304    | 4    |
| lbias                   | Material       | float        | lbias                   | 308    | 4    |
| shad_alpha              | Material       | float        | shad_alpha              | 312    | 4    |
| septex                  | Material       | int          | septex                  | 316    | 4    |
| rgbsel                  | Material       | char         | rgbsel                  | 320    | 1    |
| texact                  | Material       | char         | texact                  | 321    | 1    |
| pr_type                 | Material       | char         | pr_type                 | 322    | 1    |
| use_nodes               | Material       | char         | use_nodes               | 323    | 1    |
| pr_back                 | Material       | short        | pr_back                 | 324    | 2    |
| pr_lamp                 | Material       | short        | pr_lamp                 | 326    | 2    |
| pad4                    | Material       | short        | pad4                    | 328    | 2    |
| ml_flag                 | Material       | short        | ml_flag                 | 330    | 2    |
| diff_shader             | Material       | short        | diff_shader             | 332    | 2    |
| spec_shader             | Material       | short        | spec_shader             | 334    | 2    |
| roughness               | Material       | float        | roughness               | 336    | 4    |
| refrac                  | Material       | float        | refrac                  | 340    | 4    |
| param                   | Material       | float        | param[4]                | 344    | 16   |
| rms                     | Material       | float        | rms                     | 360    | 4    |
| darkness                | Material       | float        | darkness                | 364    | 4    |
| texco                   | Material       | short        | texco                   | 368    | 2    |
| mapto                   | Material       | short        | mapto                   | 370    | 2    |
| ramp_col                | Material       | ColorBand    | *ramp_col               | 372    | 4    |
| ramp_spec               | Material       | ColorBand    | *ramp_spec              | 376    | 4    |
| rampin_col              | Material       | char         | rampin_col              | 380    | 1    |
| rampin_spec             | Material       | char         | rampin_spec             | 381    | 1    |
| rampblend_col           | Material       | char         | rampblend_col           | 382    | 1    |
| rampblend_spec          | Material       | char         | rampblend_spec          | 383    | 1    |
| ramp_show               | Material       | short        | ramp_show               | 384    | 2    |
| pad3                    | Material       | short        | pad3                    | 386    | 2    |
| rampfac_col             | Material       | float        | rampfac_col             | 388    | 4    |
| rampfac_spec            | Material       | float        | rampfac_spec            | 392    | 4    |
| mtex                    | Material       | MTex         | *mtex[18]               | 396    | 72   |
| nodetree                | Material       | bNodeTree    | *nodetree               | 468    | 4    |
| ipo                     | Material       | Ipo          | *ipo                    | 472    | 4    |
| group                   | Material       | Group        | *group                  | 476    | 4    |
| preview                 | Material       | PreviewImage | *preview                | 480    | 4    |
| friction                | Material       | float        | friction                | 484    | 4    |
| fh                      | Material       | float        | fh                      | 488    | 4    |
| reflect                 | Material       | float        | reflect                 | 492    | 4    |
| fhdist                  | Material       | float        | fhdist                  | 496    | 4    |
| xyfrict                 | Material       | float        | xyfrict                 | 500    | 4    |
| dynamode                | Material       | short        | dynamode                | 504    | 2    |
| pad2                    | Material       | short        | pad2                    | 506    | 2    |
| sss_radius              | Material       | float        | sss_radius[3]           | 508    | 12   |
| sss_col                 | Material       | float        | sss_col[3]              | 520    | 12   |
| sss_error               | Material       | float        | sss_error               | 532    | 4    |
| sss_scale               | Material       | float        | sss_scale               | 536    | 4    |
| sss_ior                 | Material       | float        | sss_ior                 | 540    | 4    |
| sss_colfac              | Material       | float        | sss_colfac              | 544    | 4    |
| sss_texfac              | Material       | float        | sss_texfac              | 548    | 4    |
| sss_front               | Material       | float        | sss_front               | 552    | 4    |
| sss_back                | Material       | float        | sss_back                | 556    | 4    |
| sss_flag                | Material       | short        | sss_flag                | 560    | 2    |
| sss_preset              | Material       | short        | sss_preset              | 562    | 2    |
| YF_ar                   | Material       | float        | YF_ar                   | 564    | 4    |
| YF_ag                   | Material       | float        | YF_ag                   | 568    | 4    |
| YF_ab                   | Material       | float        | YF_ab                   | 572    | 4    |
| YF_dscale               | Material       | float        | YF_dscale               | 576    | 4    |
| YF_dpwr                 | Material       | float        | YF_dpwr                 | 580    | 4    |
| YF_dsmp                 | Material       | int          | YF_dsmp                 | 584    | 4    |
| YF_preset               | Material       | int          | YF_preset               | 588    | 4    |
| YF_djit                 | Material       | int          | YF_djit                 | 592    | 4    |
| scriptlink.scripts      | ScriptLink     | ID           | **scripts               | 596    | 4    |
| scriptlink.flag         | ScriptLink     | short        | *flag                   | 600    | 4    |
| scriptlink.actscript    | ScriptLink     | short        | actscript               | 604    | 2    |
| scriptlink.totscript    | ScriptLink     | short        | totscript               | 606    | 2    |
| scriptlink.pad          | ScriptLink     | int          | pad                     | 608    | 4    |
| gpumaterial.first       | ListBase       | void         | *first                  | 612    | 4    |
| gpumaterial.last        | ListBase       | void         | *last                   | 616    | 4    |


### VFontreference  

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| id.next                 | ID             | void         | *next                   | 0      | 4    |
| id.prev                 | ID             | void         | *prev                   | 4      | 4    |
| id.newid                | ID             | ID           | *newid                  | 8      | 4    |
| id.lib                  | ID             | Library      | *lib                    | 12     | 4    |
| id.name                 | ID             | char         | name[24]                | 16     | 24   |
| id.us                   | ID             | short        | us                      | 40     | 2    |
| id.flag                 | ID             | short        | flag                    | 42     | 2    |
| id.icon_id              | ID             | int          | icon_id                 | 44     | 4    |
| id.properties           | ID             | IDProperty   | *properties             | 48     | 4    |
| name                    | VFont          | char         | name[256]               | 52     | 256  |
| scale                   | VFont          | float        | scale                   | 308    | 4    |
| pad                     | VFont          | float        | pad                     | 312    | 4    |
| data                    | VFont          | VFontData    | *data                   | 316    | 4    |
| packedfile              | VFont          | PackedFile   | *packedfile             | 320    | 4    |



### MetaElemreference  

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| next                    | MetaElem       | MetaElem     | *next                   | 0      | 4    |
| prev                    | MetaElem       | MetaElem     | *prev                   | 4      | 4    |
| bb                      | MetaElem       | BoundBox     | *bb                     | 8      | 4    |
| i1                      | MetaElem       | int          | i1                      | 12     | 4    |
| j1                      | MetaElem       | int          | j1                      | 16     | 4    |
| k1                      | MetaElem       | int          | k1                      | 20     | 4    |
| i2                      | MetaElem       | int          | i2                      | 24     | 4    |
| j2                      | MetaElem       | int          | j2                      | 28     | 4    |
| k2                      | MetaElem       | int          | k2                      | 32     | 4    |
| type                    | MetaElem       | short        | type                    | 36     | 2    |
| flag                    | MetaElem       | short        | flag                    | 38     | 2    |
| selcol1                 | MetaElem       | short        | selcol1                 | 40     | 2    |
| selcol2                 | MetaElem       | short        | selcol2                 | 42     | 2    |
| x                       | MetaElem       | float        | x                       | 44     | 4    |
| y                       | MetaElem       | float        | y                       | 48     | 4    |
| z                       | MetaElem       | float        | z                       | 52     | 4    |
| quat                    | MetaElem       | float        | quat[4]                 | 56     | 16   |
| expx                    | MetaElem       | float        | expx                    | 72     | 4    |
| expy                    | MetaElem       | float        | expy                    | 76     | 4    |
| expz                    | MetaElem       | float        | expz                    | 80     | 4    |
| rad                     | MetaElem       | float        | rad                     | 84     | 4    |
| rad2                    | MetaElem       | float        | rad2                    | 88     | 4    |
| s                       | MetaElem       | float        | s                       | 92     | 4    |
| len                     | MetaElem       | float        | len                     | 96     | 4    |
| mat                     | MetaElem       | float        | *mat                    | 100    | 4    |
| imat                    | MetaElem       | float        | *imat                   | 104    | 4    |


### MetaBallreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| id.next                 | ID             | void         | *next                   | 0      | 4    |
| id.prev                 | ID             | void         | *prev                   | 4      | 4    |
| id.newid                | ID             | ID           | *newid                  | 8      | 4    |
| id.lib                  | ID             | Library      | *lib                    | 12     | 4    |
| id.name                 | ID             | char         | name[24]                | 16     | 24   |
| id.us                   | ID             | short        | us                      | 40     | 2    |
| id.flag                 | ID             | short        | flag                    | 42     | 2    |
| id.icon_id              | ID             | int          | icon_id                 | 44     | 4    |
| id.properties           | ID             | IDProperty   | *properties             | 48     | 4    |
| bb                      | MetaBall       | BoundBox     | *bb                     | 52     | 4    |
| elems.first             | ListBase       | void         | *first                  | 56     | 4    |
| elems.last              | ListBase       | void         | *last                   | 60     | 4    |
| disp.first              | ListBase       | void         | *first                  | 64     | 4    |
| disp.last               | ListBase       | void         | *last                   | 68     | 4    |
| ipo                     | MetaBall       | Ipo          | *ipo                    | 72     | 4    |
| mat                     | MetaBall       | Material     | **mat                   | 76     | 4    |
| flag                    | MetaBall       | short        | flag                    | 80     | 2    |
| totcol                  | MetaBall       | short        | totcol                  | 82     | 2    |
| texflag                 | MetaBall       | int          | texflag                 | 84     | 4    |
| loc                     | MetaBall       | float        | loc[3]                  | 88     | 12   |
| size                    | MetaBall       | float        | size[3]                 | 100    | 12   |
| rot                     | MetaBall       | float        | rot[3]                  | 112    | 12   |
| wiresize                | MetaBall       | float        | wiresize                | 124    | 4    |
| rendersize              | MetaBall       | float        | rendersize              | 128    | 4    |
| thresh                  | MetaBall       | float        | thresh                  | 132    | 4    |

### BezTriplereference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| vec                     | BezTriple      | float        | vec[3][3]               | 0      | 12   |
| alfa                    | BezTriple      | float        | alfa                    | 12     | 4    |
| weight                  | BezTriple      | float        | weight                  | 16     | 4    |
| radius                  | BezTriple      | float        | radius                  | 20     | 4    |
| h1                      | BezTriple      | short        | h1                      | 24     | 2    |
| h2                      | BezTriple      | short        | h2                      | 26     | 2    |
| f1                      | BezTriple      | char         | f1                      | 28     | 1    |
| f2                      | BezTriple      | char         | f2                      | 29     | 1    |
| f3                      | BezTriple      | char         | f3                      | 30     | 1    |
| hide                    | BezTriple      | char         | hide                    | 31     | 1    |


### BPointreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| vec                     | BPoint         | float        | vec[4]                  | 0      | 16   |
| alfa                    | BPoint         | float        | alfa                    | 16     | 4    |
| weight                  | BPoint         | float        | weight                  | 20     | 4    |
| f1                      | BPoint         | short        | f1                      | 24     | 2    |
| hide                    | BPoint         | short        | hide                    | 26     | 2    |
| radius                  | BPoint         | float        | radius                  | 28     | 4    |
| pad                     | BPoint         | float        | pad                     | 32     | 4    |


### Nurbreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| next                    | Nurb           | Nurb         | *next                   | 0      | 4    |
| prev                    | Nurb           | Nurb         | *prev                   | 4      | 4    |
| type                    | Nurb           | short        | type                    | 8      | 2    |
| mat_nr                  | Nurb           | short        | mat_nr                  | 10     | 2    |
| hide                    | Nurb           | short        | hide                    | 12     | 2    |
| flag                    | Nurb           | short        | flag                    | 14     | 2    |
| pntsu                   | Nurb           | short        | pntsu                   | 16     | 2    |
| pntsv                   | Nurb           | short        | pntsv                   | 18     | 2    |
| resolu                  | Nurb           | short        | resolu                  | 20     | 2    |
| resolv                  | Nurb           | short        | resolv                  | 22     | 2    |
| orderu                  | Nurb           | short        | orderu                  | 24     | 2    |
| orderv                  | Nurb           | short        | orderv                  | 26     | 2    |
| flagu                   | Nurb           | short        | flagu                   | 28     | 2    |
| flagv                   | Nurb           | short        | flagv                   | 30     | 2    |
| knotsu                  | Nurb           | float        | *knotsu                 | 32     | 4    |
| knotsv                  | Nurb           | float        | *knotsv                 | 36     | 4    |
| bp                      | Nurb           | BPoint       | *bp                     | 40     | 4    |
| bezt                    | Nurb           | BezTriple    | *bezt                   | 44     | 4    |
| tilt_interp             | Nurb           | short        | tilt_interp             | 48     | 2    |
| radius_interp           | Nurb           | short        | radius_interp           | 50     | 2    |
| charidx                 | Nurb           | int          | charidx                 | 52     | 4    |



### CharInforeference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| kern                    | CharInfo       | short        | kern                    | 0      | 2    |
| mat_nr                  | CharInfo       | short        | mat_nr                  | 2      | 2    |
| flag                    | CharInfo       | char         | flag                    | 4      | 1    |
| pad                     | CharInfo       | char         | pad                     | 5      | 1    |
| pad2                    | CharInfo       | short        | pad2                    | 6      | 2    |


### TextBoxreference

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| x                       | TextBox        | float        | x                       | 0      | 4    |
| y                       | TextBox        | float        | y                       | 4      | 4    |
| w                       | TextBox        | float        | w                       | 8      | 4    |
| h                       | TextBox        | float        | h                       | 12     | 4    |


### Curvereference   

| struct field name       | structure      | type         | name                    | offset | size |
|-------------------------|----------------|--------------|-------------------------|--------|------|
| id.next                 | ID             | void         | *next                   | 0      | 4    |
| id.prev                 | ID             | void         | *prev                   | 4      | 4    |
| id.newid                | ID             | ID           | *newid                  | 8      | 4    |
| id.lib                  | ID             | Library      | *lib                    | 12     | 4    |
| id.name                 | ID             | char         | name[24]                | 16     | 24   |
| id.us                   | ID             | short        | us                      | 40     | 2    |
| id.flag                 | ID             | short        | flag                    | 42     | 2    |
| id.icon_id              | ID             | int          | icon_id                 | 44     | 4    |
| id.properties           | ID             | IDProperty   | *properties             | 48     | 4    |
| bb                      | Curve          | BoundBox     | *bb                     | 52     | 4    |
| nurb.first              | ListBase       | void         | *first                  | 56     | 4    |
| nurb.last               | ListBase       | void         | *last                   | 60     | 4    |
| disp.first              | ListBase       | void         | *first                  | 64     | 4    |
| disp.last               | ListBase       | void         | *last                   | 68     | 4    |
