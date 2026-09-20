<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9zx36l4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9zx36l4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wifi-square-filled" {...props}></Icon>
