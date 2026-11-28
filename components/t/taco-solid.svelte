<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw2s-n17k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nw2s-n17k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:taco-solid" {...props}></Icon>
