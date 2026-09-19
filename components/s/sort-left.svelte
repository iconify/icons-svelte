<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlk1spbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zlk1spbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:sort-left" {...props}></Icon>
