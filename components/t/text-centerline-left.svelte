<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3a2dgbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3a2dgbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-centerline-left" {...props}></Icon>
