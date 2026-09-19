<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n11l6w7ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n11l6w7ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:staircase" {...props}></Icon>
