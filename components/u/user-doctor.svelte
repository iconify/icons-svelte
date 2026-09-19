<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsnjhj1vj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="tsnjhj1vj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:user-doctor" {...props}></Icon>
