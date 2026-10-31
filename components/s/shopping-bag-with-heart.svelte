<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr7lizbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sr7lizbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-heart" {...props}></Icon>
