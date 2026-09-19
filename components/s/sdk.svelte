<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3hhpg6el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f3hhpg6el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sdk" {...props}></Icon>
