<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/p/p7kgkobvq.css';
import '../../css/g/gyw8t7bmz.css';
import '../../css/d/dlvzn3b3n.css';
import '../../css/w/wsfagf5nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="p7kgkobvq wm-shadow"/><path class="gyw8t7bmz wm-shadow"/><path class="dlvzn3b3n"/><path class="wsfagf5nt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:vr-headset" {...props}></Icon>
