<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egub1acbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="egub1acbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:texas-with-capital-star" {...props}></Icon>
