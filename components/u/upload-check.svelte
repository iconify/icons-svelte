<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxf9_mbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxf9_mbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:upload-check" {...props}></Icon>
