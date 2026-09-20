<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx1qh9vvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx1qh9vvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tags-off" {...props}></Icon>
