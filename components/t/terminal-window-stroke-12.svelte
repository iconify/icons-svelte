<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egjdr5bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="egjdr5bch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:terminal-window-stroke-12" {...props}></Icon>
