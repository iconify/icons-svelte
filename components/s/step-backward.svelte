<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8v1zhb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="g8v1zhb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:step-backward" {...props}></Icon>
