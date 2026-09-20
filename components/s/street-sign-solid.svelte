<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp2fribyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rp2fribyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:street-sign-solid" {...props}></Icon>
