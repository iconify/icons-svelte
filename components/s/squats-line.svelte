<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-x_vrxce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-x_vrxce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:squats-line" {...props}></Icon>
