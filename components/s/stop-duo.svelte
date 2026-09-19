<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vib408mob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vib408mob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:stop-duo" {...props}></Icon>
