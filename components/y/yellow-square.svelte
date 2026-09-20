<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csh1a7bzc.css';
import '../../css/t/tbzab391z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="csh1a7bzc"/><path class="tbzab391z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:yellow-square" {...props}></Icon>
