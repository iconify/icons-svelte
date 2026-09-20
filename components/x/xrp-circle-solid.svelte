<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnhi5mopy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hnhi5mopy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:xrp-circle-solid" {...props}></Icon>
