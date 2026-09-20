<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbxb9zycx.css';
import '../../css/u/uu386rb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="nbxb9zycx"/><path class="uu386rb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:white-small-square" {...props}></Icon>
