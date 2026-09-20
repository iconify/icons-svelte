<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg7_4ub4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vg7_4ub4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sprout-solid" {...props}></Icon>
