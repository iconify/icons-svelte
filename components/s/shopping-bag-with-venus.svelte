<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojmfhdbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ojmfhdbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-venus" {...props}></Icon>
