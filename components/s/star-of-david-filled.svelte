<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf6tcylxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jf6tcylxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:star-of-david-filled" {...props}></Icon>
