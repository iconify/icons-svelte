<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8q0_-tir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8q0_-tir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-5-line" {...props}></Icon>
