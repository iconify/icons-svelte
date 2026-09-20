<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgu11uvkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgu11uvkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:xuanyuan" {...props}></Icon>
