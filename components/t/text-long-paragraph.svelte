<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7-0lx72p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v7-0lx72p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-long-paragraph" {...props}></Icon>
