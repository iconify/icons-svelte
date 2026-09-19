<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6zyj1bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="g6zyj1bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:school" {...props}></Icon>
