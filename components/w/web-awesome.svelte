<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyuxx_bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="iyuxx_bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:web-awesome" {...props}></Icon>
