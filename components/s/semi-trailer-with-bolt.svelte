<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld1eu9b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ld1eu9b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:semi-trailer-with-bolt" {...props}></Icon>
