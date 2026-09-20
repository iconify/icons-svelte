<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fikox4b0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fikox4b0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:toc" {...props}></Icon>
