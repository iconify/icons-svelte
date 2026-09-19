<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crhxl_b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crhxl_b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:sticky-note" {...props}></Icon>
