<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uog2ysb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uog2ysb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:scales-tipped" {...props}></Icon>
