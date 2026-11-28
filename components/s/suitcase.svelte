<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf9p40zkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf9p40zkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:suitcase" {...props}></Icon>
