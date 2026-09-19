<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjg9lod-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vjg9lod-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:scribble" {...props}></Icon>
