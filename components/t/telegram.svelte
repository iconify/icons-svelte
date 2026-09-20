<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig55c0bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig55c0bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:telegram" {...props}></Icon>
