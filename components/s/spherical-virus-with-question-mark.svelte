<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y05ag6itt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y05ag6itt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spherical-virus-with-question-mark" {...props}></Icon>
