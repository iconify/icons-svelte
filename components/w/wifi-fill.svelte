<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw7glvfrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sw7glvfrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wifi-fill" {...props}></Icon>
