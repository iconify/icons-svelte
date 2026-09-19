<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy0o8cbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jy0o8cbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:w" {...props}></Icon>
