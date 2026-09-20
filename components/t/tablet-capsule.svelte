<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfh6n882y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rfh6n882y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tablet-capsule" {...props}></Icon>
