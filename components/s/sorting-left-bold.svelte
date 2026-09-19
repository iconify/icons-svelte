<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgi-m9epy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgi-m9epy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sorting-left-bold" {...props}></Icon>
