<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yve2u8pfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yve2u8pfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:stox" {...props}></Icon>
