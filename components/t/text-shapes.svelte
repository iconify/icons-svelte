<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgbb3bemw.css';
import '../../css/u/uykx6e1uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fgbb3bemw"/><path class="uykx6e1uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:text-shapes" {...props}></Icon>
