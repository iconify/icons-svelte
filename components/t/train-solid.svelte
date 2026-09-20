<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nepuf8mxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nepuf8mxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:train-solid" {...props}></Icon>
