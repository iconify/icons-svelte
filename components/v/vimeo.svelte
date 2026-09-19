<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc9fj215m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cc9fj215m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:vimeo" {...props}></Icon>
