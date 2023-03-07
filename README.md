# Unofficial Psych Engine Cheat Sheet
MAY BE SHITTY SINCE I'M MAKING THIS IN SCHOOL

## Shader Functions
### initLuaShader(shader:String, glslVersion = 120)

### setSpriteShader(obj:String, shader:String)

### removeSpriteShader(obj:String)

## Global Variable Functions

### getGlobalFromScript(luaFile:String, global:String)

### setGlobalFromScript(luaFile:String, global:String, value:Dynamic)

## Haxe Functions
### runHaxeCode(codeToRun:String)

### addHaxeLibrary(libName:String, libPackage:String)

## Gamepad Input Functions
### anyGamepadJustPressed(name:String)

### anyGamepadJustReleased(name:String)

### anyGamepadPressed(name:String)

### anyGamepadReleased(name:String)

### gamepadAnalogX(id:Int, leftStick:Bool = true)

### gamepadAnalogY(id:Int, leftStick:Bool = true)

### gamepadJustPressed(id:Int, name:String)

### gamepadJustReleased(id:Int, name:String)

### gamepadPressed(id:Int, name:String)

### gamepadReleased(id:Int, name:String)

## Song Functions

### restartSong(skipTransition:Bool = false)

### exitSong(skipTransition:Bool = false)

## Save Functions
### initSaveData(name:String, folder:String = psychenginemods)

### flushSaveData()

### getDataFromSave(name:String, field:String, defaultValue:Dynamic = null)

### setDataFromSave(name:String, field:String, value:Dynamic)

## File Functions
### checkFileExists(filename:String, absolute:Bool = false)

### saveFile(path:String, content:String, absolute:Bool = false)

### deleteFile(path:String, ignoreModFolders:Bool = false)

### getTextFromFile(path:String, ignoreModFolders:Bool = false)

## String Functions
### stringStartsWith(str:String, start:String)

### stringEndsWith(str:String, end:String)

### stringSplit(str:String, split:String)

### stringTrim(str:String)

## Misc. Functions
### loadSong(name:String, difficultyNum:Int = -1)

### doTweenColor(tag:String, vars:String, targetColor:String, duration:Float, ease:String)

### noteTweenDirection(tag:String, note:Int, value:Dynamic, duration:Float, ease:String)

### getMidpointX(var:String)

### getMidpointY(var:String)

### addOffset(obj:String, anim:String, x:Float, y:Float)

### setHealthBarColors(leftHex:String, rightHex:String)

### setTimeBarColors(leftHex:String, rightHex:String)

### screenCenter(obj:String, pos:String = 'xy')

### getRandomInt(min:Int, max:Int, exclude:String)

### getRandomFloat(min:Int, max:Int, exclude:String)

### getRandomBool(chance:Float = 50)

### changePresence(details:String, state:String, smallKeyImage:String, hasStartTimestamps:Bool, endTimestamp:Bool)

