<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp6sracwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jp6sracwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:webcam-fill" {...props}></Icon>
