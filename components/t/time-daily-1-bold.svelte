<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb5p6obzi.css';
import '../../css/o/ow-wen-ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sb5p6obzi"/><path class="ow-wen-ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:time-daily-1-bold" {...props}></Icon>
