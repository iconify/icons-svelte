<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9_h0wb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z9_h0wb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:volume-level-off-solid" {...props}></Icon>
