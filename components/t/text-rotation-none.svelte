<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsk6of0ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fsk6of0ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:text-rotation-none" {...props}></Icon>
