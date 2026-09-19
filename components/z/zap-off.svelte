<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2_kfxf2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2_kfxf2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:zap-off" {...props}></Icon>
