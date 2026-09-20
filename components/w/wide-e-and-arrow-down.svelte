<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-vfj0b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b-vfj0b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wide-e-and-arrow-down" {...props}></Icon>
