<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r85lcmtxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r85lcmtxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:split-vertical-solid" {...props}></Icon>
