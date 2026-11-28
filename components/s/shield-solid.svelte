<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmlynwbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmlynwbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shield-solid" {...props}></Icon>
