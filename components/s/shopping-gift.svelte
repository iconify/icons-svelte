<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhnsj164s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fhnsj164s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:shopping-gift" {...props}></Icon>
