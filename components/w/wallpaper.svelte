<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8fkkvm0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="s8fkkvm0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:wallpaper" {...props}></Icon>
