<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyjxwfb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cyjxwfb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:star-16" {...props}></Icon>
