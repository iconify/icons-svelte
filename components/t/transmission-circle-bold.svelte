<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saoi0tb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="saoi0tb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:transmission-circle-bold" {...props}></Icon>
