<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixrh7abjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ixrh7abjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-dots-horizontal-in-rectangle" {...props}></Icon>
