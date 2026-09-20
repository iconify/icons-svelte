<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oem3dgbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oem3dgbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:seven-solid" {...props}></Icon>
