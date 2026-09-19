<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbz8j5yuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wbz8j5yuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:trace" {...props}></Icon>
