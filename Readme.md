in /home/ubuntu/Project/Ramin/Portainer/sources_front/main.css

app-react-sidebar-Sidebar-module__root{display:none;width:var(--sidebar-width)}.app-react-sidebar-Sidebar-module__root{height:100%;left:0;position:fixed;-webkit-transition:all .4s ease 0s;transition:all .4s ease 0s;width:var(--sidebar-closed-width);z-index:10}.app-react-sidebar-Sidebar-module__nav{display:none;background-color:var(--bg-sidebar-color)}.app-react-sidebar-Sidebar-module__root

#page-wrapper{--sidebar-width:0px;--sidebar-closed-width:72px}


and for some tabs or buttons which are created dynamically by js we do:

<!-- <button authorization="DockerContainerStart" class="btn btn-light btn-sm" ng-click="start()" ng-disabled="container.State.Running || container.IsPortainer">\n            <pr-icon icon="\'play\'"></pr-icon>\n            Start\n          </button>\n

<button authorization="DockerContainerStart" class="btn btn-light btn-sm" ng-click="start()" ng-disabled="true">\n            <pr-icon icon="\'play\'"></pr-icon>\n            Start\n          </button>\n -->