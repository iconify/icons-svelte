<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3z-_y6_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t3z-_y6_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:virtual-reality-solid" {...props}></Icon>
