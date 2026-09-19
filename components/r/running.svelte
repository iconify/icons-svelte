<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfi69eb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":512};
const content = `<path class="hfi69eb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:running" {...props}></Icon>
