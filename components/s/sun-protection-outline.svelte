<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xltm0abxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xltm0abxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sun-protection-outline" {...props}></Icon>
