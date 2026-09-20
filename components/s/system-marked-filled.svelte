<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0lx0cb_d.css';
import '../../css/w/wmq89w7_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0lx0cb_d"/><path class="wmq89w7_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-marked-filled" {...props}></Icon>
