<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc3w75-_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dc3w75-_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:splash-up" {...props}></Icon>
