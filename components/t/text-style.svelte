<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woz-1qbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woz-1qbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:text-style" {...props}></Icon>
