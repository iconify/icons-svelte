<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua5sdswjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua5sdswjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:usb-fill" {...props}></Icon>
