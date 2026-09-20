<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1fr8ybcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u1fr8ybcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:vr-headset-2-solid" {...props}></Icon>
