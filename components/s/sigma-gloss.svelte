<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8meee8sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8meee8sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sigma-gloss" {...props}></Icon>
