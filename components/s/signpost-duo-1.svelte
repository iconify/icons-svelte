<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xskbo8bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xskbo8bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:signpost-duo-1" {...props}></Icon>
