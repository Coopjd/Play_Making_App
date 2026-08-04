# Play

- id: number
- name: string
- description: string
- players: Player[]
- ballHandlerId: number

# Player
- id: number
- name: string
- position: string
- x: number
- y: number
- movement: RoutePoint[]

# RoutePoint
- x: number
- y: number
- action: string

# Possible actions
- move
- dribble
- pass
- screen
- shoot