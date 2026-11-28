<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxmsrw0ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxmsrw0ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ruler-solid" {...props}></Icon>
