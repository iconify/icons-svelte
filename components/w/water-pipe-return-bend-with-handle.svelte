<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isaurbc7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="isaurbc7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-pipe-return-bend-with-handle" {...props}></Icon>
