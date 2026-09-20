<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsejinj5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nsejinj5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:volume-down-ltr" {...props}></Icon>
