<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrzzp4k-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rrzzp4k-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-wrap" {...props}></Icon>
