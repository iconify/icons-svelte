<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgis7cprr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgis7cprr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:up-angle-arrow" {...props}></Icon>
