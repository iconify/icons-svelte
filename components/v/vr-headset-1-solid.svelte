<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jej-03bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jej-03bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:vr-headset-1-solid" {...props}></Icon>
