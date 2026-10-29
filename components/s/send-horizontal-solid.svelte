<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwk_-hbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwk_-hbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:send-horizontal-solid" {...props}></Icon>
