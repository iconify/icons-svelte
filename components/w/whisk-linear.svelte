<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0h_4qbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0h_4qbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:whisk-linear" {...props}></Icon>
