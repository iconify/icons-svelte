<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osquvkb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="osquvkb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spyglass" {...props}></Icon>
