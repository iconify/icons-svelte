<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-bmdtxyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x-bmdtxyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-open-book" {...props}></Icon>
