<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t49-fcc2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="t49-fcc2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:tiktok" {...props}></Icon>
