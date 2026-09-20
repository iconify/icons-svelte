<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6kp0_bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6kp0_bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:text-align-left-box" {...props}></Icon>
