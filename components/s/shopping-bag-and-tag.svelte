<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d94gv9lat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d94gv9lat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-and-tag" {...props}></Icon>
