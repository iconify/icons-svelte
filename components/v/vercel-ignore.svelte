<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3jil3bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z3jil3bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:vercel-ignore" {...props}></Icon>
