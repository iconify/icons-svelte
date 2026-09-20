<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf68w40sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pf68w40sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:vercel-light" {...props}></Icon>
