Have you ever seen a project that **eats more and more memory**, or GDI resources, and suddenly becomes **unresponsive**? Have you ever forgotten to call `Destroy` when an object is not required anymore? A handle that was not closed. A memory block that was not freed.

Yes, it happens... **Deleaker** to the rescue when you need to fix leaks right now! Just take snapshots, review leaked objects and resources with detailed call stacks that help locate source code where leaks occurred.

We are happy to offer **20% Off** for attendees of DelphiCon 2020 Worldwide event. The coupon code **DELPHICON2020** is valid till November 27th.

Deleaker is a tool to find leaks of any kind in applications written in Delphi and C++ Builder, it tightly integrates with RAD Studio and also can work as a standalone tool. 

Want to see Deleaker in action? Get [14-days fully-functional trial](https://www.deleaker.com/download.html).

Prefer to watch the video? Here the tutorial on how Deleaker works:
https://www.youtube.com/watch?v=yDyq2zdpAVA

After installation, Deleaker is added to RAD Studio:

![Deleaker menu](https://github.com/ArtemRazin/DelphiCon2020Promo/blob/main/deleaker_menu_rad_studio%5B1%5D.gif?raw=true)

The resource usage graph displays memory usage, GDI objects and handles count in live mode:

![Resource usage graph](https://github.com/ArtemRazin/DelphiCon2020Promo/blob/main/resource_usage_graph%5B1%5D.gif?raw=true)

A snapshot contains allocated memory, handles, GDI resources, and objects that are grouped by class name. For each object you can review a detailed call stack to find where the object was instantiated:

![Allocated objects](https://github.com/ArtemRazin/DelphiCon2020Promo/blob/main/snapshot_on_exit%5B1%5D.gif?raw=true)
