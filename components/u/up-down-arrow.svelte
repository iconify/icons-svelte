<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7cjjcbnv.css';
import '../../css/w/w82a4gxog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="x7cjjcbnv"/><path class="w82a4gxog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:up-down-arrow" {...props}></Icon>
