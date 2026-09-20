<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxtibtbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxtibtbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:user-minus" {...props}></Icon>
