<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl1c57z_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yl1c57z_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:sc" {...props}></Icon>
