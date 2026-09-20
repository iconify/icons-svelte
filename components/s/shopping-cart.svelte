<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed9y2pb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ed9y2pb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:shopping-cart" {...props}></Icon>
