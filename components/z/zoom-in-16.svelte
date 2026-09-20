<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_fpg3b5s.css';
import '../../css/w/wm45_4p5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p_fpg3b5s"/><path clip-rule="evenodd" class="wm45_4p5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:zoom-in-16" {...props}></Icon>
