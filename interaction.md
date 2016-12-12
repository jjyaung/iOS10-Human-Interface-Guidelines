# 3D Touch

3D Touch adds an additional dimension to touch-based interaction. On supported devices, people can access additional functionality by applying varying levels of pressure to the touchscreen. Apps can respond by displaying a menu, showing additional content, or playing an animation. People don’t need to learn new gestures to interact with 3D Touch. They quickly discover the additional interactive dimension when they press lightly on the screen and get a response.

## Home Screen Interaction

On the Home screen, pressing the icon of an app that supports 3D Touch displays an action view. This view lets you quickly perform common app-specific tasks and see interesting information. Calendar, for example, provides a shortcut for creating an event. It also shows the next event on your schedule. For design guidance, see Home Screen Actions and Widgets.

在支持3D Touch的设备的主屏按压应用图标会触发相应的操作视图。该视图让你能够快速地执行常用的应用任务和预览有趣的信息，譬如日历应用，它能够提供创建新事件的快捷操作，同时显示日程表上的下一个事件。了解相关设计指导，请参阅Home Screen Action和Widgets。

## Peek and Pop

A peek lets people use 3D Touch to preview an item, such as a page, link, or file, in a view that appears temporarily above the current context. To peek at an item that supports this functionality, apply a little pressure to the item with your finger. Simply lift your finger to exit the peek. To open the item and see more detail, press a little harder until the item pops and fills the screen. In some peek views, you can swipe up to reveal related action buttons. For example, while peeking at a link in Safari, you can swipe up to reveal buttons for opening the link in the background, adding the link to your reading list, and copying the link.

轻压允许用户使用3D Touch在当前环境上预览一个临时视图内的对象，譬如一个页面、链接或者文件。要想在支持该功能的设备上实现预览，只需用手指对应用施加一点压力，而抬起手指就能退出预览。要想打开对象来浏览更多的内容，请更重地按压屏幕直到对象放大到填满屏幕。在一些轻压视图上，你可以通过上滑来显示相应的操作按钮。譬如，在Safari打开了某个链接的轻压视图时，你可以通过上滑展开相应的操作按钮——打开链接，添加至阅读列表和复制链接。

**Use peeking to provide live, content-rich previews. **Ideally, peeking gives enough information about an item to augment the current task, or helps you decide whether to fully engage the item. For example, preview a link in a Mail message before deciding to open it in Safari or share it with friends. Peeking is often used in tables to view detailed row information before the row is selected.

利用轻压视图提供实时的，内容丰富的预览

理想情况下，轻压视图为该项提供足够的信息以补充说明当前任务，或者帮助你决定是否完全地打开该项。例如，预览邮件（Mail）信息中的链接，从而决定是否在Safari浏览器中打开或者分享给朋友。轻压视图一般被利用于表单视图中,提供一个行项的详细信息，从而决定是否选择该项。

**Design big-enough peek views**. Design a peek view that's large enough so that fingers don’t obscure its content. Make the peek detailed enough for people to decide whether to press a little deeper to fully open \(pop\) the item.

**设计足够大的轻压视图**

设计一个足够大的轻压视图从而保证手指不会遮挡到内容。确保轻压视图能够提供足够详细的信息，以便用户决定是否按地更重来完全地打开该项。

**Adopt Peek and Pop consistently**. If you support Peek and Pop in some places but not others, people won’t know where they can use the feature and may think there’s a problem with your app or their device.



Allow every peek to be popped. Even though peeking should give people most of the information they need, always let them transition to the pop if they decide to switch away from the current task and focus on the item. Popping should show the same thing as tapping the item.

Avoid displaying button-like elements in a peek view. If a user lifts a finger to tap an element that looks like a button, the peek disappears.

Don’t enable peeking and an edit menu for the same item. It can be confusing to users and hard for the system to detect intent when both features are enabled for one item. For additional guidance, see Edit Menus.

Provide action buttons when appropriate. Not every peek needs action buttons, but they’re a great way to offer shortcuts for common tasks. If your app already provides custom touch-and-hold actions for items, it’s good practice to include the same actions during peeks.

Avoid providing an action button that opens a peeked item. People generally press deeper to open an item they’re peeking. As a result, there’s typically no need to provide an explicit Open button.  
避免讓peek後的項目有按鈕可按。因為當使用者深壓的時候，已經預期開啟某個項目了。  
Don’t make peek the only way to perform item actions. Not every device supports peek and pop, and some people may turn off 3D Touch. Your app should provide other ways to trigger item actions in situations like these. For example, your app could mirror a peek’s quick actions in a view that appears while touching and holding an item.

**Live Photos**  
Apps can incorporate pressure into the photo viewing experience by supporting Live Photos. Live Photos come to life when you press them, using movement and sound to show the moments just before and after the photo was taken. For design guidance, see Live Photos.

