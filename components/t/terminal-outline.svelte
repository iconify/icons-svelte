<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elyxbx7ey.css';
import '../../css/r/r92xs4nql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="elyxbx7ey"/><path class="r92xs4nql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:terminal-outline" {...props}></Icon>
