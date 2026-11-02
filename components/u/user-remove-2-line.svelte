<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqnxifbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqnxifbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-remove-2-line" {...props}></Icon>
