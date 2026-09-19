<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8j8t-uam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="j8j8t-uam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:users" {...props}></Icon>
