<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/fd_wzbjmu.css';
import '../../css/t/t8ec7tmhe.css';
import '../../css/g/gr6khdcvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="fd_wzbjmu"/><path class="t8ec7tmhe"/><path class="gr6khdcvk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:transition-top" {...props}></Icon>
