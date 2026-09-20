<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv6f026dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gv6f026dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wifi-horizontal-solid" {...props}></Icon>
