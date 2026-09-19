<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opxh7ab4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="opxh7ab4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:value-variable" {...props}></Icon>
