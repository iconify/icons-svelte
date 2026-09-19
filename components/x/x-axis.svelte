<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh6i7hbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oh6i7hbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:x-axis" {...props}></Icon>
