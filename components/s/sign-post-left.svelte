<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otumz-d4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="otumz-d4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:sign-post-left" {...props}></Icon>
