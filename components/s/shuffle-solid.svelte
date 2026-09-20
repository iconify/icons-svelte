<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x686wac0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x686wac0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shuffle-solid" {...props}></Icon>
