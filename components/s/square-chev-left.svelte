<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiksrrvez.css';
import '../../css/x/xwlsu8bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hiksrrvez"/><path class="xwlsu8bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:square-chev-left" {...props}></Icon>
