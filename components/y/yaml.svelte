<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3jp7-bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c3jp7-bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:yaml" {...props}></Icon>
