<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr42wnp1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sr42wnp1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:toilet-sign-man-solid" {...props}></Icon>
