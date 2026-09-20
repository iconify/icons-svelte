<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gav4x1b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gav4x1b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:rupee-solid" {...props}></Icon>
