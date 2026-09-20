<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m86xyuyka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m86xyuyka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tall-chevron-up" {...props}></Icon>
