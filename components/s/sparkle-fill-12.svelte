<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1f7s7bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="x1f7s7bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sparkle-fill-12" {...props}></Icon>
