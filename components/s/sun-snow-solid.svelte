<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy54agbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy54agbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:sun-snow-solid" {...props}></Icon>
