<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obc4b9b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obc4b9b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wireshark" {...props}></Icon>
