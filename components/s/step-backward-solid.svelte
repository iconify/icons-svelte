<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw9gdt5eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bw9gdt5eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:step-backward-solid" {...props}></Icon>
