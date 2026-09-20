<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9oa8dbac.css';
import '../../css/g/gc5xy5own.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="f9oa8dbac"/><path class="gc5xy5own"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yamtrack" {...props}></Icon>
