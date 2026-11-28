<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmfepibel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmfepibel primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-round-corner-duotone" {...props}></Icon>
