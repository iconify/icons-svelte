<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd27rseip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="gd27rseip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:square" {...props}></Icon>
