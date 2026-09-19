<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8_pp3b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8_pp3b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:up-arrow-circle" {...props}></Icon>
