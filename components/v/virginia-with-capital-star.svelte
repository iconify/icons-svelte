<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeqlbnbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eeqlbnbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:virginia-with-capital-star" {...props}></Icon>
