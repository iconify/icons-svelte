<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrvoa6bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrvoa6bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:yen-square" {...props}></Icon>
