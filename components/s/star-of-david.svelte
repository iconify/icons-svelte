<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5nbp-g2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r5nbp-g2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:star-of-david" {...props}></Icon>
