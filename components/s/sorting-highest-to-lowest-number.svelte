<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yimeyobhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yimeyobhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sorting-highest-to-lowest-number" {...props}></Icon>
