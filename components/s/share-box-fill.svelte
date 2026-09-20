<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6fy3d2pj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6fy3d2pj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:share-box-fill" {...props}></Icon>
