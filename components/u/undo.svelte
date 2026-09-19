<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhd4-8i0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jhd4-8i0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:undo" {...props}></Icon>
