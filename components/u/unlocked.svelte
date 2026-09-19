<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l4t7nkb3h.css';
import '../../css/x/xuyrlebfz.css';
import '../../css/u/ugsg8xbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="l4t7nkb3h"/><path class="xuyrlebfz"/><path class="ugsg8xbov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:unlocked" {...props}></Icon>
