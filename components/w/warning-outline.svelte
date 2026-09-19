<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7-96frbe.css';
import '../../css/j/jo95-poua.css';
import '../../css/i/iw3w-abnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z7-96frbe"/><path class="jo95-poua"/><path class="iw3w-abnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:warning-outline" {...props}></Icon>
