<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3qka0b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e3qka0b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-tap-with-handle-and-drinking-glass" {...props}></Icon>
