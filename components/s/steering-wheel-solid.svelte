<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2vltv_6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r2vltv_6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:steering-wheel-solid" {...props}></Icon>
