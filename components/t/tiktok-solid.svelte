<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljkbb2b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ljkbb2b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tiktok-solid" {...props}></Icon>
