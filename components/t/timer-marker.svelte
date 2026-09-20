<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg9gvxw4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg9gvxw4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-marker" {...props}></Icon>
