<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl551cj4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hl551cj4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:south-dakota-with-capital-star" {...props}></Icon>
