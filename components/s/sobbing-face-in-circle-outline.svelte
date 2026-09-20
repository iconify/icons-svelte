<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sllvyibzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sllvyibzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sobbing-face-in-circle-outline" {...props}></Icon>
