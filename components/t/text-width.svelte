<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egbi4eyap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="egbi4eyap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:text-width" {...props}></Icon>
