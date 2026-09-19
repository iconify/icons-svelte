<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unsnq708q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="unsnq708q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:triangle-left" {...props}></Icon>
