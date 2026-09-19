<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe37jgblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fe37jgblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-underline" {...props}></Icon>
