<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzhq6p0xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzhq6p0xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:up-line" {...props}></Icon>
