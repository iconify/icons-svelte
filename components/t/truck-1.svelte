<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g43n1dbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="g43n1dbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:truck-1" {...props}></Icon>
