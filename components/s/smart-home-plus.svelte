<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl-n21a0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl-n21a0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smart-home-plus" {...props}></Icon>
