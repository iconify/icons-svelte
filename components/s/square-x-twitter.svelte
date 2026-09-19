<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r483jr0qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="r483jr0qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-x-twitter" {...props}></Icon>
