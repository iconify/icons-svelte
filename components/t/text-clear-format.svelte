<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk-frxrct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yk-frxrct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-clear-format" {...props}></Icon>
