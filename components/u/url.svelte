<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryq49vj0z.css';
import '../../css/i/iz9ll_bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ryq49vj0z"/><path class="iz9ll_bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:url" {...props}></Icon>
