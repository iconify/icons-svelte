<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu6aho1hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":120,"height":120};
const content = `<path class="vu6aho1hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:webhint" {...props}></Icon>
