# 3D Touch

3D Touch adds an additional dimension to touch-based interaction. On supported devices, people can access additional functionality by applying varying levels of pressure to the touchscreen. Apps can respond by displaying a menu, showing additional content, or playing an animation. People don’t need to learn new gestures to interact with 3D Touch. They quickly discover the additional interactive dimension when they press lightly on the screen and get a response.
3D Touch(立體觸控)增加觸控為基礎的互動體驗維度。支援3D觸控的裝置上，使用者對觸控螢幕不同的壓力輕重，讓Apps顯示選單或更詳細的內容或是播放動畫等。來使用這項3D觸控。Apps使用者不需要學習新的手勢，

Home Screen Interaction
On the Home screen, pressing the icon of an app that supports 3D Touch displays an action view. This view lets you quickly perform common app-specific tasks and see interesting information. Calendar, for example, provides a shortcut for creating an event. It also shows the next event on your schedule. For design guidance, see Home Screen Actions and Widgets.
主螢幕的互動
在主螢幕時，點選支援3D觸控的App
Peek and Pop
A peek lets people use 3D Touch to preview an item, such as a page, link, or file, in a view that appears temporarily above the current context. To peek at an item that supports this functionality, apply a little pressure to the item with your finger. Simply lift your finger to exit the peek. To open the item and see more detail, press a little harder until the item pops and fills the screen. In some peek views, you can swipe up to reveal related action buttons. For example, while peeking at a link in Safari, you can swipe up to reveal buttons for opening the link in the background, adding the link to your reading list, and copying the link.

Use peeking to provide live, content-rich previews. Ideally, peeking gives enough information about an item to augment the current task, or helps you decide whether to fully engage the item. For example, preview a link in a Mail message before deciding to open it in Safari or share it with friends. Peeking is often used in tables to view detailed row information before the row is selected.

Design big-enough peek views. Design a peek view that's large enough so that fingers don’t obscure its content. Make the peek detailed enough for people to decide whether to press a little deeper to fully open (pop) the item.
讓peek和pop一致-
Adopt Peek and Pop consistently. If you support Peek and Pop in some places but not others, people won’t know where they can use the feature and may think there’s a problem with your app or their device.
每個peek都可以pop
**Allow every peek to be popped**. Even though peeking should give people most of the information they need, always let them transition to the pop if they decide to switch away from the current task and focus on the item. Popping should show the same thing as tapping the item.
不要讓
**Avoid displaying button-like elements in a peek view.** If a user lifts a finger to tap an element that looks like a button, the peek disappears.

Don’t enable peeking and an edit menu for the same item. It can be confusing to users and hard for the system to detect intent when both features are enabled for one item. For additional guidance, see Edit Menus.

Provide action buttons when appropriate. Not every peek needs action buttons, but they’re a great way to offer shortcuts for common tasks. If your app already provides custom touch-and-hold actions for items, it’s good practice to include the same actions during peeks.

Avoid providing an action button that opens a peeked item. People generally press deeper to open an item they’re peeking. As a result, there’s typically no need to provide an explicit Open button.

Don’t make peek the only way to perform item actions. Not every device supports peek and pop, and some people may turn off 3D Touch. Your app should provide other ways to trigger item actions in situations like these. For example, your app could mirror a peek’s quick actions in a view that appears while touching and holding an item.

**Live Photos**
Apps can incorporate pressure into the photo viewing experience by supporting Live Photos. Live Photos come to life when you press them, using movement and sound to show the moments just before and after the photo was taken. For design guidance, see Live Photos.