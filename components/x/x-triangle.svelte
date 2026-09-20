<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-l9c4vor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-l9c4vor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:x-triangle" {...props}></Icon>
