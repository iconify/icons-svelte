<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj1y1wbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj1y1wbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shell-solid" {...props}></Icon>
