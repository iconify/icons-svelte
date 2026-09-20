<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/effkhktdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="effkhktdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:toilet-sign-man-woman-2-solid" {...props}></Icon>
