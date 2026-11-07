<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1nbikbny.css';
import '../../css/h/hd3mzwb_t.css';
import '../../css/y/ydzn23buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g1nbikbny"/><path class="hd3mzwb_t"/><path class="ydzn23buh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sidebar-open-bold-duotone" {...props}></Icon>
