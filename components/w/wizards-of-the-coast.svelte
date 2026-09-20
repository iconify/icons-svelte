<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azi09o8qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="azi09o8qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:wizards-of-the-coast" {...props}></Icon>
