<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m93uw9bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m93uw9bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:x-circle-fill-24" {...props}></Icon>
