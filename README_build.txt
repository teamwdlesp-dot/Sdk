Build AAR (Bcore):

1) Open project in AndroidIDE
2) Run Gradle task:
   :Bcore:assembleRelease

Or terminal:
   ./gradlew :Bcore:assembleRelease

Output:
   Bcore/build/outputs/aar/Bcore-release.aar

Copy that AAR into your loader project's app/libs/ folder.

Note (libs AAR): add runtime deps in loader:
  implementation "me.weishu:free_reflection:3.0.1"
  implementation "com.github.CodingGay.BlackReflection:core:1.1.2"
