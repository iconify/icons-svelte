<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz2ti29gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wz2ti29gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:transmission-square-bold" {...props}></Icon>
