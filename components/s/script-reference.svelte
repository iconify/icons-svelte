<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y57omyb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y57omyb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:script-reference" {...props}></Icon>
