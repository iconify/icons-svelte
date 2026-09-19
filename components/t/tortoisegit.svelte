<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-3u1wzsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k-3u1wzsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:tortoisegit" {...props}></Icon>
