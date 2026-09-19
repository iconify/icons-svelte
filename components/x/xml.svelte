<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-m4umibe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j-m4umibe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:xml" {...props}></Icon>
