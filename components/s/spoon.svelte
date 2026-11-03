<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt9f0cb0i.css';
import '../../css/l/lz7k7y3sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="lt9f0cb0i"/><path class="lz7k7y3sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:spoon" {...props}></Icon>
