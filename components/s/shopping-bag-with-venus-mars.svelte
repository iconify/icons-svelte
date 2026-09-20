<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_3iaccdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b_3iaccdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-venus-mars" {...props}></Icon>
