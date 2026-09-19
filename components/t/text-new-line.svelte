<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/achj8hlrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="achj8hlrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-new-line" {...props}></Icon>
