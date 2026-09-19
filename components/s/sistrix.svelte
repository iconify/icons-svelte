<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j88m44res.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j88m44res"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:sistrix" {...props}></Icon>
