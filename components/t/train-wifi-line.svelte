<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7rcmwb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7rcmwb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:train-wifi-line" {...props}></Icon>
