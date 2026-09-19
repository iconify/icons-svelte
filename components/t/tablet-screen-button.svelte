<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiix5obts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="hiix5obts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tablet-screen-button" {...props}></Icon>
