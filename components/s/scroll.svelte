<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8j21qb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="i8j21qb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:scroll" {...props}></Icon>
