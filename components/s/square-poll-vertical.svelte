<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxyqtbbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="sxyqtbbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-poll-vertical" {...props}></Icon>
