<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd--d5ahu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pd--d5ahu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:steering-wheel-fill" {...props}></Icon>
