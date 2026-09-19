<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aywe44bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":380,"height":700};
const content = `<path class="aywe44bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:small-arrow-down" {...props}></Icon>
