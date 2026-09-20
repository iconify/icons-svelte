<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyvic_bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gyvic_bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tired-face-with-z-in-circle" {...props}></Icon>
