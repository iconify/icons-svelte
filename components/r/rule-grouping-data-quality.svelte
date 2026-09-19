<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_s7ombqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b_s7ombqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rule-grouping-data-quality" {...props}></Icon>
