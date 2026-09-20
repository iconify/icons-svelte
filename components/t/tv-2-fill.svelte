<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2-1tbeio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2-1tbeio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:tv-2-fill" {...props}></Icon>
