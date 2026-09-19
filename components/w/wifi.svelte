<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llbqrh8ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="llbqrh8ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:wifi" {...props}></Icon>
