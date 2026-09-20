<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enltw_b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="enltw_b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-baht" {...props}></Icon>
