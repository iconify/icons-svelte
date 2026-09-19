<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joehd8b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="joehd8b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:wordpress" {...props}></Icon>
