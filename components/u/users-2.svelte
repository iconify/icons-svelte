<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/w/wlk7cymyb.css';
import '../../css/m/mio52ig2b.css';
import '../../css/y/yh3pvrblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wlk7cymyb"/><circle class="mio52ig2b"/><path class="yh3pvrblm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:users-2" {...props}></Icon>
