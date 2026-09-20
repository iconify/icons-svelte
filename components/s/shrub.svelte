<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycx2subns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycx2subns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shrub" {...props}></Icon>
