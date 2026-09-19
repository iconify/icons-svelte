<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruxfll-hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ruxfll-hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sorting-lowest-to-highest-number" {...props}></Icon>
