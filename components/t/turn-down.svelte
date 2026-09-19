<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7792ebiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="h7792ebiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:turn-down" {...props}></Icon>
