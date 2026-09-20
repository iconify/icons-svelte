<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exb_8omph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="exb_8omph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:surveillance-camera-solid" {...props}></Icon>
