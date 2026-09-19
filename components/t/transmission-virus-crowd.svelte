<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toko7hbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="toko7hbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:transmission-virus-crowd" {...props}></Icon>
