<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfo2c8bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="nfo2c8bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:soccer-11" {...props}></Icon>
