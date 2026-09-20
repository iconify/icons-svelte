<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo64tablj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo64tablj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:signal-hexagon" {...props}></Icon>
