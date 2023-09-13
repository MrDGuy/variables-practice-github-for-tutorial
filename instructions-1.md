m# Robot Exam Coding Assignment

## Make code which reaches the goal @unplugged

This coding assignment is worth 5 points:
1. 1 Point Earned if Code Runs without Errors
2. 1 Point Earned if Robot Reaches the Goal and Collects all the Coins.
3. 2 Points for using 2 of the following: While, Function, For Loop or If statement
4. 1 Point Earned if you use only 1 while loop to complete the entire tilemap.


## Make code which reaches the goal

This coding assignment is worth 5 points:
1. 1 Point Earned if Code Runs without Errors
2. 1 Point Earned if Robot Reaches the Goal and Collects all the Coins.
3. 2 Points for using 2 of the following: While, Function, For Loop or If statement
4. 1 Point Earned if you use only 1 while loop to complete the entire tilemap.
   
Use the commands and conditions in the robot category.
```python
    robot.begin_screen()
    robot.move_forward()
    robot.turn_right()
    robot.turn_left()
    robot.place_coin()
    robot.collect_coin()
    robot.detect_coin()
    robot.can_move("")
    robot.goal_reached()
```

## Functions, Loops and If Statements

2 Points are Earned For for using 2 of the following: Function, For Loop or If statement

```python
  def move_3_times():
    robot.move_forward()
    robot.move_forward()
    robot.move_forward()

  while robot.goal_reached() == False:
    pass

  for i in range(4):
    robot.move_forward()

  if robot.detect_coin():
    robot.collect_coin():

  if robot.can_move("forward"):
    robot.move_forward()
  else:
    robot.turn_left()
    robot.turn_left()
```

## Share your work to Google Classroom  

Be sure to share your code by clicking the share icon and sharing the link to Google Classroom.
![Share Icon](https://github.com/MrDGuy/robot-quiz-code-assignment-1/blob/24c88c502ccd146fc1be1352949c18ee918a8f30/share-icon.png "Share Icon" )

```assetjson
{
  "README.md": " ",
  "assets.json": "",
  "main.blocks": "<xml xmlns=\"https://developers.google.com/blockly/xml\"><block type=\"pxt-on-start\" x=\"0\" y=\"0\"></block></xml>",
  "main.py": "\n\n\n",
  "main.ts": "\n",
  "pxt.json": "{\n    \"name\": \"Robot Test Coding Assignment Assets\",\n    \"description\": \"\",\n    \"dependencies\": {\n        \"device\": \"*\",\n        \"Robot Extension\": \"github:MrDGuy/robot-extension#9c77349a3fe19cbb531500cdbc71c8ad1443b174\"\n    },\n    \"files\": [\n        \"main.blocks\",\n        \"main.ts\",\n        \"README.md\",\n        \"assets.json\",\n        \"main.py\",\n        \"tilemap.g.jres\",\n        \"tilemap.g.ts\"\n    ],\n    \"targetVersions\": {\n        \"branch\": \"v1.13.37\",\n        \"tag\": \"v1.13.37\",\n        \"commits\": \"https://github.com/microsoft/pxt-arcade/commits/f538f544699a0cf30bc4178a7a7b10440cd7dff3\",\n        \"target\": \"1.13.37\",\n        \"pxt\": \"9.1.13\"\n    },\n    \"preferredEditor\": \"pyprj\"\n}\n",
  "tilemap.g.jres": "{\n    \"transparency16\": {\n        \"data\": \"hwQQABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true\n    },\n    \"tile1\": {\n        \"data\": \"hwQQABAAAAD//////////09ERERERET0T0RERERERPRPRERERERE9E9ERERERET0T0RERERERPRPRERERERE9E9ERERERET0T0RERERERPRPRERERERE9E9ERERERET0T0RERERERPRPRERERERE9E9ERERERET0T0RERERERPT//////////w==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true,\n        \"displayName\": \"startTile\"\n    },\n    \"tile2\": {\n        \"data\": \"hwQQABAAAAD//////////4+IiIiIiIj4j4iIiIiIiPiPiIiIiIiI+I+IiIiIiIj4j4iIiIiIiPiPiIiIiIiI+I+IiIiIiIj4j4iIiIiIiPiPiIiIiIiI+I+IiIiIiIj4j4iIiIiIiPiPiIiIiIiI+I+IiIiIiIj4j4iIiIiIiPj//////////w==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true,\n        \"displayName\": \"goalTile\"\n    },\n    \"tile3\": {\n        \"data\": \"hwQQABAAAAD//////////393d3d3d3f3f3d3d3d3d/d/d3d3d3d39393d3d3d3f3f3d3d3d3d/d/d3d3d3d39393d3d3d3f3f3d3d3d3d/d/d3d3d3d39393d3d3d3f3f3d3d3d3d/d/d3d3d3d39393d3d3d3f3f3d3d3d3d/f//////////w==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true,\n        \"displayName\": \"coinTile\"\n    },\n    \"tile4\": {\n        \"data\": \"hwQQABAAAAD//////////x8RERERERHxHxEREREREfEfERERERER8R8RERERERHxHxEREREREfEfERERERER8R8RERERERHxHxEREREREfEfERERERER8R8RERERERHxHxEREREREfEfERERERER8R8RERERERHxHxEREREREfH//////////w==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true,\n        \"displayName\": \"floorTile\"\n    },\n    \"tile5\": {\n        \"data\": \"hwQQABAAAAD//////////7+7u7u7u7v7v7u7u7u7u/u/u7u7u7u7+7+7u7u7u7v7v7u7u7u7u/u/u7u7u7u7+7+7u7u7u7v7v7u7u7u7u/u/u7u7u7u7+7+7u7u7u7v7v7u7u7u7u/u/u7u7u7u7+7+7u7u7u7v7v7u7u7u7u/v//////////w==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true,\n        \"displayName\": \"wallTile\"\n    },\n    \"tile8\": {\n        \"data\": \"hwQQABAAAAB3d3d3zMx3d3d3d8zLy3x3d3d33Lu8zHd3d8zcvbzMd8fMu7zdzMx3vN27y93LzHfc3d2728vMfNvd3bvby7x8293du9u7vMvb3d2929u8y7fd3b3b27zLd9vdvb3bvMt32927vb27fHe3u7u7zbt8d3d3293My3d3d3e3y7x7dw==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true,\n        \"displayName\": \"rock1\"\n    },\n    \"tile9\": {\n        \"data\": \"hwQQABAAAAB3d3fMfHd3d3d3zMbMfHd3d8dmZszMd3d3x2ZnbMZ3d3dsdmdm9nx3d2x3dmf8T3fHZndnZ2b8fsdnV3fGZvzux3d3Z2fM/O7HVWdmZ/bPd2dVd2dn/Hznd3Z1Z2bG73R3xnZWZ8Z/d3fHbHbG/Hd3d3fMZsZ8d3d3d8fMzHd3dw==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true,\n        \"displayName\": \"myTile1\"\n    },\n    \"tile10\": {\n        \"data\": \"hwQQABAAAAB3d3fMd3d3d3d3Z8fMfHd3d3dsx3x8d3d3Z2xnd3x3d8fMx2ZmzHd+x8ZnbGZ35n7HfHfHdsfvd2xVd2xm9u7uXFV3Zmb/7u7HfHVnd8fud2fHZ2Z3d+x+Z2bHd2fMd353Z8x3d3x3d3d3Zmd8fHd3d3dnZ8Z8d3d3d3dmd3d3dw==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true,\n        \"displayName\": \"myTile2\"\n    },\n    \"tile11\": {\n        \"data\": \"hwQQABAAAAB3d2ZnZnx3d3d3Zsx2xmx3d2d2bHfMZnZ3Z3Vsd1x3ZnfMdWZnVnVmx8ZVZmx3ZcZmZ3ZnzGZmfHZVZ8bMfFdmdld1xsx8V2dmZ1ZlzGZmZsfGVWdsd2V8d8x1ZmdWdcZ3Z3dsd1x3Zndndmx3zGZ2d3d2xnbGbHd3d2ZnZnx3dw==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true,\n        \"displayName\": \"myTile3\"\n    },\n    \"level2\": {\n        \"id\": \"level2\",\n        \"mimeType\": \"application/mkcd-tilemap\",\n        \"data\": \"MTAwYTAwMDcwMDA0MDQwNDBhMDUwYTA0MGEwNTBiMDkwMTBkMGQwZDBkMDUwZDBkMDQwNTBlMDMxMTBmMGYxNDEyMGQwYzA5MTMxNDEwMGQwNTA1MTMxMjA0MDQwNDA0MDQxMTE0MTIwMzBlMGMwOTAyMGYwZjEwMDMxMzBmMTAwYzA3MDYwNjA2MDYwNjA2MDYwNjA4MjIyMjIyMjIyMjAyMjIyMjIyMjIwMjAyMDAwMDIyMDIwMDIyMDIyMDIyMjIwMDIwMjAwMjAwMjAwMDIwMjIyMjIyMjIyMg==\",\n        \"tileset\": [\n            \"myTiles.transparency16\",\n            \"myTiles.tile1\",\n            \"myTiles.tile2\",\n            \"myTiles.tile8\",\n            \"myTiles.tile9\",\n            \"myTiles.tile10\",\n            \"sprites.skillmap.islandTile7\",\n            \"sprites.skillmap.islandTile6\",\n            \"sprites.skillmap.islandTile8\",\n            \"sprites.skillmap.islandTile3\",\n            \"sprites.skillmap.islandTile1\",\n            \"sprites.skillmap.islandTile2\",\n            \"sprites.skillmap.islandTile5\",\n            \"sprites.skillmap.islandTile4\",\n            \"sprites.vehicle.roadVertical\",\n            \"sprites.vehicle.roadHorizontal\",\n            \"sprites.vehicle.roadTurn4\",\n            \"sprites.vehicle.roadTurn1\",\n            \"sprites.vehicle.roadTurn2\",\n            \"sprites.vehicle.roadTurn3\",\n            \"myTiles.tile3\"\n        ],\n        \"displayName\": \"level1\"\n    },\n    \"*\": {\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"dataEncoding\": \"base64\",\n        \"namespace\": \"myTiles\"\n    }\n}",
  "tilemap.g.ts": "// Auto-generated code. Do not edit.\nnamespace myTiles {\n    //% fixedInstance jres blockIdentity=images._tile\n    export const transparency16 = image.ofBuffer(hex``);\n    //% fixedInstance jres blockIdentity=images._tile\n    export const tile1 = image.ofBuffer(hex``);\n    //% fixedInstance jres blockIdentity=images._tile\n    export const tile2 = image.ofBuffer(hex``);\n    //% fixedInstance jres blockIdentity=images._tile\n    export const tile3 = image.ofBuffer(hex``);\n    //% fixedInstance jres blockIdentity=images._tile\n    export const tile4 = image.ofBuffer(hex``);\n    //% fixedInstance jres blockIdentity=images._tile\n    export const tile5 = image.ofBuffer(hex``);\n    //% fixedInstance jres blockIdentity=images._tile\n    export const tile8 = image.ofBuffer(hex``);\n    //% fixedInstance jres blockIdentity=images._tile\n    export const tile9 = image.ofBuffer(hex``);\n    //% fixedInstance jres blockIdentity=images._tile\n    export const tile10 = image.ofBuffer(hex``);\n    //% fixedInstance jres blockIdentity=images._tile\n    export const tile11 = image.ofBuffer(hex``);\n\n    helpers._registerFactory(\"tilemap\", function(name: string) {\n        switch(helpers.stringTrim(name)) {\n            case \"level1\":\n            case \"level2\":return tiles.createTilemap(hex`0a0007000404040a050a040a050b09010d0d0d0d050d0d04050e03110f0f14120d0c091314100d050513120404040404111412030e0c09020f0f1003130f100c07060606060606060608`, img`\n2 2 2 2 2 2 2 2 2 2 \n2 . 2 2 2 2 2 2 2 2 \n2 . 2 . . . . . 2 2 \n2 . . . 2 2 2 . . 2 \n2 2 2 2 . . . 2 . 2 \n2 . . . . 2 . . . 2 \n2 2 2 2 2 2 2 2 2 2 \n`, [myTiles.transparency16,myTiles.tile1,myTiles.tile2,myTiles.tile8,myTiles.tile9,myTiles.tile10,sprites.skillmap.islandTile7,sprites.skillmap.islandTile6,sprites.skillmap.islandTile8,sprites.skillmap.islandTile3,sprites.skillmap.islandTile1,sprites.skillmap.islandTile2,sprites.skillmap.islandTile5,sprites.skillmap.islandTile4,sprites.vehicle.roadVertical,sprites.vehicle.roadHorizontal,sprites.vehicle.roadTurn4,sprites.vehicle.roadTurn1,sprites.vehicle.roadTurn2,sprites.vehicle.roadTurn3,myTiles.tile3], TileScale.Sixteen);\n        }\n        return null;\n    })\n\n    helpers._registerFactory(\"tile\", function(name: string) {\n        switch(helpers.stringTrim(name)) {\n            case \"transparency16\":return transparency16;\n            case \"startTile\":\n            case \"tile1\":return tile1;\n            case \"goalTile\":\n            case \"tile2\":return tile2;\n            case \"coinTile\":\n            case \"tile3\":return tile3;\n            case \"floorTile\":\n            case \"tile4\":return tile4;\n            case \"wallTile\":\n            case \"tile5\":return tile5;\n            case \"rock1\":\n            case \"tile8\":return tile8;\n            case \"myTile1\":\n            case \"tile9\":return tile9;\n            case \"myTile2\":\n            case \"tile10\":return tile10;\n            case \"myTile3\":\n            case \"tile11\":return tile11;\n        }\n        return null;\n    })\n\n}\n// Auto-generated code. Do not edit.\n"
}
```


```customts
tiles.loadMap(tiles.createMap(tilemap`level1`))
robot.beginScreen()
game.onUpdate(function () {
    if (robot.goalReached()) {
        music.play(music.melodyPlayable(music.powerUp), music.PlaybackMode.UntilDone)
        game.splash("You reached the goal!")
        game.reset()
    }
})
```
