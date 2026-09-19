<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogctq8daa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ogctq8daa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:users-viewfinder" {...props}></Icon>
