<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5dvmebfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":448};
const content = `<path class="y5dvmebfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:triangle" {...props}></Icon>
