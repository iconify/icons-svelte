<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6l_3sb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u6l_3sb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:toggle-off" {...props}></Icon>
