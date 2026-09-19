<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7i1p681y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="d7i1p681y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tv-music-note-fill" {...props}></Icon>
