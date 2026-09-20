<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svie05b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="svie05b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:usb-square-filled" {...props}></Icon>
