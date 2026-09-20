<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7s6ydbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e7s6ydbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:tag" {...props}></Icon>
