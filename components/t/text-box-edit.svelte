<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb-w5f2ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb-w5f2ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:text-box-edit" {...props}></Icon>
