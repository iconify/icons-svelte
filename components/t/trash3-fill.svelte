<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkgg58bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fkgg58bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:trash3-fill" {...props}></Icon>
