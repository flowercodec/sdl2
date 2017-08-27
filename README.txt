Modify the implementation of SDL_CreateWindowFrom
Support Qt sub-component rendering (pass NSView instead of NSWindow)

QWidget* widget;	///< a sub-component 
SDL_CreateWindowFrom((void*)widget->winId());