<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abppvacyo.css';
import '../../css/y/yv427ebbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="abppvacyo"/><path clip-rule="evenodd" class="yv427ebbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:view-page-single-16" {...props}></Icon>
